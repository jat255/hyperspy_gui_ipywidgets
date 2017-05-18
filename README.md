# hyperspy_gui_ipywidgets
[![Build Status](https://travis-ci.org/hyperspy/hyperspy_gui_ipywidgets.svg?branch=master)](https://travis-ci.org/hyperspy/hyperspy_gui_ipywidgets)



**hyperspy_gui_ipywidgets** provides ipywidgets graphic user interface (GUI) elements for hyperspy.


## Installation

# Option 1: With pip
Make sure you have
[pip installed](https://pip.pypa.io/en/stable/installing/) and run:

```bash
pip install hyperspy_gui_ipywidgets
```

# Option 2: With Anaconda

Install anaconda for your platform and run

```bash
conda install hyperspy_gui_ipywidgets -c conda-forge

```

## Running the tests

py.test is required to run the tests.

```bash
pip install "hyperspy_gui_ipywidgets[test]"
py.test --pyargs hyperspy_gui_ipywidgets
```

## Usage

Please refer to the [HyperSpy documentation](http://hyperspy.org/hyperspy-doc/current/index.html) for details. Example:

```python

import hyperspy.api as hs
hs.preferences.gui(toolkit="ipywidgets")
```

## Development

Contributions through pull requests are welcome. See the
[HyperSpy Developer Guide](http://hyperspy.org/hyperspy-doc/current/dev_guide.html).
