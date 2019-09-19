# Intro to Neural Networks

### Instalations

#### Python 3

This is an intro to Neural networks. To run the code on your own machine you will need to have python 3 installed. If you do not currently have it installed, install it and make sure that the `Add to path` option is checked. 

When you have python 3 installed on your machine you can find yourself a terminal and run the following command

```
python3
```

To see if you have installed it correctly.

#### Pipenv

You will also need to have pipenv on your machine. To get this open a terminal and run

```
python3 -m pip install pipenv
```

This will install the pipenv package on your computer. On windows you might also have to run the following comand where you have swapped `USERNAME` with your username in a power shell

```
set PATH=%PATH%;
set PATH=%PATH%;'c:\users\Username\appdata\local\programs\python\python36-32\Scripts'
```

### Run
Download the zip file for this project and place it somewhere on your computer and unzip it. Then open a terminal and change the directory to the folder where you placed the files. In that terminal run the following comands. Wait untill one is done before running the next.

```
pipenv shell
pipenv install

python -m ipykernel install --user --name=neural-network

jupyter notebook
```
You should now have a browser window with the code available.


