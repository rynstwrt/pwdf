## Useful Tutorial
[This is a helpful tutorial](https://www.geeksforgeeks.org/command-line-scripts-python-packaging/) about how to make python packages executable as terminal commands.

<br>

## Building and Installing
**Create a dynamic package for development: `python setup.py develop`**

**Test install:** `python setup.py install`

**Build distributions:** `python setup.py sdist bdist_wheel`

**Install distributions:** `pip install dist/pwdf-<version>-py2.py3-none-any.whl`

<br>

## Distributing
### To upload a package to PyPI:
- Must have an account on PyPI
- Must have twine installed `pip install twine`
- `twine upload dist/*`