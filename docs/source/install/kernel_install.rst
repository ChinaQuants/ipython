.. _kernel_install:

Kernel Installation
-------------------

IPython can be installed (different python versions, virtualenv or conda 
environments) as a kernel by following these steps:

* Make sure that the desired python installation is active (e.g. activate the environment)
  and ipython is installed
* Run once ``ipython kernel install`` (use ``ipython2 ...`` or ``ipython3 ...``
  if you want to install specific python versions)
* See `ipython kernel install --help` for the list of installation options like naming the kernel, or non default install location. 
* The IPython kernel for Jupyter is provided by the `ipykernel` python package, see there if you need more flexibility for installation. 

The last command installs a :ref:`kernel spec <jupyterclient:kernelspecs>` file for the current python installation. Kernel spec files are JSON files, which can be viewed and changed with a
normal text editor.


.. note ::
    
    `ipython kernelspec`  is deprecated and will be removed in future versions.
