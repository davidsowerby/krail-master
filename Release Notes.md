### Release Notes for krail-master 0.5.1

This version uses a later version of q3c-gradle to better support README generation, and removes the IDEA project files from Git

#### Change log

-   [4](https://github.com/davidsowerby/krail-master/issues/4): Remove IDEA project files from git
-   [6](https://github.com/davidsowerby/krail-master/issues/6): Shorten testPreparation task to testPrep
-   [7](https://github.com/davidsowerby/krail-master/issues/7): groupID is wrong for q3cTestUtil
-   [315](https://github.com/davidsowerby/krail-master/issues/315): Invalid issue number or uri.   https://api.github.com/repos/davidsowerby/krail-master/issues/315


#### Dependency changes

   compile dependency version changed to: krail:0.7.9
   compile dependency version changed to: krail-testUtil:1.0.6
   compile dependency version changed to: q3c-testUtil:0.7.3

#### Detail

*Set version information*


---
*Fix [315](https://github.com/davidsowerby/krail-master/issues/315) Upgraded to q3c-gradle 0.6.0*

The README has been amended to conform to the standard for [q3c-gradle](https://github.com/davidsowerby/q3c-gradle)


---
*Fix [7](https://github.com/davidsowerby/krail-master/issues/7). Removed group setting for q3c-testUtil*

This was incorrectly set in the master gradle build anyway, but has now been moved to q3c-testUtil.gradle


---
*Fix [krail 306](https://github.com/davidsowerby/krail/issues/306) Gradle Vaadin plugin upgraded to 0.9.6*

This resolves an [issue](https://github.com/johndevs/gradle-vaadin-plugin/issues/147) raised against the plugin


---
*Merge branch 'fix311' into develop*


---
*Fix [6](https://github.com/davidsowerby/krail-master/issues/6).  'testPreparation' task is now 'testPrep' task.  Name change only*


---
*Build file amended to use Vaadin 7.3.9, see [krail 305](https://github.com/davidsowerby/krail/issues/305)*


---
*Fix [4](https://github.com/davidsowerby/krail-master/issues/4) Removed IDEA project files from Git*


---
