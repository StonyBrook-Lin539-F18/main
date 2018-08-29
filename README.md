Mathematical Methods in Linguistics
===================================

**A friendly plug:** If you are interested in this class, also consider attending the department's [Mathematical Linguistics Reading Group](http://mlrg.thomasgraf.net).

Course Outline
--------------

This course is an introduction to mathematics in linguistics.
It aims to help students familiarize themselves with mathematical concepts and applications that are widely relevant to theoretical and/or computational linguistics. 
This covers a wide range of topics, mostly from *discrete mathematics*.
The course is also very different from what you did in high school, there's precious few numbers here and we don't care much about trigonometry or calculating compound interest.
In contrast to a proper mathematics course, we also focus more on techniques and tools rather than theorems and proofs.
This means that you will learn how to work with things like matrices, semirings, and lattices, but you won't have to prove things about them.
So this is more like a CS methods course than a proper math class.

For more information about the content, see the [syllabus].

Using the Lecture Notes
-----------------------

The lecture notes are made available as [Jupyter notebooks](http://jupyter.org/) in the [notebooks folder](./tree/master/notebooks) of the [main github repository](https://github.com/StonyBrook-Lin539-F17/main). 
A Jupyter notebook is a mixture of text and Python code, which allows for a more interactive learning environment.
You can view the notebooks directly on github, but this does not work perfectly as github ignores some layout instructions and does not allow you to execute any of the Python code --- you'd be looking at a static, impoverished snapshot of the interactive notebook.

If you are a Stony Brook student, you should instead use the [preconfigured Jupyter server for this course](https://dev.tlt.stonybrook.edu:8000).
The server can only be accessed from a campus network.
Right now you have to use Stony Brook's [VirtualSINC](https://it.stonybrook.edu/services/virtual-sinc-site) to connect, but hopefully the server will soon be accessible online without jumping through this extra hoop.

Everybody else should consult the [instructions on how to get the Jupyter notebooks to work on your computer][instructions].


Assigned Units per Week
--------------------------

- will be announced each week per email


Link List
---------

### Using git

You can clone this repository to your computer and issue `git pull -s recursive -X theirs` on a regular basis to keep your clone up-to-date.

- Our department's [git tutorial](https://github.com/CompLab-StonyBrook/git_training)
- [Github app for Windows](http://windows.github.com); supports only Windows 7 or later
- [Github app for Mac](http://mac.github.com); supports only OS X 10.9 or later
- List of alternative [GUI clients for git](http://git-scm.com/downloads/guis)
- Tutorials for using [git via the command line](https://www.atlassian.com/git/tutorials)
- Official [documentation for git](http://git-scm.com/doc)


### Markdown

You can use Markdown syntax when authoring github issues or wiki entries.

- Interactive tutorial to [markdown basics](http://markdowntutorial.com/)
- [Complete markdown syntax](http://daringfireball.net/projects/markdown/syntax)
- Overview of [Github's markdown dialect](https://help.github.com/categories/writing-on-github/)


### LaTeX

If you need to write mathematical formulas, use LaTeX commands, e.g. `$f(x) = \frac{x}{2}$` to typeset the fraction.

- [Overleaf](https://www.overleaf.com/) (formerly writeLaTeX) is an online LaTeX editor with live preview
- List of [commonly used math symbols](http://web.ift.uib.no/Teori/KURS/WRK/TeX/symALL.html)
- Andrew Roberts' [Getting to Grips with LaTeX](http://www.andy-roberts.net/writing/latex)


### Python

The notebooks contain Python code that you can run and edit on your own.
This way you can check some of your own calculations with Python or play around with parameters to see how they affect the output of a computation.

- A succinct yet extensive [tutorial for Python 3](http://www.python-course.eu/python3_course.php)
- The official [Python 3 documentation](https://docs.python.org/3/)
- [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/) is an excellent introduction that covers the basics of Python and applies them to real-world tasks.


[syllabus]: ./source/00_syllabus/syllabus.mdown
[instructions]: ./source/00_syllabus/setup.mdown
