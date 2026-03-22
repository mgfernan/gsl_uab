# Localization systems

This repository contains code snippets as well as datasets to be used in the UAB's course "Geodèsia i Sistemes de Localització" (GSL)

Start here 👇

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mgfernan/gsl_uab/HEAD)

This will open a tab with Binder, a virtual environment where to launch the notebooks present in this repository.
As an alternative means to execute them, you will find `Colab` links in each notebook, which will open up a
Google's Colab session (but you will need a Google Account to run the code)

If the Binder link seems stuck, try to clear the web browser cache (this will remove the local container image stored in the
browser cached data)

## Book

The book is built using `quarto`. To have a live-preview of the book

```bash
cd book
quarto preview
```

To create a static version of the book

```bash
quarto render book
```