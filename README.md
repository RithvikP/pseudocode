# Pseudocode

Pseudocode is a live programming environment for writing natural language programs implemented by [Keshav Saharia](http://keshav.is) and maintained by the instructors/interns at [TechLab Education](https://techlab.education). 
It is designed to be a fun introduction to typed programming languages, without the burden of syntactical correctness or error messages. 

**Keshav will add GIF here**

There is no "run" button and no error messages - code is executed as you type it, and instructions that cannot be understood are ignored. After teaching with pseudocode, we teach Python with [Pythonroom](https://pythonroom.com) and Java with the [APCS graphics](http://apcs.io) library. 

## Getting started

For Mac OSX, the easiest way to get started is to download the [Pseudocode application](https://github.com/MAC_APP_URL) and copy it into your Applications folder.

You can also download a [runnable JAR file](https://github.com/JAR_FILE_URL) that will work on any operating system with a Java runtime environment.

## Features

### Drawing shapes

Draw a circle/square/rectangle/oval

```
draw a circle
```

** put an image of a circle**


You can position this circle 

```
draw a circle at 100 100
draw a circlea at the center
```

Its attributes are width, height, radius, size, diameter

```
draw a circle at 100 100 with a radius of 50
draw a square at 100 100 with a width of 50 and height of 50 
```

You can color the shape

```
draw a red circle
```

### Drawing images

You can draw an image by giving a url or file path

```
draw an image "URL"
draw an image "FILE_PATH"
```

Images have the same attributes as shapes

```
draw an image "URL" at 100 100 with a size of 50
draw an image "URL" at 100 100 with a width of 50 and height of 50
```

### Colors

You can use preset colors such as blue, green, or light green

```
draw a red circle
```

You can use RGB values

```
draw a rgb 255 0 0 circle
```

Your can use Hex codes

```
draw a #fffffff circle
```

You can use random colors

```
draw a randomly colored circle
draw a random color circle
```

### Forever loops

```
forever draw a small circle at the mouse
```

## Examples

- draw shapes
- infinite loops
- write if statements
- write if-else statements
- get mouse position and clicked

## Todo list

**everyone** - create examples in the `example` package as `My_Example.pseudo`

- [√] Get all keywords into expression/Constant.java
- [√] Formatting the editor
- [√] Console for print output
- [√] Add polygons (`draw a polygon from a, b to c, d to e, f`)
- [√] String interpolation (`print "the value of the variable is #variable and I am at #x, #y"`)
- [√] Draw an image from the web (`import "https://image.com/image.png" as xyz` ... `draw xyz at 300, 300`)
- [ ] Ensure all files are commented
- [√] Random numbers
- [√] Random color
- [√] Commenting in the code (`// comment`) - add to Lexer.java, not to Parser.java
- [√] Square root and absolute value (`square root of x`, `absolute value of x`)
- [√] Distance function (`distance from x, y to a, b`)
- [ ] Mesh with other
- [ ] Fix mouse clicked event
- [√] Arbitrary RGB colors (`draw an rgb 1, 2, 3 square`) and hex codes*
- [ ] Parser tests - test individual parsing routines

* in the Window.java library

## Future todo list

- [ ] Lists
- [ ] Functions

```
to draw a triangle at x, y,
	...
	
draw a triangle at x, y
```

```
to add one to x,
	set x to x + 1
	increment x
```

- [ ] Simple class

```
a ball has an x, y

when a ball is created,
	set x to a random number
	set y to a random number

when a ball is told to draw,
	draw a red circle at ball's x, ball's y

set b to a new ball
tell b to draw
```

## Mesh

- When you join the mesh, asks for your name
- Once you're in the mesh, then other people can access your variables
- Should be completely transparent, no need to write/read explicitly from the mesh

```
draw a green circle at keshav's x, keshav's y
```
