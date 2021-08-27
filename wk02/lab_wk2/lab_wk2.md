---
jupytext:
  formats: ipynb,md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.10.3
kernelspec:
  display_name: Python 3 (ipykernel)
  language: python
  name: python3
---

# Lab Week 2 - Jupyterhub Tutorial

## EOSC 211

### Learning Objectives

- Connect to Jupyterhub via the course website
- Explain what an IDE is.
- Execute code cells to do some easy calculations
- Assign data to *variables* 
- Use comments and/or *markdown* cells to add annotations code
- Save your work and submit an assignment via Canvas

+++

### Intro

Welcome to your first lab in **EOSC 211**! Here we will write our first bits of *Python* code, explore some of the features of *Jupyter Notebooks*, and learn how to save and submit your work for grading. 

#### Why Python/Jupyterhub?

Python is a *high level programming language,* meaning it is comparatively easy for humans to read. Python programs are executed by a *python interpreter,* which takes python code, reads it into a processor (the CPU on your computer, or in our case, a Jupyterhub server) and returns a result. 

Python is also *open source*, meaning that ... there are many add ons (called *packages*) developed specifically for the type of scientific programming we want to do in this course

Jupyterhub is an IDE, or *integrated development environment* which has gained popularity amoung the science community for processing data, creating scientific figures, and solving numerical equations. There are many IDE's available 

syntax highlighting

no installation required

+++

### Code Cells and Markdown Cells

Jupyter notebooks are divided into *cells,* which can be individually edited and run. To create a new cell, click `Insert` $\rightarrow$ `Insert Cell Below`, or press `alt` + `enter` to run the current cell and create a new one below. After you create a cell, you can choose either *Code* or *Markdown* as the cell type. 

<img src=insert_new_cell.png width=180><img src=cell_type.png width=150>

#### Code Cells

Code cells are where you can write, edit, and run *Python Code.* Text entered into code cells will be shown with *syntax highlighting,* with python *reserved words* shown in green, *strings* shown in red, and *comments* in blue. You can execute code cells by pressing [$\blacktriangleright$ Run], or `[Ctrl]` + `[Enter]` (execute current cell), `[Shift]` + `[Enter]` (run current cell and select the next one), or `[Alt]` + `[Enter]` (execute current cell and create a new one below).

Try it yourself! Edit the cell below, replacing the comment (lines of code beginning with "#" are ignored by the python interpreter and not executed) with:

```python
print("Hello World")
```

and press `[Ctrl]` + `[Enter]` to execute the code. 

```{code-cell} ipython3
# your code here
```

Congratulations, you have just run your first Python code! (The "Hello World" program is a long-standing tradition in computer programming as a first program in a new language). 

Python has much more capability than just printing "Hello World". You can write multiple lines of code in one cell, the *python interpreter* will execute each line of code in the order it appears, i.e.

```{code-cell} ipython3
print("Hello Earth")
print("Hello Ocean")
print("Hello Atmpsphere")
```

You can also store data as *variables*, and reference them throughout your code, like so:

```{code-cell} ipython3
planet = "Earth"
```

This tells the python interpreter: "find some space in computer memory, store the word "earth" there, and reference that word with a variable called *planet*. Throughout the rest of your code, the calling the variable "planet" will result in the word "earth". If you change the variable (maybe to "Betelgeuse"), every reference to that variable will now produce "Betelgeuse". Clever use of variables can save you time hunting through your code and replacing every instance of a word/number/value.

```{code-cell} ipython3
print("Welcome to " + planet)
print("Nice weather today here on " + planet)
print(planet + " will soon be destroyed by the Vogons to make space for the new interstellar highway.")
```

#### Cell Execution Order

Within a cell, lines of code are executed in the order they are written. Code cells will execute in any order you decide. The order in which cells are executed appears to the left e.g. `In [10]` indicates that a particular cell is the tenth cell to be run in the notebook. Try executing the cells below in order:

* cell 1, cell 2, cell 3
* cell 3, cell 2, cell 1

Which value for `my_field` gets printed to the screen in either case? 

```{code-cell} ipython3
# cell 1
my_field = "oceanography"
```

```{code-cell} ipython3
# cell 2
print(my_field + " is awesome!")
```

```{code-cell} ipython3
# cell 3
my_field = "atmospheric science"
my_field = "geology"
```

Finally, press the \[$\circlearrowright$\] button to *restart the kernel* and try executing cell 2 again. What happens? Restarting the kernel tells the python interpreter to forget all variables and start over from scratch. The \[$\blacktriangleright\blacktriangleright$\] button restarts the kernel and executes each cell in order (top to bottom). 

<div class="alert alert-danger" role="alert">
  <strong>Important: </strong> When your instructors mark a submitted notebook, all cells will be executed in order. Before you submit, run the whole notebook and make sure it produces the result you want
</div>


Try it out! Edit the cells above (create new cells or copy/paste lines of code) so that when you press \[$\blacktriangleright\blacktriangleright$\], the resulting output is:

```
atmospheric science is awesome!
```

+++

#### Math in Python

Python also 

+++

## To Hand In

Write your answers in the cells below and submit your lab via Canvas

+++

**Why are you interested in taking this course? (double click to edit the markdown cell below, `ctrl` + `shift` to render)**

+++

your answer here

+++

## Helpful Terminology

**Python:** a high level programming language popular among scientists. Python code is saved with the extension `.py` and can be run on any computer with a python interpreter installed on it. We are using version the *miniconda distribution, version 3.7* for this course.

**Jupyter Notebooks:** an *Integrated Development Environment* for writing python code that runs in a web browser (i.e. Chrome, Firefox). Notebooks are comprised of cells, which are either executable python code or rendered markdown text. Notebooks contain and execute python code, but are saved with the extension `.ipynb`

**Jupyterhub:** a *computational environment* for running jupyter notebooks in the cloud, designed specifically for applications like teaching or collaborative research. The EOSC211 course hub is available online and requires no installation on your own machine. Later in the course, we will talk about installing python yourself and developing your own individual workflow.
