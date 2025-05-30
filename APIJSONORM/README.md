# APIJSONORM  [![](https://jitpack.io/v/Tencent/APIJSON.svg)](https://jitpack.io/#Tencent/APIJSON) [<img src="https://devin.ai/assets/deepwiki-badge.png" alt="Ask DeepWiki.com" height="20"/>](https://deepwiki.com/Tencent/APIJSON)
腾讯 [APIJSON](https://github.com/Tencent/APIJSON) ORM 库，可通过 Maven, Gradle 等远程依赖。<br />
Tencent [APIJSON](https://github.com/Tencent/APIJSON) ORM library for remote dependencies with Maven, Gradle, etc.

### Maven
#### 1. 在 pom.xml 中添加 JitPack 仓库
#### 1. Add the JitPack repository to pom.xml
```xml
	<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
```
<br />

#### 2. 在 pom.xml 中添加 APIJSON 依赖
#### 2. Add the APIJSON dependency to pom.xml
```xml
	<dependency>
	    <groupId>com.github.Tencent</groupId>
	    <artifactId>APIJSON</artifactId>
	    <version>LATEST</version>
	</dependency>
```

<br />
<br />

### Gradle
#### 1. 在项目根目录 build.gradle 中最后添加 JitPack 仓库
#### 1. Add the JitPack repository in your root build.gradle at the end of repositories
```gradle
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
<br />

#### 2. 在项目某个 module 目录(例如 `app`) build.gradle 中添加 apijson-orm 依赖
#### 2. Add the APIJSON dependency in one of your modules(such as `app`)
```gradle
	dependencies {
	        implementation 'com.github.Tencent:APIJSON:latest'
	}
```

<br />
<br />

### FASTJSON 2
#### Code
https://github.com/Tencent/APIJSON/tree/fastjson2

#### Maven
https://mvnrepository.com/artifact/com.github.linushp/zikai-apijson/1.0

<br />

### Unit Test
http://apijson.cn/unit
