# Colorize
[ ![Download](https://api.bintray.com/packages/yakovenkodenis/maven/colorize/images/download.svg) ](https://bintray.com/yakovenkodenis/maven/colorize/_latestVersion)

A tiny java library for generating random nice looking colors.

## Installation

Download [colorize.jar](https://github.com/yakovenkodenis/Colorize/blob/master/colorize.jar) and add it to your libs folder.

## Usage

Get random color:

```java
String randomHexColor = Colorize.get();
```

Get color by name: (all available colors are listed [here](colors.md))

```java
String color = Colorize.get("blue");
```

Check if color is available:

```java
boolean colorAbailable = Colorize.checkColorAvailability("thistle");
```
