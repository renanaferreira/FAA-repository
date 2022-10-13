# Jupyter Notebook

The Jupyter Notebook is an incredibly powerful tool for interactively developing and presenting data science projects

## What is a Notebook?

A notebook integrates code and its output into a single document that combines visualizations, narrative text, mathematical equations, and other rich media. In other words: it’s a single document where you can run code, display the output, and also add explanations, formulas, charts, and make your work more transparent, understandable, repeatable, and shareable.

Using Notebooks is now a major part of the data science workflow at companies across the globe. If your goal is to work with data, using a Notebook will speed up your workflow and make it easier to communicate and share your results.

### Requisites
* Python Language
* Pandas Library

## Installation
1. Install Anaconda

Anaconda is the most widely used Python distribution for data science and comes pre-loaded with all the most popular libraries and tools.


2. Install Jupyter
```
$ pip3 install jupyter
```

## Creating Your First Notebook

### Running Jupyter
In Linux
1. Activate conda base environment
```
$ conda activate
```
2. Run Jupyter application/platform
```
$ (base) jupyter notebook
```
It will open a python server in localhost:8888. This is the Notebook Dashboard, specifically designed for managing your Jupyter Notebooks.
3. Go to the folder you want to create your notebook and click in the new button and choose python3.

#### Warning: The tutorial presented a python3 module, mine presented a python3(ipykernel)

### What is an ipynb File?
The short answer: each .ipynb file is one notebook, so each time you create a new notebook, a new  .ipynb file will be created.

The longer answer: Each .ipynb file is a text file that describes the contents of your notebook in a format called JSON. Each cell and its contents, including image attachments that have been converted into strings of text, is listed therein along with some metadata.

You can edit this yourself — if you know what you are doing! — by selecting “Edit > Edit Notebook Metadata” from the menu bar in the notebook. You can also view the contents of your notebook files by selecting “Edit” from the controls on the dashboard

However, the key word there is can. In most cases, there’s no reason you should ever need to edit your notebook metadata manually.

### The Notebook Interface

There are two fairly prominent terms that you should notice, which are probably new to you: *cells* and *kernels* are key both to understanding Jupyter and to what makes it more than just a word processor. Fortunately, these concepts are not difficult to understand.

* A **kernel** is a “computational engine” that executes the code contained in a notebook document.
* A **cell** is a container for text to be displayed in the notebook or code to be executed by the notebook’s kernel.

### Cells
We’ll return to kernels a little later, but first let’s come to grips with cells. Cells form the body of a notebook. In the screenshot of a new notebook in the section above, that box with the green outline is an empty cell. There are two main cell types that we will cover:

* A code cell contains code to be executed in the kernel. When the code is run, the notebook displays the output below the code cell that generated it.
* A Markdown cell contains text formatted using Markdown and displays its output in-place when the Markdown cell is run.

The first cell in a new notebook is always a code cell.

#### Warning: From this point I prefered not to write everything here. For more information, go to [Jupyter Tutorial](https://www.dataquest.io/blog/jupyter-notebook-tutorial/)
