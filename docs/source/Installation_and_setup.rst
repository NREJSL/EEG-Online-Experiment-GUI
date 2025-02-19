Installation and setup
----------------------
I used Pycharm for developing this GUI, so the installation and setup are shown in Pycharm
environment, but you are welcome to try other IDEs.

* Clone project from github to your own <path>

    .. code-block:: python

       git clone https://github.com/WILLSNIU186/uw_eboinics_experimental_interface.git

* Open this project in Pycharm and setup python interpreter, which will automatically create a new environment for you.
  Detailed instruction can be found `here <https://www.jetbrains.com/help/pycharm/creating-virtual-environment.html#python_create_virtual_env>`_\

    Open Pycharm -> click File -> click Open -> open the cloned project in your <path> -> click
    settings -> click add python interpreter -> create a venv\

* Open terminal in Pycharm

    .. code-block:: python

        pip install -r requiremnts.txt
        cd lib\neurodecode-master
        python setup.py develop
        cd ..\..

* Run GUI
    Either run it in terminal

        .. code-block:: python

            python main.py

    Or add main.py to configuration -> click play button on the top

