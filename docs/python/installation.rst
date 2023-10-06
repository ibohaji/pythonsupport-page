.. _install-python-ny:

Setting up python 
=================

.. tip:: 
    We suggest removing any pre-installed Python versions and VS Code before 
    proceeding with this  guide to ensure a smooth installation process. You can refer to this guide to walk you through the uninstallation process, ensuring you're all set to get started.




1. **Download & Installation**
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. note:: 
    For the time being, we recommend **not** downloading the newest python release (3.12).

.. tab:: {{ windows }}

    - For a hassle-free Python download & installation experience, we recommend grabbing it straight from the `Microsoft Store <https://www.microsoft.com/store/productid/9NRWMJP3717K?ocid=pdpshare>`_.
  
    - However, if you find yourself on an adventurous detour and can't access it there, you can still opt for the `official Python release <https://www.python.org/downloads/release/python-3115/>`_ -- **Just remember to check the Add Python to PATH box (at the bottom of the installation GUI)**.




.. tab:: {{ macos }}

    - You can download the official python directly from `here <https://www.python.org/downloads/release/python-3115/>`_.
    After downloading the installer, the installation process should be relatively straightforward. 




.. tab:: {{ linux }}

    *In progress*


2. **Verify the installation** 
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. warning::
    If you did not download python through Microsoft Store, then you need to make sure 
    that you check the "Add to path" box during the installation. 

.. tab:: {{ windows }}

    1. Give your keyboard window key:kbd: windows a friendly nudge.  
    2. Type "powershell" in the search bar, and hit enter to launch PowerShell.
    3. In the powershell window, type *"python --version"*
       
    .. code-block:: powershell

        python --version

    4. If you spot the "Python x.xx.x" smiling back at you, you're all set! You've got a python in your machine |:snake:|.  
        
    .. code-block:: powershell 

        Python 3.11.6   

.. tab:: {{ macos }} 

    If you have an M1 or M2 processor we **strongly** recommend you installing the **rosseta** 1 or 2.
   
    1. Give your keyboard's "Command" key a friendly nudge.
    2. Type "terminal" in the search bar, and press Enter to open Terminal.
    3. In the Terminal window, type *"python3 --version"*

    .. code-block:: bash 

        Python3 --version

    4. If you see the "Python x.xx.x" smiling back at you, you're all set! You've got a Python friend on your machine |:snake:|.
    
    .. code-block:: bash 

        Python 3.11.6   

.. tab:: {{ linux }} 

    If you use linux, you know what to do (jk, det skal nok rettes inden publish)



What's next ? 
^^^^^^^^^^^^^^
    Now that your python is all up and running, the next step is :ref:'installing vs-code'

.. toctree::
   :caption: Downloading python installation
   :maxdepth: 1
