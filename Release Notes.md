### Release Notes for krail-master 0.5.2

This version uses a later version of q3c-gradle to better support README generation, and removes the IDEA project files from Git

#### Change log

-   [9](https://github.com/davidsowerby/krail-master/issues/9): Add findBugs annotations to build
-   [10](https://github.com/davidsowerby/krail-master/issues/10): Run on Windows or Linux


#### Dependency changes

   compile dependency version changed to: krail:0.8.0
   compile dependency version changed to: krail-testUtil:1.0.7
   compile dependency version changed to: q3c-testUtil:0.7.4

#### Detail

*Fix [10](https://github.com/davidsowerby/krail-master/issues/10) Detects OS and calls appropriate command line*

startTomcat and stopTomcat are OS aware.  Requires that target environments have the commands set up.


---
*Update version information*


---
*Fix [9](https://github.com/davidsowerby/krail-master/issues/9) Added javax annotations to the build for code checking*


---
*gitattributes added*

To overcome Linux/Windows line ending issues


---
*Enable bintrayUpload*


---
*disable bintrayUpload*


---
