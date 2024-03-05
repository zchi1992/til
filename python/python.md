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

## Python language features
### generator

## Python module 
`__all__` controls what could be imported from a module via `from module import *`

## Python type hinting
[Youtube: Type Hints - Guido van Rossum - PyCon 2015](https://www.youtube.com/watch?v=2wDvzy6Hgxg)

[What are type hints in Python 3.5?](https://stackoverflow.com/questions/32557920/what-are-type-hints-in-python-3-5/32558710#32558710)

## Python useful packages
### String/Regex/Unicode operation related: `re`, `unicodedata`, `regex`
`translate()` is fast for nontrivial character-to-character remapping or deletion

### Date/Time/Calendar related: `calendar`
### System/OS related: `sys`, `os`

### `collections`
__defaultdict__ class is almost same as built-in __dict__ class except __defaultdict__ has default values for keys thus won't raise a __KeyError__

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
* `class multiprocessing.pool.AsyncResult`

### `asyncio` 
[Learn Python's AsyncIO - a deep dive on AsyncIO ecosystem](https://www.youtube.com/playlist?list=PLhNSoGM2ik6SIkVGXWBwerucXjgP1rHmB)  

__important concepts__:  
* `async` introduces a native coroutine or an asynchronous generator
* `await` passes function control back to the event loop
* coroutine  
 coroutine is a function that can suspend its execution before reaching return, and it can indirectly pass control to another coroutine for some time.
* Task  
`asyncio.create_task()`  
* Event Loop  
`asyncio.get_running_loop()` returns current running loop in the current OS thread  
`loop.call_at()` schedules _callback_ to be called at the given absolute timestamp _when_
* `DatagramTransport`  
A transport for datagram (UDP) connections.
* `Coroutine`  
[A great example about how to use corouting via asyncio](https://docs.python.org/3/library/asyncio-task.html#coroutine)
* `asyncio.Handle`
A callback wrapper object to cancel the callback later

### `mmap`
* Memory-Mapped Files  
[File I/O with memory mapping using Python mmap](https://www.youtube.com/watch?v=ky1n6luzL3Y)  
Note: mmap operates in a byte manner  

### `threading`
* Thread  
* Daemon Thread

### `signal`
Python signal handler package

### `matplotlib`

## Python Class
* What Is `__slots__` ? The __slots__ declaration allows us to explicitly declare data members, causes Python to reserve space for them in memory, and prevents the creation of __dict__ and __weakref__ attributes. It also prevents the creation of any variables that aren't declared in __slots__.

## Python Global Interpret Lock(GIL)

## Python Concurrency

## Some useful python reference websites/blogs
* [Real Python](https://realpython.com/)


