### Release Notes for krail-master 0.6.0

This version introduces Docker containers for testing, and enables testing on Tomcat 8

#### Change log

-   [5](https://github.com/davidsowerby/krail-master/issues/5): Upgrade Bintray plugin
-   [17](https://github.com/davidsowerby/krail-master/issues/17): org.assertj:assertj-core 2.0.0 has just been released
-   [18](https://github.com/davidsowerby/krail-master/issues/18): Use Tomcat in Docker containers for testing


#### Dependency changes

   compile dependency version changed to: krail:0.9.1
   compile dependency version changed to: q3c-testUtil:0.7.7
   compile dependency version changed to: krail-testUtil:1.0.10

#### Detail

*Version update information*


---
[krail 353](https://github.com/*davidsowerby/krail/issues/353) Vaadin 7.4.2*

Updated tests.  Had to undo the fix of [152](https://github.com/davidsowerby/krail-master/issues/152), as it was causing mock to fail for VaadinSession.  Raised a new ticket [354](https://github.com/davidsowerby/krail-master/issues/354).
rechecked and eliminated some 'force' statements in the Gradle ResolutionStrategy


---
[krail-bench 7](https://github.com/*davidsowerby/krail-bench/issues/7) Testbench update*


---
[krail 260](https://github.com/*davidsowerby/krail/issues/260) Tests set up for Tomcat 8*

Now defaults to Tomcat 8


---
*Fix [18](https://github.com/davidsowerby/krail-master/issues/18) Using container for test*

Works to a point, but is using a shell script to build and start the container.  The Gradle docker plugin does not yet support publishing ports, which is a shame because apart from that it worked.  (Code is commented out in build.gradle) .  Closing this issue but opened [19](https://github.com/davidsowerby/krail-master/issues/19) pending [plugin feature](https://github.com/bmuschko/gradle-docker-plugin/issues/30) becoming available.


---
*Fix [17](https://github.com/davidsowerby/krail-master/issues/17) assertj upgrade*


---
*Changed war destination for mount to container, see [18](https://github.com/davidsowerby/krail-master/issues/18)*


---
*Fix [5](https://github.com/davidsowerby/krail-master/issues/5) Bintray plugin to 1.1*


---
