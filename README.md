# Machine learning and data science course

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/jakevdp/PythonDataScienceHandbook/master?filepath=notebooks%2FIndex.ipynb)
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/Index.ipynb)

This repository contains the entire [Python Data Science Handbook](http://shop.oreilly.com/product/0636920034919.do), in the form of (free!) Jupyter notebooks.

![cover image](notebooks/figures/PDSH-cover.png)

## How to Use this Course

- Read the tutorials and lecture notes entirety available online online at https://tejshahi.github.io/beginner-machine-learning-course/

- Run the code using the Jupyter notebooks available in this repository's [notebooks](notebooks) directory.

- Launch executable versions of these notebooks using [Google Colab](http://colab.research.google.com): [![Colab](https://colab.research.google.com/assets/colab-badge.svg)]

- Regester here (www.mountech.com.np) for live training class.

## About

All notebooks are written and tested with Python 3.8, though other python version should work fine but not guranted.

The course covers the core packages that includes: [Python](http://python.org/), [NumPy](http://numpy.org), [Pandas](http://pandas.pydata.org), [Matplotlib](http://matplotlib.org), [Scikit-Learn](http://scikit-learn.org), and [seaborn] (https://seaborn.pydata.org/) packages.
There is no pre-assumption for this course. Anyone can start with this. However if you need a introduction to the python itself, see the free companion project,
[A Whirlwind Tour of Python](https://github.com/jakevdp/WhirlwindTourOfPython): it's a fast-paced introduction to the Python language aimed at researchers and scientists.

## Software

The packages I used to run the code in the book are listed in [requirements.txt](requirements.txt) (Note that some of these exact version numbers may not be available on your platform: you may have to tweak them for your own use).
To install the requirements using [conda](http://conda.pydata.org), run the following at the command-line:

```
$ conda install --file requirements.txt
```

To create a stand-alone environment named ``PDSH`` with Python 3.5 and all the required package versions, run the following:

```
$ conda create -n PDSH python=3.5 --file requirements.txt
```

You can read more about using conda environments in the [Managing Environments](http://conda.pydata.org/docs/using/envs.html) section of the conda documentation.


## License

### Code
The code in this repository, including all code samples in the notebooks listed above, is released under the [MIT license](LICENSE-CODE). Read more at the [Open Source Initiative](https://opensource.org/licenses/MIT).

### Text
The text content of the book is released under the [CC-BY-NC-ND license](LICENSE-TEXT). Read more at [Creative Commons](https://creativecommons.org/licenses/by-nc-nd/3.0/us/legalcode).
