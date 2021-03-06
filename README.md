# UnOfficial maven repository.

## using

add repository config into your maven project pom.xml.

```xml
<repositories>
    <repository>
	<id>bastengao-mvn-repository</id>
	<url>https://raw.github.com/bastengao/mvn-repository/master/releases</url>
    </repository>
</repositories>
```


## repositories

* [ftp4j](http://www.sauronsoftware.it/projects/ftp4j/)

```xml
<dependency>
    <groupId>it.sauronsoftware.ftp4j</groupId>
    <artifactId>ftp4j</artifactId>
    <version>1.7.2</version>
</dependency>
```

[ftp4j fixed](https://github.com/bastengao/ftp4j)

```xml
<dependency>
    <groupId>it.sauronsoftware.ftp4j</groupId>
    <artifactId>ftp4j</artifactId>
    <version>1.7.2-fixed</version>
</dependency>
```

* [jsmpp](https://code.google.com/p/jsmpp/)

```xml
<dependency>
    <groupId>com.googlecode.jsmpp</groupId>
    <artifactId>jsmpp</artifactId>
    <version>2.1.0-UO</version>
</dependency>
```


* [smslib](http://smslib.org/)

```xml
<dependency>
    <groupId>org.smslib</groupId>
    <artifactId>smslib</artifactId>
    <version>v3.5.3</version>
</dependency>
```

* [KPJavaSDK](https://github.com/KSkuaipan/KPJavaSDK)

```xml
<dependency>
    <groupId>com.kuaipan</groupId>
    <artifactId>kuaipan-java-SDK</artifactId>
    <version>0.2-beta</version>
</dependency>
```


* [UCanAccess](http://ucanaccess.sourceforge.net/site.html)

```xml
<dependency>
    <groupId>net.ucanaccess</groupId>
    <artifactId>ucanaccess</artifactId>
    <version>2.0.9.3</version>
</dependency>
```

## references

* [Hosting Maven Repos on Github](http://cemerick.com/2010/08/24/hosting-maven-repos-on-github/)
* [Use github as maven remote repository](http://blog.rueedlinger.ch/2012/09/use-github-as-maven-remote-repository/)
