# pwdf
A terminal command (Python module) to get the path of a file (pwd for files instead of directories).

**PyPI Package:** [View pwdf on PyPI here.](https://pypi.org/project/pwdf/)

<br>

## Installing
`pip install pwdf`

<br>

## Usage
`pwdf <relative file path>`

### Example:
```shell
foo@bar:~$ pwdf testfile.json
/Users/ryn/Documents/testfiles/testfile.json
```

<br>

## Building and Installing From Source
**Test install:** `python setup.py install`

**Build distributions:** `python setup.py sdist bdist_wheel`

**Install distributions:** `pip install dist/pwdf-<version>-py2.py3-none-any.whl`