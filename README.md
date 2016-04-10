[![Release](https://jitpack.io/v/neuralcubes/libsphero.svg)](https://jitpack.io/#neuralcubes/libsphero)
# Intro
A maven repo for easy access to the Sphero SDK for Android


In order to use this add the following in your gradle:

```gradle
allprojects {
        repositories {
                ...
                maven { url "https://jitpack.io" }
        }
}
```

```gradle
dependencies {
        compile 'com.github.neuralcubes:libsphero:3.1.159'
}
```

or pom file:

```xml
        <repositories>
                <repository>
                    <id>jitpack.io</id>
                    <url>https://jitpack.io</url>
                </repository>
        </repositories>
```

```xml
        <dependency>
            <groupId>com.github.neuralcubes</groupId>
            <artifactId>libsphero</artifactId>
            <version>3.1.159</version>
        </dependency>
```

                                                                                                        
