https://www.youtube.com/watch?v=eesqK59rhGA

comit/ reverse AJAX.

[Web container](#web-container)

[Servlet container state](#state)

[App Server vs Web Server](#app-vs-web-servers)



## Web Container 

A web/servelet container is a component in web server which interacts with java servlets. A Web container is responsible for URL mapping, Servelet Lifecycle management and URL request has correct access rights.

<img src="https://www.javatpoint.com/servletpages/servletterminology/images/servlet-container1.png">


## State

The servlet container is the part of web server which can be run in a separate process. We can classify the servlet container states in three types:

**Standalone state**

It is typical Java-based servers in which the servlet container and the web servers are the integral part of a single program. For example:- Tomcat running by itself

**Inprocess**

It is separated from the web server, because a different program is runs within the address space of the main server as a plug-in. For example:- Tomcat running inside the JBoss.
The in-process Servlet containers are the containers which work inside the JVM of Web server, these provides good performance but poor in scalibility. 

**OutOfProcess**

The web server and servlet container are different programs which are run in a different process. For performing the communications between them, web server uses the plug-in provided by the servlet container.

The out-of-process containers are the containers which work in the JVM outside the web server. poor in performance but better in scalibility 
In the case of out-of-process containers, web server and container talks with each other by using the some standard mechanism like IPC. 

In addition to these types of containers, there is 3rd type which is stand-alone servlet containers. These are an integral part of the web server.

## App vs Web Servers
<img src="https://www.google.co.in/imgres?imgurl=https://realtimelogic.com/images/appserver-vs-webserver.jpg&imgrefurl=https://realtimelogic.com/products/web-server-vs-application-server/&h=724&w=1361&tbnid=JakytO8LVAytGM:&tbnh=112&tbnw=211&usg=__-11wuSTmJipfj72iPbJdT0DJCvU%3D&vet=10ahUKEwjwnfnwiMbaAhUKKo8KHfTQCrsQ9QEILDAA..i&docid=i_5hvygcXZqexM&sa=X&ved=0ahUKEwjwnfnwiMbaAhUKKo8KHfTQCrsQ9QEILDAA">




