# timey-wimey

## Description

Timeywimey is a collection of libraries providing conversion utilities for JodaTime, Legacy `java.util.Date`, and Java 8 `java.time` classes.

`timeywimey-core` provides Java static methods for the conversion logic usable in both Java 8 and Scala.

`timeywimey-scala` includes Scala implicits to provide syntactic sugars `.asJava` and `.asJoda`.

This is a Cropster maintained version of the [original project from meetup](https://github.com/meetup/timeywimey).

See the [original README](README-orig.md) for more details and usage.


## Build and Publish


1. Configure your `gradle.properties`, from `gradle.properties.sample`
2. Build and test
  ```
  gradle build test
  ```
3. Publish to Nexus
  ```
  gradle publish
  ```
