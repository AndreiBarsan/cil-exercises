# CIL Lecture Notes

## Overview

This folder contains Jupyter notebooks with study notes for the Computational Intelligence Lab at ETH Zurich.
As in [my Data Mining note repository][0], these notes come with **absolutely NO guarantee of correctness or completeness**.


## Viewing the notes

Please use [Jupyter][1] for viewing and interacting with the notebooks. The PDF previews on GitHub don't seem to be rendered too great, especially in Firefox.

With Jupyter installed, running this in the project root should do the trick:

```bash
jupyter notebook
```

Using a Python virtual environment such as virtualenv or Anaconda is highly recommended.
There's no `requirements.txt` because Anaconda tends to put a lot of extra unnecessary stuff in it.
Installing some basic ML libraries in addition to the main Jupyter installation (`numpy`, `scikit-learn`, `scipy`) should get you going.
Some tiny stuff may depend on [TensorFlow][2], but you can probably skip those if you're not interested in installing TF, without losing too much insight.


## License

These notes are Public Domain.


[0]:https://github.com/andreibarsan/dm-notes
[1]:http://jupyter.org/
[2]:tensorflow.org