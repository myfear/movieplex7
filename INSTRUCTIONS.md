# Java EE 7 Hands-on Lab with GlassFish 4
The Java EE 7 platform continues the ease of development push that characterized prior releases by bringing further simplification to enterprise development. It adds new and important APIs such as the REST client API in JAX-RS 2.0 and the long awaited Batch Processing API. Java Message Service 2.0 has undergone an extreme makeover to align with the improvements in the Java language. There are plenty of improvements to several other components. Newer web standards like HTML 5, WebSocket, and JSON processing are embraced to build modern web applications.

This hands-on lab will build a typical 3-tier end-to-end application using the
following Java EE 7 technologies:

* Java Persistence API 2.1 ([JSR 338](http://jcp.org/en/jsr/detail?id=338))
* Java API for RESTful Web Services 2.0 ([JSR 339](http://jcp.org/en/jsr/detail?id=339))
* Java Message Service 2.0 ([JSR 343](http://jcp.org/en/jsr/detail?id=343))
* JavaServer Faces 2.2 ([JSR 344](http://jcp.org/en/jsr/detail?id=344))
* Contexts and Dependency Injection 1.1 ([JSR 346](http://jcp.org/en/jsr/detail?id=346))
* Bean Validation 1.1 ([JSR 349](http://jcp.org/en/jsr/detail?id=349))
* Batch Applications for the Java Platform 1.0 ([JSR 352](http://jcp.org/en/jsr/detail?id=352))
* Java API for JSON Processing 1.0 ([JSR 353](http://jcp.org/en/jsr/detail?id=353))
* Java API for WebSocket 1.0 ([JSR 356](http://jcp.org/en/jsr/detail?id=356))
* Java Transaction API 1.2 ([JSR 907](http://jcp.org/en/jsr/detail?id=907))

Together these APIs will allow you to be more productive by simplifying enterprise development.
The latest version of this document can be downloaded from http://glassfish.org/hol/javaee7-hol.pdf

### Author
[Arun Gupta](http://blogs.oracle.com/arungupta), Java EE & GlassFish Guy || [@arungupta](http://twitter.com/arungupta)

## Table of Contents
1. Software Requirement
2. Problem Statement
    1. Lab Flow
3. Walk-­‐through of Sample Application
4. Show	Booking (JavaServer Faces)
5. Chat Room (Java API for WebSocket)  
6. View and Delete Movie (Java API for RESTful Web Services)
7. Add Movie (Java API for JSON Processing)
8. Ticket Sales (Batch Applications for the Java Platform)
9. Movie Points (Java Message Service 2)
10. Conclusion	
11. Troubleshooting

## 1. Software Requirement
The following software needs to be downloaded and installed:
* JDK 7 from http://www.oracle.com/technetwork/java/javase/downloads/index.html
* NetBeans 7.3 or higher “All” or “Java EE” version from http://netbeans.org/downloads/
* GlassFish 4 b87 from http://dlc.sun.com.edgesuite.net/glassfish/4.0/promoted/glassfish-4.0-b87.zip

Configure GlassFish 4 in NetBeans IDE following the instructions in **Appendix A**.
