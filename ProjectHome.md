## Update May 2014 ##
The licensing of this project is now under Apache 2:
http://www.apache.org/licenses/LICENSE-2.0

Any references in this project's code to the GPL can be ignored and replaced with Apache 2.


## Update July 2010 ##
I have updated the project file to use Netbeans 6.9.  In addition I have added a new data manager interface to the project so new backing stores can be added but require the minimum functionality already in the MySQL Data Manager provided in the source code.

Due to many requests I've now added the source code to the GFSClient.swc.  Its a mess and needs some cleaning and refactoring but here it is anyway.


## Update May 2010 ##
I have updated the project file to use Netbeans 6.8 as well as Apache Mina 1.1.7, the latest MySQL JDBC Connector, and the latest SLF4J.  I am hoping to overhaul this project as time permits and eventually put the code into Subversion as it should be.  Once the code is in Subversion I'll be seeking volunteers who would like to help with this project.  I would also like to update the documentation as well as the Flash/Flex examples to use the latest CS5 suite of tools (Flash Pro CS5 and Flash Builder 4).  Drop me an email if you would like to help out on this project!

**So to recap here are a few things off the top of my head I'd like to do:**

  * ~~Create an interface so GFS Server can quickly and easily switch between datastores (MySQL, MongoDB, SimpleDB, CouchDB, etc.)~~ Done!

  * Clean up the code (refactor, implement best practices)

  * Add members to this project to help out

  * Update all documentation and examples


## GFS Server ##

GFS Server was born in January 2008 as a side project.  I wanted to create a socket server for Flash and Flex clients in a minimal amount of time.  Using existing projects like Apache Mina (and others) I was able to essentially glue together a socket server that worked well originally based off of the Apache Mina sample code.

With GFS Server you can host multi-player chat rooms and games easily.

Keep in mind this was a project born in my spare time and written to be up and running in very little time.  There are many sharp edges and best practices that can and should be incorporated into the code base but unfortunately are not there at this time.  In a nutshell the code needs a lot of tender loving care.  I've been asked by more than one person to open source this - so here it is warts and all.

This project uses several open source code from several different developers.  Unless otherwise specified the GFS Server code is licensed under the GPL 2.