# spring-boot-starter-parent
Parent pom providing dependency and plugin management for applications built with Maven

[![](https://jitpack.io/v/cloud-technology/spring-boot-starter-parent.svg)](https://jitpack.io/#cloud-technology/spring-boot-starter-parent)

## How to
Step 1. Add the JitPack repository to your build file

```xml
	<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
```

Step 2. Change the parent
```xml
    <parent>
        <groupId>com.github.cloud-technology</groupId>
        <artifactId>spring-boot-starter-parent</artifactId>
        <version>${version}</version>
    </parent>
```
