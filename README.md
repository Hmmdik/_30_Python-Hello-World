Hello, World
============

A simple program, and an example of how to structure a python project. Demonstrates a basic package
file structure and a way to define a single package version. shared between
package metadata and program runtime.



Basic usage
-----------

You can install the package using `pip` and then run the main script from the command line as
`helloworld_in_python` or import it in python via `import helloworld`:

```shell
$ cd python-helloworld/  # Dir containing this repo's root
$ pip install .
$ helloworld_in_python
Hello, world
$ helloworld_in_python --version
helloworld 0.1
$ python
>>> import helloworld
>>> helloworld.__version__
'0.1'
```

You can also try it without installing by running `python helloworld.py` in the repository root:

```shell
$ python helloworld.py
Hello, world
$ python helloworld.py --version
helloworld 0.1
```
