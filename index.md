# Programming Abstractions in Python
### Luca de Alfaro
Copyright 2019-21, [Luca de Alfaro](https://luca.dealfaro.com). [License: CC BY-NC](https://creativecommons.org/licenses/by-nc/4.0/)

## Introduction

This is the online textbook Programming Abstractions in Python, written for the class by the same name at the University of California, Santa Cruz. 

The idea of the book, and of the class, consists in teaching students to think about software in terms of objects that have primitive operations.  When confronted with a new problem to solve, one should consider what are the objects that are useful for representing the problem, and what operations can be defined on those objects that solve the problem.  The operations on objects are often best understood as mathematical operations on the set of objects: considering the properties of the operations leads to cleaner, and more general, solutions. 

The book is articulated into five parts:

* **Methods:**  A first part on methods provides a refresher of the Python programming language, and provides an introduction to recursion and generators, topics that are occasionally missing from introductory Python classes. 
* **Structures:** A part on structures shows how solve many interesting problems by designing the appropriate objects and operations. We build a clone of [Pandas](https://pandas.pydata.org/), we introduce data structures for representing subsets of real numbers, we develop a motion detection algorithm for images, and more. 
* **From Symbolic Expressions to Machine Learning:** We introduce the idea of representing expressions via trees, and evaluating them with respect to a variable assignment.  We then develop symbolic differentiation, autogradient, and we build a simplified clone of [PyTorch](https://pytorch.org/).   
* **Graphs and dynamic algorithms:** A part on graphs dynamic algorithms introduces graphs, along with the fundamental algorithsm for graph exploration. We then present some ideas about dynamic solution methods that are fundamental to problem solving in many areas of computer science.
* **Search:** We introduce the fundamental guess-propagate-recur paradigm that is at the core of most search procedures, and we illustrate it on Sudoku and SAT. 

In the course of the book, we will provide simple implementations of well-known problems.  Among other things, we will reimplement the machine-learning framework [PyTorch](https://pytorch.org/), albeit in a simplified pure-Python setting; we will reimplement the core of [Pandas](https://pandas.pydata.org/), and we will write Sudoku and Boolean SAT solvers.  All these implementations will be concise, minimalistic, and yet powerful, and we hope that they can serve as illustration of how to approach non-trivial software and algorithmic problems. 

The book chapters consist in [Jupyter notebooks](https://jupyter.org/).  Jupyter notebooks allow [literate programming](https://www-cs-faculty.stanford.edu/~knuth/lp.html): one can write, in the same place and properly interleaved, both the text and mathematics that explains the high-level concepts, and their implementations into code.  The notebooks provided here form the book.  In these notebooks, exercises appear in two forms: as suggestions, and as holes where code is missing, for students to fill in.  Separately, upon request, are available also teacher versions of the notebooks, where all the code holes have been filled, so that the whole notebook can be run during a classroom lecture. To request these notebooks, email the author at dealfaro@alumni.stanford.edu. 

The author is much indebted to Philippe Bossut for inspiration about the approach, and to Massimo Di Pierro for his many suggestions on topics to cover and methods. 

## Chapters

We provide each chapter as a link to a notebook hosted in [Google Colab](https://colab.research.google.com/). 
For this to work, you might have to visit the [Colab home page](https://colab.research.google.com/) prior to clicking on the links here. 

### Part I: Methods

* [Introduction to Python 3](https://drive.google.com/file/d/1u2JiL4uyXaPbRN1jAHpgbqY1TIWSHtj9/view?usp=sharing)
* [Classes](https://drive.google.com/file/d/1G-DxUTrpH5iwZSrs9DGYzmOkHBIeh5bU/view?usp=sharing)
* [Data structures and their access characteristics](https://drive.google.com/file/d/1yRmE5nCeW0h9_sQy-MRieCZYBLBmY3lE/view?usp=sharing)
* [Recursion](https://drive.google.com/file/d/1ouv7isWK61DA5v0-aXMwkZLPK-ZH8-b-/view?usp=sharing)
* [Generators](https://drive.google.com/file/d/1SST42824TaYjUuXcDa6c_R6kLxE6ZiEs/view?usp=sharing)

### Part II: Structures

* [Counting stacks and queues](https://drive.google.com/file/d/1ZEwT2j4yWMcFsg8uNXV60xK0d5tq3LCy/view?usp=sharing)
* [Sock drawers and arithmetic dictionaries](https://drive.google.com/file/d/1fcd5V9Ykm6e8--ONjMIw60zBQFYpSCJ2/view?usp=sharing)
* [Sparse arrays](https://drive.google.com/file/d/1wiBbhjPdj8X2niE0--S8etEaTfAiTvcA/view?usp=sharing)
* [Data tables](https://drive.google.com/file/d/1cTxt6yhUU1N5kMC5gRnM_lrBV1L9nw4h/view?usp=sharing)
* [Stream averages and motion detection](https://drive.google.com/file/d/1rSTeGDzugEF02gwP_wEslkY1BkTwEcaH/view?usp=sharing)
* [An interval algebra](https://drive.google.com/file/d/1yzN-zr1d8uhJoqESf5M3rt4nphJdb-Lt/view?usp=sharing)
* [Regions](https://drive.google.com/file/d/1sFF2rjDLW1EdGFdPYYV0t91dP-Q71z9l/view?usp=sharing)
* [Light and filters](https://drive.google.com/file/d/163h_E4XsWat8hBuPPPc0H7JdDKt0GZPW/view?usp=sharing)

### Part III: From Symbolic Expressions to Machine Learning

* [Mathematical expressions](https://drive.google.com/file/d/17tbBG3C5xNCZJZ3I5IMQFJYvLoLyMCgy/view?usp=sharing)
* [Expressions as classes](https://drive.google.com/file/d/1sRqhaXfOo1JVzZyyM0CyWs_GTDCzBRu9/view?usp=sharing)
* [From expressions to machine learning](https://drive.google.com/file/d/16KI17U6MOjdasZHIwMgtHlmk-dNc1_R7/view?usp=sharing)
* [Machine learning with PyTorch](https://drive.google.com/file/d/1whGvUdiXI-xthY1ts-7VS_eJLaObCCN6/view?usp=sharing)

### Part IV: Graphs and Dynamic Algorithms

* [Graphs](https://drive.google.com/file/d/16iFSKZJ6vTfvwKwUlaiVwQv1ng00FGae/view?usp=sharing)
* [Scheduling with dependencies](https://drive.google.com/file/d/13Bao5jM7K4VoM-QQ_kv1I1VUhGDb2QmC/view?usp=sharing)
* [Cooking times and dynamic programming](https://drive.google.com/file/d/1Mhwc15udggBODo4l1CCjbw0731gKbvvP/view?usp=sharing)

### Part V: Search

* [Sudoku](https://drive.google.com/file/d/1HXsCrHp8HqHJPF9RR1ZcfG7ehr_qP8e5/view?usp=sharing)
* [SAT](https://drive.google.com/file/d/1Gtesc9VMy7BlKh3ZpgRE9MvLpMzZWieg/view?usp=sharing)
* [From Sudoku to SAT](https://drive.google.com/file/d/1Bc4lymTWsAsooBfUwoV-Zqu0_Sgyw6Kn/view?usp=sharing)
