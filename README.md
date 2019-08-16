JBoss Jakarta Interceptors
==================================

This is fork of Jakarta Interceptors, with few extra fixes to make it work better inside WildFly.

Upstream used: https://github.com/eclipse-ee4j/interceptor-api

Building
--------

Jakarta Interceptors can be built by executing the following from the project root:

``mvn clean package``

The API jar can then be found in /api/target.

Making Changes
--------------

To make changes, fork this repository, make your changes, and submit a pull request.

About Jakarta Interceptors
-------------

Jakarta Interceptors defines a means of interposing on business method invocations
and specific events—such as lifecycle events and timeout events—that occur on instances
of Jakarta EE components and other managed classes.
