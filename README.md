#ml_projects

Steps to install pandas on a M1 chip:
1) pip3 install cython
2) OPENBLAS="$(brew --prefix openblas)" MACOSX_DEPLOYMENT_TARGET=11.1 pip3 install numpy --no-use-pep517
3) OPENBLAS="$(brew --prefix openblas)" MACOSX_DEPLOYMENT_TARGET=11.1 pip3 install pandas --no-use-pep517
