#krail-master

A Gradle master project, used purely to manage the build across the various [krail](https://github.com/davidsowerby/krail) libraries.

Note that the folder the project is in must be called 'master' in order for the parallel structure (master on the same level as sub-projects) to work.  Individual Git folders (one per project) are necessary to align the Git repositories with Bintray
#Download
<a href='https://bintray.com/dsowerby/maven/krail-master/view?source=watch' alt='Get automatic notifications about new "krail-master" versions'><img src='https://www.bintray.com/docs/images/bintray_badge_color.png'></a>
##Gradle

```
repositories {
	jcenter()
}
```

```
'uk.q3c.krail:krail-master:0.7.0'
```
##Maven

```
<repository>
	<id>jcenter</id>
	<url>http://jcenter.bintray.com</url>
</repository>

```

```
<dependency>
	<groupId>uk.q3c.krail</groupId>
	<artifactId>krail-master</artifactId>
	<version>0.7.0</version>
</dependency>
```
##Direct

[ ![Download](https://api.bintray.com/packages/dsowerby/maven/krail-master/images/download.svg) ](https://bintray.com/dsowerby/maven/krail-master/_latestVersion)

