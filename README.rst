
Instructions for Introduction to Scientific Python
==================================================

**If you can't get this to work, you can do much of** `this class in  mybinder.org`_.

To be able to execute all of the code I will demonstrate during the class, and to be able to write your own, please come prepared:

- `Installing Python`_

  - `Windows Users`_

  - `Mac Users`_

- `Installing GitHub`_

`What will be covered`_? The rest will happen in class!

Installing Python
-----------------

- Students should have `Anaconda Python`_, Python version 3.5, 3.6, or 3.7, installed (64 bit is correct for any reasonably recent machine). **There won't be time to do this at the start of the short class!!!**

I may have an alternative live during the course, but it won't get your machine working!

- When doing this *also install Visual Studio Code*. It is an option near the end.

- Just install anything it asks you about.

- Users should install locally (not for all users) to keep things simple.

- All platforms (Mac, Windows, Linux) will be covered.

Platform Differences
--------------------

Windows Users
~~~~~~~~~~~~~

- Find the Anaconda Prompt application and run it.
- Type ``conda update --all``
- Type ``conda install cython``
- Type ``conda install numba``

Mac Users
~~~~~~~~~

- Find the ``Terminal.app``. It is located in your ``/Applications/Utilities`` folder.
  - Quick tip- command-key space-bar, then type 'Terminal' may launch it if Spotlight is set up correctly.
- Type ``conda update --all``
- Type ``conda install cython``
- Type ``conda install numba``

Linux Users
~~~~~~~~~~~

- Open your favorite terminal and type ``conda update --all``
- Type ``conda install cython``
- Type ``conda install numba``

Installing GitHub
-----------------

I will want you to get things during the course from `GitHub <http://github.com>`_.

- Download `GitHub Desktop`_ and install it. You may need to create an account on GitHub.

  Linux Users:

  You will need to use `GitKraken`_.

  - Good News: It's much more powerful.
  - Bad News: It's much more complicated.

- Go to `the repository for this class in your web browser`_.
- You should be able to see a green button that says ``Clone or Download``. ``Clone`` is much better. This will allow you to update it in the future. Download means you reorganize each time. I suggest you create a folder ``GitHub`` in your Documents folder.




If we have time, we will learn a little Bokeh
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

These are notes to myself... you might figure them out, you need to know how to hunt paths, though.

``bokeh serve /Users/jslater/Documents/python-dev/bokeh/examples/app/taylor.py``

``jupyter notebook /Users/jslater/Documents/python-dev/bokeh-notebooks/quickstart``

Other Educational Resources
---------------------------
- `Python Plotting With Matplotlib`_
- `Lorena Barba's Numerical Python Mooc`_
- `SciPy Lecture Notes`_
- `Generic Python Introduction`_
- `SciPy Cookbook`_

Recommended Books
-----------------
- `Learning Scientific Programming with Python`_ - Christian Hill
- `A Primer on Scientific Programming with Python`_ - Hans Petter Langtangen (`4th Edition`_)


.. _`SciPy Cookbook`: https://scipy-cookbook.readthedocs.io/
.. _`Generic Python Introduction`: https://github.com/guntukukamal/Good-python-reference
.. _`SciPy Lecture Notes`: https://github.com/scipy-lectures/scipy-lecture-notes
.. _`4th Edition`_: https://hplgit.github.io/primer.html/doc/pub/half/book.pdf
.. _`A Primer on Scientific Programming with Python`: https://www.amazon.com/Scientific-Programming-Computational-Science-Engineering/dp/3662498863/ref=sr_1_4?ie=UTF8&qid=1542249635&sr=8-4&keywords=scientific+python
.. _`Learning Scientific Programming with Python`: https://www.amazon.com/Learning-Scientific-Programming-Python-Christian/dp/110742822X/ref=sr_1_3?ie=UTF8&qid=1542249635&sr=8-3&keywords=scientific+python
.. _`What will be covered`: https://github.com/josephcslater/Introduction_to_Python/blob/master/Introduction_to_Scientific_Python.ipynb
.. _`class repository`: https://github.com/josephcslater/Introduction_to_Python
.. _`Lorena Barba's Numerical Python Mooc`: https://github.com/numerical-mooc/numerical-mooc
.. _`Python Plotting With Matplotlib`: https://realpython.com/python-matplotlib-guide/#pylab-what-is-it-and-should-i-use-it
.. _`Anaconda Python`: https://www.anaconda.com/download/#download
.. _`GitHub Desktop`: https://desktop.github.com/
.. _`GitKraken`: https://www.gitkraken.com/
.. _`the repository for this class in your web browser`: https://github.com/josephcslater/Introduction_to_Python
.. _`this class in  mybinder.org`: https://mybinder.org/v2/gh/josephcslater/Introduction_to_Python/master
