Btrplace Sandbox
===============================

This web application allows to simply test the behavior of BtrPlace.
It first generate a sample configuration. The user can then write
some placement constraints and check BtrPlace fix the configuration when
it is stated as not viable.

- author: Fabien Hermenier
- contact: fabien.hermenier@unice.fr

The last release of the sandbox is always deployed and usable on [this server] (http://btrp.inria.fr/sandbox).

Installation Notes
-------------------------------

The build process is managed by [maven] (http://maven.apache.org). Once installed, just type

    $ mvn install

to resolve the dependencies, compile and package the sandbox.
The resulting war file will be located in the `target` directory and should be deployable
on a servlet server.

To test the sandbox without having to use an existing servlet server, just type

    $ mvn tomcat7:run

to deploy the war inside an embedded tomcat server.
The webapp will then be available at [localhost:8080] (http://localhost:8080).

Release notes
-------------------------------

### 21 nov. 2012 - 1.2.1 ###
- bug fixes

### 19 sep. 2012 - 1.2 ###
- binaries are directly available on github
- bug fixes and UI improvements
- update dependencies
- support for the 'online' and the 'offline' constraints

### 18 sep. 2012 - 1.1 ###
- a 'pin' feature to lock then save a sandbox
- a player to navigate through the reconfiguration process
- bug fixes

### 12 sep. 2012 - 1.0rc4 && 1.0rc5 ###
- update dependencies
- addition of an internal repository for non available dependencies.

### 11 sep. 2012 - 1.0rc2 && 1.0rc3 ###
- spell checking
- minor visual improvements

### 9 sep. 2012 - 1.0rc1 ###
- initial release

Copyright
-------------------------------
Copyright (c) 2012 University of Nice-Sophia Antipolis. See `LICENSE.txt` for details.
