# python3 examples/tutorials

## more information can be found at [python](https://python.org) website.

I will add tons of examples that progressively get more complicated. I will also store examples of features of the standard library in these examples. If you see any issues with anything please make a pull request.

When people say they know python on a resume or on an interview...Do they
really know it?  You should know most of the concepts below.

### notebook examples
| File Names                        | Binder Links |
| ----------------------------------|:------------:|
| 0001_introduction.ipynb           | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/thesheff17/pythonexamples/master?filepath=src%2F0001_introduction.ipynb) |
| 0002_strings.ipynb                | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/thesheff17/pythonexamples/master?filepath=src%2F0002_strings.ipynb) |
| 0003_numbers.ipynb                | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/thesheff17/pythonexamples/master?filepath=src%2F0003_numbers.ipynb) |
| 0004_lists_and_tuples.ipynb       | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/thesheff17/pythonexamples/master?filepath=src%2F0004_lists_and_tuples.ipynb) |
| 0005_dict.ipynb                   | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/thesheff17/pythonexamples/master?filepath=src%2F0005_dict.ipynb) |
| 0006_boolean.ipynb                | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/thesheff17/pythonexamples/master?filepath=src%2F0006_boolean.ipynb) |
| 0007_file_manipulation.ipynb      | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/thesheff17/pythonexamples/master?filepath=src%2F0007_file_manipulation.ipynb) |
| 0008_error_handling_logging.ipynb | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/thesheff17/pythonexamples/master?filepath=src%2F0008_error_handling_logging.ipynb) |  
| 0009_classes.ipynb                | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/thesheff17/pythonexamples/master?filepath=src%2F0009_classes.ipynb) |
| 0010_arg_parser.ipynb             | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/thesheff17/pythonexamples/master?filepath=src%2F0010_arg_parser.ipynb) |


### running this locally
* you should run this inside a virtualenv setup.  A virtualenv is an isolated area to install 3rd
  party tools using what is in requirements.txt. pip is the package manager to install 3rd party
  tools for python.
* Each platform is different.  You can learn more about it [here](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)
* once you have the python virtualenv activated we want to clone the repo:
```bash
git clone git@github.com:thesheff17/pythonexamples.git
```
* now lets install the packages:
```bash
cd pythonexamples
pip install -r requirements.txt
```
* you can always see what packages are installed with:
```bash
pip freeze
```
* now run the juypter notebook:
```bash
cd src
juypter notebook
```

### how does this work?
* [jupyter](https://jupyter.org/)
* [docker](https://docker.com/)
* [python](https://python.org/)
* [binder](https://mybinder.org/)
