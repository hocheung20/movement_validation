Guide for Contributors to this Repository
-----------------------------------------

Thank you for your interest in contributing! Whether you are a *C.
elegans* researcher who wishes to add a feature set to the calculation
engine, or an interested person looking to contribute to the overall
OpenWorm effort, you are welcome to join in on the fun.

Objectives:
~~~~~~~~~~~

1. | This repository should house a test
     `pipeline <https://github.com/OpenWorm/movement_validation/blob/master/documentation/Processing%20Pipeline.md>`__
     for the OpenWorm project to run a behavioural phenotyping of its
     virtual worm, using the same statistical tests the Schafer lab used
     on their real worm data.
   | `Overall OpenWorm Milestone:
     #19 <https://github.com/openworm/OpenWorm/issues?milestone=19&state=open>`__

2. In achieving goal #1, this repository will also be an open source
   version of the Schafer Lab's `Worm Tracker 2
   (WT2) <http://www.mrc-lmb.cam.ac.uk/wormtracker/>`__ analysis
   pipeline that goes from raw real worm videos to worm measurements
   detected by machine vision, to a selection of calculated worm
   behavioural features like average speed.

3. Also in achieving goal #1, we hope to have a system for tracking the
   statistics of hundreds of real and virtual worm strains in a
   database.

History of this Repository
~~~~~~~~~~~~~~~~~~~~~~~~~~

On 7 January 2013 Dr. Evitar "Ev" Yemini published `"A database of
Caenorhabditis elegans behavioral
phenotypes" <http://www.nature.com/nmeth/journal/v10/n9/fig_tab/nmeth.2560_F1.html>`__
with his colleagues at the Schafer Lab, describing WT2.

Dr. Yemini first gained exposure to the OpenWorm project when he spoke
at an `OpenWorm Journal Club
event <https://www.youtube.com/watch?v=YdBGbn_g_ls>`__, on 16 August
2013. He described how his software can process raw videos of worms into
statistics describing their movement quantitatively. It was realized
that OpenWorm could adapt this software to validate whether its
simulated worms were behaving correctly.

Consequently, to start, in August 2013 `Jim
Hokanson <https://github.com/JimHokanson>`__ cloned the WT2 software,
written in Matlab, into a repository he called
`"SegWorm" <https://github.com/openworm/SegWorm>`__.

He took this repository as the starting point for his code development
work on behalf of OpenWorm. He revised this code from September 2013 to
January 2014, to speed up and clarify the code. This revised Matlab
version is available in the
`"SegWormMatlabClasses" <https://github.com/JimHokanson/SegwormMatlabClasses/>`__
repo.

From October 2013, `Michael Currie <https://github.com/MichaelCurrie>`__
started to translate Jim's SegWormMatlabClasses repository into Python
so it would be fully open source. To this end he started the
`movement\_validation <https://github.com/openworm/movement_validation>`__
repository.

Currently only the movement\_validation repository is being actively
worked on.

An overview of the current status of the work on the
movement\_validation repository is available at `Code
Progress <https://docs.google.com/spreadsheets/d/1dW1ukYlTu4vbm35bkf8MIZ3obP37yrKFz12X84ukOTU/edit#gid=9274694>`__.

Best practices for contributing to this repo
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Just find an issue in the "Ready" column of the `waffle
board <https://waffle.io/openworm/movement_validation>`__ and dig in.
Ask questions of others early and often; you can do so on our message
board,
`OpenWorm-discuss <https://groups.google.com/forum/#!forum/openworm-discuss>`__.

Please commit your code often, even if you've made a very small change,
but only if you've verified that your change has not broken any
`examples <https://github.com/openworm/movement_validation/tree/master/examples>`__.

For more information, see `"Commit Often, Perfect Later, Publish Once:
Git best
practices" <http://sethrobertson.github.io/GitBestPractices/>`__.

Further Information
~~~~~~~~~~~~~~~~~~~

`White Paper Describing Movement Validation at a high
level <https://github.com/openworm/movement_validation/blob/master/documentation/Movement%20Validation%20White%20Paper.md>`__
*(June 2014)*

`movement\_validation Google Docs
folder <https://drive.google.com/#folders/0B9dU7zPD0s_LdHRndU9QQ3NTRUE>`__,
with various information including team member list, code progress, etc.

`Archived Monthly Progress
Reports <https://drive.google.com/folderview?id=0B9dU7zPD0s_LMm5RMGZGX2JEeGc&usp=sharing>`__
*(Maintained from September 2013 to March 2014, after which they were
discontinued)*

`Movement
Validation <https://github.com/openworm/openworm_docs/blob/master/Projects/worm-movement.rst>`__
documented at the OpenWorm/openworm\_docs repository. *(Has not been
updated since 29 Dec 2013)*
