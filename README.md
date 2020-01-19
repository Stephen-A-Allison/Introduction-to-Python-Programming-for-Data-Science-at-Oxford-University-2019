# Introduction to Python Programming for Data Science (i2pp4ds) <img src="oudce_logo.png" align="right"/>
### Massimiliano Izzo

Materials for [Introduction to Python Programming for Data Science at Oxford](https://www.conted.ox.ac.uk/courses/introduction-to-python-programming-for-data-science?code=O19P727COW) - **this page will be updated as the course progresses**.

The class workspace on **Slack** is https://i2pp4ds-MT2019.slack.com. I encourage you to ask questions should you have them in the Slack channel incase your classmates can help. Massi (your tutor; massimiliano.izzo@oerc.ox.ac.uk) and Ramon (your TA; ramon.granell@oerc.ox.ac.uk) will also check Slack and provide support where possible. Download Slack from: https://slack.com/get


To use **Jupyter** yourself, I recommend you download and install **Anaconda**, a Python Data Science Platform, from: [here](https://www.anaconda.com/download/) Make sure you download the **Python 3** version of Anaconda. You can also install Jupyter if you have a standard Python distribution installed. Ask your tutors for assistance if you need to install Jupyter on your own machine.

To get the contents of this repository I recommend that you install **Git SCM**, a source code management software, that will help you keep up-to-date with the repository. I will be adding content as the course progresses and Git will allow you to pull new material as it becomes available.

**Jupyter/Anaconda, Slack and Git are available to use in the Computer Teaching Room (CTR) at Ewert House.**

You can also run online live versions of the notebooks that are launched by **[Binder](https://mybinder.org)** by clicking on the `binder` buttons below without having to install anything yourself. Please note that Binder is still in beta testing and is hosted by *University of California, Berkeley* so may occasionally not work as expected (but is quite reliable). 

### Cloning this repository to use at home

If you want to run the notebooks on your own computer at home, apart from installing Jupyter/Anaconda as per above, you will need to install **Git**, which is a source code management software, from [here](https://git-scm.com/downloads). Once installed, you need to open up the command-line ("Command Prompt" on Windows or "Terminal" on Mac OSX) to run some commands.

Change directory to somewhere sensible, such as `My Documents` or similar on Windows or `Documents` on Mac OSX. Assuming you're using `Documents`:

```
cd Documents
```

Then ask Git to clone this repository with the following command.
```
git clone https://gitlab.com/data-science-course/01-i2pp4ds-mt2019
```

This will create a subdirectory called `01-i2pp4ds-mt2019` in your `Documents` folder. When you need to update the content at some later time after I have added some new files to the repository, you will need to open up the command-line again and do the following commands.
```
cd Documents/01-i2pp4ds-mt2019
git pull
```
What this does is to ask Git to check if there are any new changes in the online repository and to download those new files or updates to the existing files.

Either some lines of stuff should whizz by, or it will say `Already up to date.` if there are no new changes.

If this doesn't work, you may need to force the update, which will overwrite your local files. To do this (make sure any of your own work is renamed or moved outside of the `01-i2pp4ds-mt2019` folder first):
```
git fetch --all
git reset --hard origin/master
```




### Course Programme

The course will be every week on Thursdays during Michaelmas 2019 (Nov 14 is scrapped)

**Week 1:**  Introduction to Data Science (Oct 03)

**Week 2:**  Python basics: built-in types, functions and methods, if statement (Oct 10)

**Week 3:**  Python data structures: list, dicts, tuples; for loops (Oct 17)

**Week 4:**  NumPy and the SciPy ecosistem (Oct 24)

**Week 5:**  Pandas for data science I  (Oct 31)

**Week 6:**  Pandas for data science II  (Nov 7)

**Week 7:**  Data visualisation: matplotlib and seaborn  (Nov 14)

**Week 8:**  Object-oriented programming: classes, inheritance, and applications (Nov 21)

**Week 9:**  Data gathering and cleaning  (Nov 28)

**Week 10:**  Introduction to Unix and the Git management system and the Anaconda environment + final assignment (Dec 5)

## Week 1: Introduction to Data Science

* **Lecture slides:** [Download here](https://tinyurl.com/y34jkd46)
* **Exercise 01A:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/data-science-course%2F01-i2pp4ds-mt2019/master?filepath=exercises%2F01a_Notebook_Basics.ipynb)
* **Exercise 01B:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/data-science-course%2F01-i2pp4ds-mt2019/master?filepath=exercises%2F01b_Running_Code.ipynb)
* **Exercise 01C:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/data-science-course%2F01-i2pp4ds-mt2019/master?filepath=exercises%2F01c_Working_With_Markdown_Cells.ipynb)
* **Exercise 01D:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/data-science-course%2F01-i2pp4ds-mt2019/master?filepath=exercises%2F01d_Notebook_Exercises.ipynb)

## Week 2: Introduction to Python - Built-in data types, functions, IF statements

* **Lecture slides** [Download here](https://tinyurl.com/y5k8wpkn)
* **Exercise 02:** Expressions [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/data-science-course%2F01-i2pp4ds-mt2019/master?filepath=exercises%2F02_Expressions.ipynb)
* **Exercise 02 with solutions** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/data-science-course%2F01-i2pp4ds-mt2019/master?filepath=exercises-solutions%2F02_Expressions_complete.ipynb)

## Week 3: Data Structures

* **Lecture slides** [Download here](https://tinyurl.com/yyqlvcrf)
* **Exercise 03:** Data Structures, Functions, and Loops [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/data-science-course%2F01-i2pp4ds-mt2019/master?filepath=exercises%2F03_Data_Structures_and_Loops.ipynb)
* **Exercise 03 with solutions** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/data-science-course%2F01-i2pp4ds-mt2019/master?filepath=exercises-solutions%2F03_Data_Structures_and_Loops.ipynb)

## Week 4: The Python Standard Library, NumPy, and the SciPy Ecosystem

* **Lecture slides** [Download here](https://tinyurl.com/yyejbb8l)
* **Exercise 04** NumPy Library for Array Manipulation [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/data-science-course%2F01-i2pp4ds-mt2019/master?filepath=exercises%2F04_Numpy_exercises.ipynb)
* **Exercise 04 with solutions** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/data-science-course%2F01-i2pp4ds-mt2019/master?filepath=exercises-solutions%2F04_Numpy_exercises.ipynb)

## Week 5: Introduction to Pandas  

* **Lecture slides** [Download here](https://tinyurl.com/yxvkbezn)
* **Exercise 05** Formative Assignment - submission deadline 04/11/2019 [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/data-science-course%2F01-i2pp4ds-mt2019/master?filepath=exercises-solutions%2F05_Formative_Assignment.ipynb)
* **Exercise 05 with solutions** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/data-science-course%2F01-i2pp4ds-mt2019/master?filepath=exercises-solutions%2F05_Formative_Assignment.ipynb)

## Week 6: Advanced Pandas

* **Lecture slides** [Download here](https://tinyurl.com/y4ua9kpj)
* **Exercise 06** The Challenge [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/data-science-course%2F01-i2pp4ds-mt2019/master?filepath=exercises%2F06_Data_Cleaning_and_Analysis.ipynb) 
* **Exercise 06 with solutions** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/data-science-course%2F01-i2pp4ds-mt2019/master?filepath=exercises-solutions%2F06_Data_Cleaning_and_Analysis_complete.ipynb)

## Week 7: Visualization

* **Lecture slides** [Download here](https://tinyurl.com/yh5k3sgs)
* **Exercise 07-Part 1**: Figures, Subplots, and Layouts [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/matplotlib/AnatomyOfMatplotlib/master?filepath=%2FAnatomyOfMatplotlib-Part1-Figures_Subplots_and_layouts.ipynb)
* **Exercise 07-Part 2**: Plotting Methods Overview [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/matplotlib/AnatomyOfMatplotlib/master?filepath=AnatomyOfMatplotlib-Part2-Plotting_Methods_Overview.ipynb)
* **Exercise 07-Part 3**: How to Speak MPL [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/matplotlib/AnatomyOfMatplotlib/master?filepath=AnatomyOfMatplotlib-Part3-HowToSpeakMPL.ipynb)
* **Exercise 07-Part 4**: Limits, Legends, and Layouts [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/matplotlib/AnatomyOfMatplotlib/master?filepath=AnatomyOfMatplotlib-Part4-Limits_Legends_and_Layouts.ipynb)
* **Exercise 07-Part 5**: Artists [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/matplotlib/AnatomyOfMatplotlib/master?filepath=AnatomyOfMatplotlib-Part5-Artists.ipynb)
* **Exercise 07-Part 6**: MPL toolkits [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/matplotlib/AnatomyOfMatplotlib/master?filepath=AnatomyOfMatplotlib-Part6-mpl_toolkits.ipynb)

## Week 8: Object-oriented Programming

* **Lecture slides** [Download here](https://tinyurl.com/wyt6w8a)
* **Exercise 08** Implement a Linear Regressor as a Python Class [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/data-science-course%2F01-i2pp4ds-mt2019/master?filepath=exercises%2F08_Ordinary_Least_Squares.ipynb)
* **Exercise 08 with solutions** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/data-science-course%2F01-i2pp4ds-mt2019/master?filepath=exercises-solutions%2F08_Ordinary_Least_Squares.ipynb)
* **Final Assignment Part 1 - Deadline Wed 18 December 2019** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/data-science-course%2F01-i2pp4ds-mt2019/master?filepath=exercises%2FFinal_Assignment_Part1.ipynb)
* **Final Assignmenat Part 2 - Deadline Wed 18 December 2019** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/data-science-course%2F01-i2pp4ds-mt2019/master?filepath=exercises%2FFinal_Assignment_Part2.ipynb)


## Week 9: Getting data from public sources

* **Lecture slides** [Download here](https://tinyurl.com/yx42j3ts)


## Week 10: Introduction to UNIX, GIT and Anaconda

* **Lecture slides** [Download here](https://tinyurl.com/rv286a2)