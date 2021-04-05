# read06

# Foreground Color
## color

There are three ways to specify colors in CSS:

1. RGB values
1. hex codes
1.  color names.
## rgb values
These express colors in terms of how much **red**, **green** and **blue** are used to make it up. For
example:
```css
rgb(100,100,90)
```
## hex codes
These are six-digit codes that represent the amount of **red**, **green** and **blue** in a color,
preceded by a pound or hash # sign. For example: 
```css
#ee3e80
```
## color names
There are 147 predefined color names that are recognized by browsers. For example:
```css
DarkCyan
```
## background-color
You can specify your choice of background color in the same  three ways:
```css
body {
  background-color: lightblue;
}
```

## Opacity opacity, **rgba**
Allow you to specify the opacity of an element
and any of its child elements,and the fourth value to
indicate opacity **(a)**

***rgba(red, green, blue, alpha)***
```css
<h1 style="background-color:rgba(255, 99, 71, 0);">rgba(255, 99, 71, 0)</h1>
```
the result of code:
<h1 style="background-color:rgba(255, 99, 71, 0);">rgba(255, 99, 71, 0)</h1>

## hsl, hsla

hsl(hue, saturation, lightness)
```css
<h1 style="background-color:hsl(300, 76%, 72%);">hsl(300, 76%, 72%)</h1>
```
the result of code:
<h1 style="background-color:hsl(300, 76%, 72%);">hsl(300, 76%, 72%)</h1>


hsla(hue, saturation, lightness, alpha)
```css
<h1 style="background-color:hsla(9, 100%, 64%, 0.2);">hsla(9, 100%, 64%, 0.2)</h1>
```
the result of code:
<h1 style="background-color:hsla(9, 100%, 64%, 0.2);">hsla(9, 100%, 64%, 0.2)</h1>