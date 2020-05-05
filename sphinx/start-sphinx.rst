Prerequisites
=============

Adding repository for python
------------------------------   

   .. image:: /img/python.png

Now execute the command to install python 3.6:
----------------------------------------------

.. code-block:: bash
    
    :~$ sudo apt-get install python3.6

.. note:: 

   PIP is a package manager for Python packages  
   
   **Install PIP**

    .. code-block:: bash
        
        :~$ sudo apt install pyhton-pip



Getting Started with Sphinx
===========================

Sphinx is a powerful documentation generator that has many great features for writing technical documentation including:

*  `Generate web pages, printable PDFs, documents for e-readers (ePub), and more all from the same sources`
*  `You can use reStructuredText or Markdown to write documentation`
*  `An extensive system of cross-referencing code and documentation`
*  `Syntax highlighted code samples`
*  `A vibrant ecosystem of first and third-party extensions`



   
   
Install sphinx executing the following command:
-----------------------------------------------

  .. code-block:: bash
     
     :~$ pip install sphinx
  

Now install sphinx readthedocs theme
-------------------------------------

 .. code-block:: bash
    
    :~$ pip install sphinx_rtd_theme
 
Some necessary steps to be followed
-------------------------------------

*  `Open your code editor make a new directory.`
   
   .. code-block:: bash
      
      :~$ mkdir `name of the project`

.. image:: /img/sphinx1.png
      
.. image:: /img/sphinx2.png

.. image:: /img/sphinx3.png
            
      
   

*  `Now, cd into that directory.`

    .. code-block:: bash
       
       :~$ cd project
    
    
   .. image:: /img/sphinx4.png

            

Run ``sphinx-quickstart`` in there:
-----------------------------------

.. code-block:: bash
   
   :~$ sphinx-quickstart


Now, build directory
--------------------

**Please enter values for the following settings.**

* Some are selected by default, just press ``Enter``.

.. image:: /img/2.png

* Enter ``project name`` and ``author name``.

.. image:: /img/3.png

* Follow the steps.

.. image:: /img/4.png

.. image:: /img/5.png



Install plugin "restructuredtext"
----------------------------------

   .. image:: /img/11.png
   


Open the folder containing the all created files.
---------------------------------------------------

    .. image:: /img/7.png

First look of the website.
----------------------------

   .. image:: /img/10.png

   



Open the file ``conf.py`` for applying read the doc theme.
-------------------------------------------------------------

  .. image:: /img/8.png

  
Apply the theme ``sphinx_rdt_theme``.
--------------------------------------

.. image:: /img/9.png

To compile your website Run
---------------------------
.. code-block:: bash
   
   :~$ make html

.. note:: 
    When you make any changes in the document, to preview that, run this command again.
   

**Have preview in browser.**

.. code-block:: bash

   :~$ google-chrome _build/html/index.html


   
**Now your website is equipped for editing.**
























