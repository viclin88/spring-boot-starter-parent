# spring-boot-starter-parent
Parent pom providing dependency and plugin management for applications built with Maven

[![](https://jitpack.io/v/cloud-technology/spring-boot-starter-parent.svg)](https://jitpack.io/#cloud-technology/spring-boot-starter-parent)

## How to use
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
	<relativePath/> <!-- lookup parent from repository -->
    </parent>
```

## Dependency
| library                  | version       |
|--------------------------|---------------|
| spring-boot              | 2.3.0.RELEASE |
| spring-boot-maven-plugin | 2.3.0.RELEASE |
| spring-cloud             | Hoxton.SR4    |
| logstash-logback-encoder | 6.3           |
| chaos-monkey             | 2.2.0         |
| jacoco-maven-plugin      | 0.8.5         |
| sonar-maven-plugin       | 3.7.0.1746    |
| testcontainers           | 1.14.2        |

## Code Style
[Google Java Style](https://github.com/google/google-java-format)  
[Maven plugin](https://github.com/Cosium/git-code-format-maven-plugin)

Manual code formatting
```bash
./mvnw git-code-format:format-code -Dgcf.globPattern=**/*
```

Install git hook
```bash
./mvnw git-code-format:install-hooks
```

[Using google-java-format with VS Code](https://www.sethvargo.com/using-google-java-format-with-vs-code/)

