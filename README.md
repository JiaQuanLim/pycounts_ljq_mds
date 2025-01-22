# pycounts_ljq_mds

[![codecov](https://codecov.io/gh/JiaQuanLim/pycounts_ljq_mds/graph/badge.svg?token=4QD8O22FS6)](https://codecov.io/gh/JiaQuanLim/pycounts_ljq_mds)

Calculate word counts in a text file!

Author: JiaQuanLim

## Installation

```bash
$ pip install pycounts_ljq_mds
```

## Usage

`pycounts_ljq_mds` can be used to count words in a text file and plot results
as follows:

```python
from pycounts_ljq_mds.pycounts_ljq_mds import count_words
from pycounts_ljq_mds.plotting import plot_words
import matplotlib.pyplot as plt

file_path = "test.txt"  # path to your file
counts = count_words(file_path)
fig = plot_words(counts, n=10)
plt.show()
```

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`pycounts_ljq_mds` was created by jiaquanlim. It is licensed under the terms of the MIT license.

## Credits

`pycounts_ljq_mds` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
