.. part-x documentation master file, created by
   sphinx-quickstart on Wed Jan  5 07:23:12 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Getting Started
====================

Installation
------------
We use the Poetry tool which is a dependency management and packaging tool in Python. It allows you to declare the libraries your project depends on and it will manage (install/update) them for you. Please follow the installation of poetry at https://python-poetry.org/docs/#installation

After you've installed poetry, you can install partx by running the following command in the root of the project:

.. code-block:: python

   poetry install 

Basic Usage
-----------

To run Part-X, we need a black-box function and initialize the parameters of Part-X. Once the black-box function the parameters are passed to the algorith, the algorithm outputs a lot of information including the best point, the statistics and much more. During the course of the algorithm, various files are generated to log the information from the optimizer, store various intermediate representatiosn of the algorithms and files that speed up the process of result generation.
These ideas are explored in detail.

.. toctree::
   :maxdepth: 2

   Inputs
   Outputs

.. _reference_examples: 

Examples
--------
This project provides implementations for four example test functions.

1) Rosenbrock function:

.. code-block:: python

   poetry run python demos/non_linear_rosenbrock.py

2) Himmelblau function:

.. code-block:: python

   poetry run python demos/non_linear_himmelblaus.py

3) Goldstein-Price function:

.. code-block:: python

   poetry run python demos/non_linear_goldstein.py

4) F16 GCAS (from ARCH benchmarks):

.. code-block:: python

   poetry run python demos/arch_benchmarks_f16.py
