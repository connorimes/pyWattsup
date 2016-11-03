This Python script instructs a WattsUp? PRO power meter to log internally when
the "start" command is issued.  It then prints out the results and statistics
when the "stop" command is issued.

Code author: Stelios Sidiroglou-Douskos

--------------------------------------------------------------------------------

Prerequisites:

The 'serial' and 'numpy' python modules. On an Ubuntu system:

$ apt-get install python-numpy python-serial

--------------------------------------------------------------------------------

Usage:

$ python pyWattsup.py start

$ python pyWattsup.py stop

By default, the script looks for the WattsUp device at /dev/ttyUSB0.
For more options, see:

$ python pyWattsup.py -h
