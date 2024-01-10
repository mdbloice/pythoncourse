[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa] 

# Python for Machine Learning and Data Science

Materials for the "Python in Machine Learning" PhD course offered at the Medical University Graz.

## Installing Python & Jupyter

To install Python, follow the instructions on [python.org](https://python.org) - note that the instructions vary by operating system. 

Oncee you have installed Python, you can install Jupyter, and all the requirements for this course, by first downloading the `requirements.txt` file from this repository and running:

```sh
pip install -r requirements.txt
```

from the command line. This will install Jupyter and all other requirements that are listed in the `requirements.txt` file.

Alternatively, you can install the requirements by copying and pasting the following in to the command line:

```
pip install ipython jupyter numpy pandas scikit-learn xgboost matplotlib biopython scipy pillow opencv-python
```

Once you have installed Jupyter, you can run the following to start a local Jupyter server which will open in the default browser:

```sh
jupyter lab
```

If a browser window does not open automatically, you will need to copy the URL printed to the console and open this in a browser. Typically this URL is [http://localhost:8888](http://localhost:8888)

**Note**: it is good practice to create a virtual environment for every project that you create, if you wish to do so, see the Python `venv` command, detailed instructions can be found here: [https://docs.python.org/3/library/venv.html](https://docs.python.org/3/library/venv.html) - however, for the purposes of this course it is not a requirement that you use a virtual environment.

## Online Alternatives

If you cannot install Python locally for whatever reason, you can use Google Colab as an alternative. See [https://colab.research.google.com](https://colab.research.google.com) - you will need a Google account to use this service.

Note that the [modul17.com](https://modul17.com) server does not run outside of the seminar class times.

# License

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

You are free to:

- Share — copy and redistribute the material in any medium or format for any purpose, even commercially.
- Adapt — remix, transform, and build upon the material for any purpose, even commercially.
- The licensor cannot revoke these freedoms as long as you follow the license terms.

Under the following terms:

- Attribution — You must give appropriate credit , provide a link to the license, and indicate if changes were made . You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
- No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.
