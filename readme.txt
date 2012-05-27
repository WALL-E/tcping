Installation:
------------
make install


Usage:
-----
Routine tasks

tcping Web Server:
	tcping localhost 
	tcping -p 80 127.0.0.1
	tcping -p 8080 localhost

tcping once:
     tcping -p port -c 1 hostname

tcping returns:
       0 on success
       2 if the host or service could not be resolved
       127 on other errors


Todo list:
     1:add timeout option
