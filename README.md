![promo](https://raw.githubusercontent.com/AlmasB/git-server/master/storage/images/fxgl_promo.jpg)

## About

<img src="https://raw.githubusercontent.com/AlmasB/git-server/master/storage/images/fxgl_logo.png" width="128" />

JavaFX Game Development Framework

[![Maven Central](https://img.shields.io/maven-central/v/com.github.almasb/fxgl.svg)]()
[![Javadoc](https://img.shields.io/badge/docs-javadoc-blue.svg)](https://www.javadoc.io/doc/com.github.almasb/fxgl-base/)
![CI](https://travis-ci.org/AlmasB/FXGL.svg?branch=master)
[![codecov](https://codecov.io/gh/AlmasB/FXGL/branch/master/graph/badge.svg)](https://codecov.io/gh/AlmasB/FXGL)

### Why FXGL?

* No installation or setup required
* "Out of the box": Java 8/9/10/11(alpha), Win/Mac/Linux/Android 5.0+([Sample](https://github.com/AlmasB/FXGL-MobileApp))/iOS([alpha](https://github.com/AlmasB/FXGL-MobileApp))/Web([alpha](https://github.com/AlmasB/FXGL-WebApp))
* Simple and clean API, higher level than other engines
* Superset of JavaFX: no need to learn new UI API
* Real-world game development techniques: Entity-Component, Event System, Scripting, etc.
* Games are easily packaged into a single executable .jar

### Good for:

* Any 2D genre (side-scroller / platformer / arcade / RPG)
* Complex UI controls
* Hobby / academic / commercial projects
* Teaching / learning / improving game development skills
* Fast prototyping of game ideas

### Features

* [More than 60 major features](https://github.com/AlmasB/FXGL/wiki/Core-Features)
* [Showcase](http://almasb.github.io/FXGLGames/)

### Minimal Example

```java
public class BasicGameApp extends GameApplication {

    @Override
    protected void initSettings(GameSettings settings) {
        settings.setWidth(800);
        settings.setHeight(600);
        settings.setTitle("Basic Game App");
    }

    public static void main(String[] args) {
        launch(args);
    }
}
```

## Getting Started

- Version for Java 8/9/10: `0.5.4`
- Version for Java 11: `11.0-alpha`

Note: from now on only 11.0+ will be developed.
FXGL 11 supports Java 11 and has a more scalable architecture,
but currently supports only a subset of features from `0.5.4`.

* [Java 11 modules](https://github.com/AlmasB/FXGL/wiki/FXGL-11-%28Java-11-modules%29)
* [Wiki & Written tutorials](https://github.com/AlmasB/FXGL/wiki)
* [YouTube tutorials](https://www.youtube.com/playlist?list=PL4h6ypqTi3RTiTuAQFKE6xwflnPKyFuPp)
* [Sample code demos](fxgl-samples)
* [Game demos](https://github.com/AlmasB/FXGLGames) (src)
* [Game demos](https://github.com/AlmasB/FXGLGames/tree/master/binaries) (.jar)

### Maven

* [Maven](https://github.com/AlmasB/FXGL-Maven) project if you use Java
* [Maven](https://github.com/AlmasB/FXGL-MavenKt) project if you use Kotlin

Already have `pom.xml`? Then add: (use `0.5.4` for Java 8/9/10)

```
<dependency>
    <groupId>com.github.almasb</groupId>
    <artifactId>fxgl</artifactId>
    <version>11.0-alpha</version>
</dependency>
```

### Gradle

* [Gradle](https://github.com/AlmasB/FXGL-Gradle) project if you use Java
* [Gradle](https://github.com/AlmasB/FXGL-GradleKt) project if you use Kotlin

Already have `build.gradle`? Then add: (use `0.5.4` for Java 8/9/10)

```
repositories {
    jcenter()
}

dependencies {
    compile 'com.github.almasb:fxgl:11.0-alpha'
}
```

### Uber jar

Download the latest uber jar from [Releases](https://github.com/AlmasB/FXGL/releases)

## Community

* University of Brighton, UK
* University of Nottingham, UK
* Walton High School, USA
* Zealand Institute of Business and Technology, Denmark
* Federal Institute of Education, Science and Technology of Rio Grande do Sul, Brazil

If your institution wants to use / is using FXGL, drop me an email to discuss how FXGL can aid your course.

### Contribution & Support

If you want to build FXGL from sources or want to contribute,
please see the [Contribution Guide](CONTRIBUTING.md) (including non-code).

You can support the FXGL development / show interest by simply starring the repo.

### Contact

* Ask questions on [StackOverflow](https://stackoverflow.com/search?q=fxgl) with tags `javafx` and `fxgl`
* Tweet with [#fxgl](https://twitter.com/search?src=typd&q=%23fxgl)
* [Chat](https://gitter.im/AlmasB/FXGL) with the friendly FXGL community
* ![Email](https://img.shields.io/badge/email-almaslvl@gmail.com-red.svg)
