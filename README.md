Releases
========

Release artifacts for some of the repositories at [https://github.com/uklance](https://github.com/uklance). These
artifacts can be used by your dependency management tool of choice (eg [maven](http://maven.apache.org/), 
[gradle](http://www.gradle.org/), [ivy](http://ant.apache.org/ivy/) etc).

Maven Usage
-----------
Add the following to the repositories section of your ```pom.xml```
```xml
<repositories>
    <repository>
        <id>uklance-releases</id>
        <url>https://raw.github.com/uklance/releases/master</url>
    </repository>
</repositories>
```
