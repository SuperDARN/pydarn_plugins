# pyDARN Plug-Ins

The pyDARN Plug-In repository is for packages developed outside the core pyDARN functionality for use with pyDARN and pyDARNio.

## Installing a Package

Each top level directory within this repository is a separate package developed for use with pyDARN. 
To install a package, you can clone this repository, move into the package that you would like to install and then install from the package. 
You can do this by:
```
git clone https://github.com/SuperDARN/pydarn_plugins.git

cd pydarn_plugins/package_name/

pip3 install .
```
After making sure your package has been installed correctly and is working, you may delete the clone of the git repository.

## Making Your Own Package

pyDARN Plug-Ins has a package called `template` which you can start from. 
`template` contains an outline for all the required files so that the package can be installed and used with pyDARN.

