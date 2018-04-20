Tornado based messaging system for inter-scratch project communication/

Interscratch will install two scripts : 
	- interscratchs : the interscratch server that must be run first, and only once 
	- interscratchc : the interscratch client that must be run on each participating machine
When running the server, the following output should be displayed::

    (.venv) vinsz@prigogine:~/git/interscratch$ interscratchs 
    To connect a client, use:
    interscratchc --server=192.168.1.34
and the output above shows the command to use on each client.

Resources
---------
Interscratch also comes with a resources folder located under the site-packages of the python
distribution. The interscratch resources folder contains the http extension interscratch.s2e. 
To load this extension, hold-shit the file menu and select *Import experimental http extension*.

