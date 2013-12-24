ZIP File System Standalone
==========================

A stand alone version of the zip file system included in JDK 7. It contains a fix for [bug 8004789](http://bugs.sun.com/view_bug.do?bug_id=8004789).

The code is under 3 clause BSD license and retains all the Oracale license headers.

The packages are prefixed with `com.github.marschall` like packages included in the JDK (like Xerces).

The name of the provider been changed from `jar` to `zipfs`.

```xml
    <dependency>
      <groupId>com.github.marschall</groupId>
      <artifactId>zipfilesystem-standalone</artifactId>
      <version>1.0.1</version>
    </dependency>
```

