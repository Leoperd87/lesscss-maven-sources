lesscss-maven-sources
===================

LessCSS 2.1.2 sources.

### Usage
The following POM plugin configuration

```
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
    ...
    <dependencies>
        ...
        <dependency>
            <groupId>ua.in.dej</groupId>
            <artifactId>lesscss-maven-sources</artifactId>
            <version>1.20</version>
            <classifier>2.1.2</classifier>
            <type>zip</type>
        </dependency>
    </dependencies>
</project>
```