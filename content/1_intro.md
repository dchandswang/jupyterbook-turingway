# Introduction

This is the *Jupyter Book 2 Workshop Template,* designed to quickly and easily produce your own online interactive textbook as well as a high quality PDF enabled with Typst using [Jupyter Book 2](https://next.jupyterbook.org/) technology.

This template:
- provides a ready-to-use Jupyter Book 2 structure for creating an online book (i.e., website),
- includes a number of lessons to get started understanding key components of a book and how to edit it,
- includes a GitHub Action workflow to automatically build and deploy your book online,
- provides instructions for generating a high quality PDF with Typst using a ready-to-go template, then deploy it online automatically using GitHub Actions.


Hence, the template allows you to engage with JB2 (and the underlying software MyST) _without installing any software on your own computer._ You only need a web browser and a GitHub account (we provide details on how to work locally on your own computer). For those who are comfortable installing software locally (i.e., with a CLI) and/or do not want to use the template book structure, use the [Advanced Start](./advanced_start.md) instructions, denoted with red hot 🌶.

As this document serves both as a template _and_ a guide, it has the following structure:

1. A quick introduction to key Jupyter Book 2, MyST and Markdown concepts.
2. A tutorial with several steps to introduce you to editing and building your own book.
3. Additional resources, for example, [Advanced Start instructions](./advanced_start.md) and [Software](./software.md).

This is an external reference to The Turing Way -> [](xref:th-turing-way)

```{note}
The template and its content are not meant as a replacement of the documentation already available on the [Jupyter Book 2 website](https://next.jupyterbook.org/) and the [MyST website](https://mystmd.org/guide). It is designed to support new users of Jupyter Book 2 and MystMD, in particular for use in workshop settings where participants may not have time or ability to install the required software on a personal computer.
```

:::{myst}
```{warning} Enjoyment Warning!
Once you start building JB2 books, it is likely you will get hooked!
For instance, try changing this cell in the browser and see its output!
```
:::
``` {figure} figures/csuf-campus-scene.jpg
:width: 50%
:name: fig_myfirstfigure
add file in the folder
```

```{iframe} https://youtu.be/cB2BofgejPQ?si=W8QbA7JmNtqqjSLC
:width: 80%

Purves et al. - Jupyter Book 2 0 – A Next Generation tool for sharing for Computational Content
```

``` python
print("Hello world!")
```

``` python
# comment
def fib(n):
    if n < 0:
        return
    if n in [0, 1]:
        return n
    else:
        return fib(n-2) + fib(n-1)
```


```{mermaid}
flowchart LR
  Start --> Stop

  A1(["Novice"]) --> B1
  A2(["I do know"]) --> B2 & B1
  B1(["Expert"])
  B2(["try"])

  A(["Start"]) --> B{"Decision"}
  B --> C["Option A"] & D["Option B"]
```

```{warning} 🌶 HOTHOTHOT
:icon: false
:class: dropdown

This is a custom warning admonition with a custom icon, try changing it!
```
:::: {tab-set}
::: {tab-item} Tab 1
Content for Tab 1
:::
::: {tab-item} Tab 2
Content for Tab 2
:::
::::

:::: {tab-set}
::: {tab-item} pip
pip install mystmd
:::
::: {tab-item} npm
npm install -g mystmd
:::
::::

:::{embed} label
:::