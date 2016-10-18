This Python script instructs a WattsUp? PRO power meter to log internally when
the "start" command is issued.  It then prints out the results and statistics
when the "stop" command is issued.

For example:

$ python pyWattsUp.py start

$ python pyWattsup.py stop

The script expects the WattsUp to be available at /dev/ttyUSB0.
