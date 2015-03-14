### Release Notes for krail-master 0.5.4

All version conflicts in the build are resolved, some other dependency versions updated

#### Change log

-   [12](https://github.com/davidsowerby/krail-master/issues/12): Remove classpath 'org.ajoberstar:gradle-git:0.12.0' from build.gradle
-   [13](https://github.com/davidsowerby/krail-master/issues/13): upgrade to vaadin plugin 0.9.7
-   [15](https://github.com/davidsowerby/krail-master/issues/15): resolve dependency version conflicts
-   [16](https://github.com/davidsowerby/krail-master/issues/16): Use neater syntax for version conflict resolution 


#### Dependency changes

   compile dependency version changed to: krail:0.9.0
   compile dependency version changed to: krail-testUtil:1.0.9
   compile dependency version changed to: q3c-testUtil:0.7.6

#### Detail

*Updated version information*


---
*Fix [16](https://github.com/davidsowerby/krail-master/issues/16) Tidies version conflict resolutions*

No changes, just using the more concise 'force' syntax


---
*Fix [13](https://github.com/davidsowerby/krail-master/issues/13) Gradle Vaadin plugin updated to 0.9.7*


---
*Fix [12](https://github.com/davidsowerby/krail-master/issues/12) Removed gradle git plugin*

Functionality replaced by q3c-gradle


---
*Fix [15](https://github.com/davidsowerby/krail-master/issues/15) Resolve dependency version conflicts*

There are quite a few of them, all have been resolved to the later version


---
*See [krail 304](https://github.com/davidsowerby/krail/issues/304) Change to logback*

Modified build to use logback


---
