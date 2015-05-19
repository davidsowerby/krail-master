### Release Notes for krail-master 0.6.2

Upgrade to Vaadin 7.4.6, Guice 4.0.  Minor change to build file for bintrayUpload.  q3c-gradle updated

#### Change log



#### Dependency changes

   compile dependency version changed to: krail:0.9.3
   compile dependency version changed to: krail-testUtil:1.0.12
   compile dependency version changed to: q3c-testUtil:0.7.9

#### Detail

*Updated version info*


---
*Vaadin 7.4.6*


---
*Guice 4.0*


---
*Vaadin 7.4.5*


---
*Bintray upload changes*

dryRun=true by default (set by krail-master), unless overridden by individual projects


---
*Updates dependency versions*

q3c-gradle and bintray plugin.  This should enable further build automation


---
*Removed 'cpas' project, should not be in the master build*


---
*See [krail 372](https://github.com/davidsowerby/krail/issues/372) Change validation API version*

Reverted to javax.validation API to 1.0.0 GA.  The later version of 1.1.0 is incompatible with GWT


---
