Matplotlib for HEP Jupyter Book

You can build this book locally on the command line following these steps:

1. Install [Anaconda](https://www.anaconda.com/products/distribution)

2. Install Jupyter Book using conda

```
conda install -c conda-forge jupyter-book
```

3. Create a new environment and activate it

```
conda create --name jupyter_book
conda activate jupyter_book
```

4. Clone the repository containing the book source files

```
git clone git@github.com:amorenobr/matplotlib_for_hep_jb.git
```

5. Build your Jupyter Book

```
jb build --all matplotlib_for_hep_jb
```

6. View the Jupyter Book in a browser

```
google-chrome-stable _build/html/index.html
```
