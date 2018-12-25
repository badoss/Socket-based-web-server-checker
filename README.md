# Socket-based-web-server-checker
Socket-based web server checker


EX 


$ python web_server_checker_tcp.py -a 192.168.1.15 -p 80 -r apache2-default

options: {'resource': 'apache2-default', 'port': 80, 'address':

'192.168.1.15'}, args: []

HTTP request:

|||GET /apache2-default HTTP/1.1

Host: 192.168.1.15

|||

Attempting to connect to 192.168.1.15 on port 80

Connected to 192.168.1.15 on port 80

Received 100 bytes of HTTP response

|||HTTP/1.1 301 Moved Permanently

Date: Wed, XX Apr 201X XX:XX:XX GMT

Server: Apache/2.0.55 (Ubuntu) |||

Closing the connection

First line of HTTP response: HTTP/1.1 301 Moved Permanently

Version: HTTP/1.1, Status: 301, Message: Moved Permanently

Success - status was 301

check_webserver returned True

