Restructured Text Primer
========================

Basic markup
------------

Bold and Italics
................

This is how you write **bold**.

This is how you write *italics*.

Bullets
.......

This is how you do a hyperlink: http://google.com

A bullet list:

* Item foo
* Item bar
 - Sub bullet 1
 - Sub bullet 2
* Item new

A numbered list:

#. Item one
#. Item two

Tables
......

Here is how to make a simple table:

+--------------------+--------------------------+
| **Name**           | **Job**                  |
+--------------------+--------------------------+
| Tim                | CEO of Microsoft         |
+--------------------+--------------------------+

You can also use an equals line to indicate the header:

+--------------------+--------------------------+
| Name               | Job                      |
+====================+==========================+
| Tim                | CEO of Microsoft         |
+--------------------+--------------------------+

This is another way to make a table:

=====  =====  ====== 
   Inputs     Output 
------------  ------ 
  A      B    A or B 
=====  =====  ====== 
False  False  False 
True   False  True 
False  True   True 
True   True   True 
=====  =====  ======

Preformatted text
.................

This is how you show a program listing or some preformatted text::

    shrub:SphinxTutorial timlinux$ ls -lah
    total 8
    drwxr-xr-x   4 timlinux  staff   136B Apr  8 09:55 .
    drwxr-xr-x  19 timlinux  staff   646B Apr  8 09:27 ..
    drwxr-xr-x  14 timlinux  staff   476B Apr  8 10:00 .git
    -rw-r--r--   1 timlinux  staff   206B Apr  8 09:59 README.rst

------------

You can find a complete list of all the supported tags here
http://docutils.sourceforge.net/docs/user/rst/quickref.html


How to install git on Ubuntu::

    sudo apt-get install 

How to install rst2pdf on Ubunut::

	sudo apt-get install rst2pdf

You can find a windows installer to covert rst to pdf here:

https://code.google.com/p/pythonxy/downloads/list


Sphinx
======

Sphinx Installation
-------------------

Install python
...............

Windows
^^^^^^^

Downlad python from here:

http://python.org/download/

And choose the latest 2.7 windows 32 bit installer e.g.

http://python.org/ftp/python/2.7.4/python-2.7.4.msi

Run the installer accepting all the prompts.

My Computer -> System Properties -> Environment Variables

Now add python to end of 'PATH'::

    c:\python27;c:\python27\Scripts

OSX
^^^

Python is already installed by default

Linux
^^^^^

Python is already installed by default


Install PIP
...........

Windows
^^^^^^^
First you need to get easy install from this location: 

http://pypi.python.org/pypi/setuptools#windows

You need to get the file called ``ez_setup.py`` and save it to ``c:\ez_install.py``

Now you need to open a command prompt window:

* press Windows Key + R
* type ``cmd.exe`` then right click and choose 'Run as administrator'
* type ``cd \`` too move to the top directory
* run this command: ``python ez_setup.py``
* now use easy_install to install pip: ``easy_install pip``

OSX
^^^

Simply open terminal and type this command::

    sudo easy_install pip
    
Ubuntu
^^^^^^

Simply open a terminal and type this command::

    sudo apt-get install python-pip


Install sphinx
..............

Windows
^^^^^^^

From command prompt or terminal, run this::

    pip install sphinx

OSX and Linux users
^^^^^^^^^^^^^^^^^^^

From terminal run this::

    sudo pip install sphinx


Sphinx Quickstart
-----------------

In your working dir (e.g. ``c:\Users\joe\Documents\sphinxtutorial``) create a new sphinx project::

    sphinx-quickstart







































































