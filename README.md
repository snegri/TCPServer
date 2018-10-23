# TCPServer

This is a simple TCP web server written in C++. It uses a default document root www. 

Running:
Send requests to the webserver by compiling and running it locally and then accessing it from a web browser using:
localhost:<port>
You may also send the web server requests using telnet or nc:
echo -en <request> | telnet 127.0.0.1 <port number>
