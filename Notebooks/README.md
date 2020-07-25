
 Author: Paul Rosen, Piyush Agram, Heresh Fattahi, David Bekaert\
 Organization: Jet Propulsion Laboratory, California Institute of Technology\
 Copyright 2018 by the California Institute of Technology. ALL RIGHTS RESERVED.\
 United States Government Sponsorship acknowledged. Any commercial use must be
 negotiated with the Office of Technology Transfer at the
 California Institute of Technology.

 This software may be subject to U.S. export control laws.
 By accepting this software, the user agrees to comply with all applicable U.S.
 export laws and regulations. User has the responsibility to obtain export
 licenses,  or other export authority as may be required before exporting
 such information to foreign countries or providing access to foreign persons.



This repository is meant for Jupyter notebooks meant for instruction at UNAVCO Short Course for InSAR Theory and Processing in Aug 2018.


Instructors
-----------

1. Paul Rosen (JPL)
2. Gareth Funning (UC Riverside)
3. Scott Baker (UNAVCO)
4. Piyush Agram (JPL)
5. David Bekaert (JPL)
6. Heresh Fattahi (JPL)


Jupyter setup
-------------

**OSX with Macports (assuming python36)**
  - sudo port install py36-jupyter
  - sudo pip-3.6 install jupyterlab
  - sudo pip-3.6 install jupyter_contrib_nbextensions
  - sudo jupyter-3.6 contrib nbextension install --user
  - sudo pip-3.6 install jupyter_nbextensions_configurator
  - sudo jupyter-3.6 nbextensions_configurator enable --user
  - sudo pip-3.6 install RISE
  - sudo jupyter-nbextension-3.6 install rise --py --sys-prefix


**With Anaconda**
  - python3 -m pip install jupyterlab
  - python3 -m pip install jupyter_contrib_nbextensions
  - python3 -m pip install jupyter_nbextensions_configurator
  - conda install -c conda-forge RISE


   
   
