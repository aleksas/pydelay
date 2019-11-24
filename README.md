# pydelay
experimental fork of the original pydelay sourceforge project

A very easy to use framework for delay dynamical system

# The required dependencies for pydelay are:

Python 2.4 or higher

weave for python 2.4 or higher

# install weave using : 

pip install weave 

# install pydelay using linux 

python setup.py install

# install pydelay using windows 

Install Visual Studio 2017 & Visual Studio C++ Build Tool 2015 at

http://landinghub.visualstudio.com/visual-cpp-build-tools

Update Conda

conda update conda

conda update --all

check the dependencies
pip install setuptool

conda install numpy cython matplotlib scipy pandas

Install gcc compiler components

conda install libpython m2w64-toolchain -c msys2

created distutils.cfg file inside Anaconda3\Lib\distutils folder with the following:

[build]
compiler = mingw32

Download Git at https://git-scm.com/downloads
git clone https://github.com/liedji/pydelay.git

Compile from the source code

python setup.py build --compiler=mingw32
python setup.py install

P.S. The solution for the issue: Cannot build msvcr library: "vcruntime140d.dll" not found.

Copy vcruntime140d.dll from C:\Windows\System32 to any folder, which is reachable in the path in the advanced system settings/environment variables/ system variables.

For more details on windows installation refer to the following link:

https://stackoverflow.com/questions/34363477/pystan-compileerror-command-gcc-failed-with-exit-status-1-windows?rq=1

 enjoy !!
