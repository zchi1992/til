# Python

## python setup
1. Download latest python using one of below approaches
    - On MacOS, install Homebrew and run below command. This will install latest python version using brew formula
    ```
    brew install python
    ```
    if you need to install a specific python version, run
    ```
    brew install python@[version]
    ```
    - On Linux, [adding details here]
2. Alway creating a virtual environment for python projects to manage python version and packages for differen t projects
3.  

## virtual environment setup

## Python package management
### pip with proxy
Be careful about `all_proxy` and `ALL_PROXY` setup in `.bashrc` file.

## Python module 
`__all__` controls what could be imported from a module via `from module import *`

## Python type hinting
[Youtube: Type Hints - Guido van Rossum - PyCon 2015](https://www.youtube.com/watch?v=2wDvzy6Hgxg)

[What are type hints in Python 3.5?](https://stackoverflow.com/questions/32557920/what-are-type-hints-in-python-3-5/32558710#32558710)

## Python useful packages
### `argparse` module to write user-friendly command line interfaces

```
## basic usage
parser = argparse.ArgumentParser(description='This is a test for argparse')
parser.add_argument('first', type=int, help='this is the first arg')
parser.add_argument('second', type=int, help='this is the second arg')
args = parser.parse_args()
```

### `pathlib` module offers classess representing file system paths for different operating systems

### `multiprocessing` is python concurrency package that supports both local and remote concurrency

* Process Pools

## Python Global Interpret Lock(GIL)



