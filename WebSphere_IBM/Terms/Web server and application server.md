A *Web server* is a computer system that processes requests via http, the basic network protocol used to distribute information on the www. The term can refer to the entire system, or specifically to the software that accepts and supervises the http requests.
* Used for display the web pages over the internet


An *Application server* behaves like an extended VM for running app, transparently handing connections to the other components like database on one side, and, often, connections to the Web client on the other. 

| Webservers  | IHS, IIS, Apache, iPlanet                                |
| ----------- | -------------------------------------------------------- |
| App servers | Websphere App server -- IBM, Oracle, ApacheTomcat, Jboss |
#### Functionality
http://google.com    (https/https)
1. Identify the request which are comes from the client
	* Static -- which we can not change in the web pages (text, PDF, Images)
	* Dynamic -- we can change/navigate the web pages over the internet
2. Status codes --  It maintain status codes for client request ( 404, 500 ,bad gateway)