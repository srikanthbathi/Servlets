[Web container](#web-container)

[Servlet container state](#state)



## Web Container 

A web/servelet container is a component in web server which interacts with java servlets. A Web container is responsible for URL mapping, Servelet Lifecycle management and URL request has correct access rights.

<img src="https://www.javatpoint.com/servletpages/servletterminology/images/servlet-container1.png">


## State

The servlet container is the part of web server which can be run in a separate process. We can classify the servlet container states in three types:

Standalone: It is typical Java-based servers in which the servlet container and the web servers are the integral part of a single program. For example:- Tomcat running by itself
In-process: It is separated from the web server, because a different program is runs within the address space of the main server as a plug-in. For example:- Tomcat running inside the JBoss.
Out-of-process: The web server and servlet container are different programs which are run in a different process. For performing the communications between them, web server uses the plug-in provided by the servlet container.

**Standalone state**

**Inprocess**

**OutOfProcess**
