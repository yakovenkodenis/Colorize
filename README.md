# Colorize
A tiny java library for generating random pleasing colors

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
