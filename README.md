# KLab Cyscorpions | Python Course

![KLab Cyscorpions](./cyscorpions_logo.png)

> [Python Course Site](http://python.cyscorpions.com/) [Github](https://github.com/KLabCyscorpions/python-course) [Twitter](https://twitter.com/klabcyscorpions) [Instagram](https://instagram.com/klabcyscorpions/) [KLab Cyscorpions](http://www.cyscorpions.com)

Feb 1, 2016

These Jupyter notebooks serve as the Klab Cyscorpions Python Course. We are making them publicly available for anyone interested in learning Python. Feel free to clone or fork the repo for your own use. If you're not a programmer, you'll still find it easy to follow but there may be some things that require some research on your part.

If you feel that something can be improved, please open an issue with the notebook name in the title for easy identification.

We welcome pull requests! We'll also appreciate if you give the repository a star :)

The requirements for using these notebooks are:

* Python 3.x
* pip
* Jupyter
* git


## Python

There are 2 versions of Python, Python 2 and Python 3. __We'll use Python 3__.

If you don't have __Python 3__ installed yet, please download it from [Python.org](https://www.python.org/).

You can check if Python is installed by typing `python` in the command line. If it goes to the Python interpreter, then you already have Python installed. You can check the version from the very first line after your command. You should see something like:

```
Python 3.5.1 (default, Dec  7 2015, 11:24:55)
Type "copyright", "credits" or "license" for more information.
>>>
```

This says the Python version used is 3.5.1.


## Pip

If you already have Python installed, make sure you have the python package manager, __pip__. If you need to install pip, just follow the instructions from the [pip documentation](https://pip.pypa.io/en/stable/installing/).

You can check if pip is installed by typing `pip` in the command line. If it gives you the help screen, then you already have pip:

```
Usage:   
  pip <command> [options]

Commands:
...
```

If you have both versions of Python installed, the `pip` command installs for your default installation. You can use the `pip3` command to make sure you're installing it for Python 3.


## Jupyter

Then just `pip3 install jupyter`. Please refer to the [Jupyter documentation](http://jupyter.readthedocs.org/en/latest/install.html#using-pip) if you encounter any problems.

> __Note:__
> Some of Jupyter’s dependencies may require compilation, in which case you would need the ability to compile Python C-extensions. This means a C compiler and the Python headers. On Debian-based systems (e.g. Ubuntu), you can get this with:
> `apt-get install build-essential python3-dev`
> And on Fedora-based systems (e.g. Red Hat, CentOS):
> `yum groupinstall 'Development Tools'`
> `yum install python3-devel`
> (Use python instead of python3 for legacy Python 2.)


## Git

We assume you already have `git` installed. Just in case you don't, please refer to the instructions in the [Git documentation](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

Once you already have Jupyter installed, you just need to clone this repository by typing:

`git clone https://github.com/KLabCyscorpions/TrainingNotebooks.git`

Enter your github credentials when asked and you should have a local copy of the repository. 

## Notebook

To open the notebooks, just type `jupyter notebook`. You should be redirected to a browser page with links to folders of training notebooks.

Browse the TrainingNotebooks subdirectories. Notebooks have a `.ipynb` extension.

Topics are arranged in order.

While the notebooks are viewable in GitHub, you are encouraged to clone the repo locally and play with the code. :)

Have fun! :)


[![Creative Commons License](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)  
This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).