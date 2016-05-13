# pycon2016-django

My GitHub repository that can be used by other participants in the tutorial for getting set up. This repository is intended for use by participants who use the Anaconda distribution of Python.

## using the repo

Fork this repository to your own GitHub account.

Clone the repository to disk.

    $ git clone https://github.com/[username]/pycon2016-django
    $ cd pycon2016-django

To create an environment using the `conda` package manager, I have provided an `environment.yml` file, which can be read by the `conda` package manager. 

    $ conda create -f environment.yml

If you have Christine Doig's [`conda-auto-env`][1], then when you enter into the directory, you will have an environment automatically set up. Beyond the initial setup, your terminal will automatically switch into the new environment each time you enter into the directory.

[1]: http://github.com/chdoig/conda-auto-env