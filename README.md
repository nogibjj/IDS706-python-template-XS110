
## Template for Python projects 

## Goal

This template is to provide a good source to make it work for the new project and reduce the time to create a new one from scratch. It is wise to automate this process and it will save us time.


## Files

In this template, it includes the following files:

- ``.devcontainer`` includes a Dockerfile and devcontainer.json.
                The 'Dockerfile' within this folder specifies how the container should be built, and devcontainer.json file specifies the development environment settings for Github Codespaces.

- ``workflows`` includes GitHub Actions, which contain configuration files for setting up automated build, test, and deployment pipelines for your project.

- ``.gitignore`` is used to specify which files or directories should be excluded from version control when using Git.

- ``Makefile`` is a configuration file used in Unix-based systems for automating tasks and building software. It contains instructions and dependencies for compiling code, running tests, and other development tasks.

- ``README.md`` is the instruction file for the readers.

- ``main.py`` is a Python file.

- ``requirements.txt`` is to specify the dependencies (libraries and packages) required to run the project.

- ``test_main.py`` is a test file for main.py that can successfully run in IDEs.

- ``img`` saves the running results.


Then use ``make install`` to install libraries and packages and run ``make test`` to run the test in ``Makefile``. Similarly, run ``make format`` and ``make lint``.

## Results

This template is a way of initializing and maintaining Python repositories, and make it easy for development.

The ``Makefile`` provides a set of commands to simplify common development tasks. In particular, it includes a ``make install`` command that can be custumized to install the project's libraries and packages, and a make test command that can be customized to run the project's tests. When used in combination with GitHub Actions, it automates the testing process for code.

The ``.devcontainer`` configuration file is used to ensure that everyone working on the project uses a consistent development environment. This helps avoid issues related to different system configurations. And it easily set up a development environment using GitHub Codespaces.

## Reference

https://github.com/carrieli15/706-Data-Engineering-Template
https://github.com/nogibjj/python-template
