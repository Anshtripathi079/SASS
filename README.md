# SASS
Sass is a CSS pre-processor.

Sass reduces repetition of CSS and therefore saves time.

## Why Use Sass?
Stylesheets are getting larger, more complex, and harder to maintain. This is where a CSS pre-processor can help.

Sass lets you use features that do not exist in CSS, like variables, nested rules, mixins, imports, inheritance, built-in functions, and other stuff.

## How Does Sass Work?
A browser does not understand Sass code. Therefore, you will need a Sass pre-processor to convert Sass code into standard CSS.

This process is called transpiling. So, you need to give a transpiler (some kind of program) some Sass code and then get some CSS code back.

## Sass Comments
Sass supports standard CSS comments /* comment */, and in addition it supports inline comments // comment.

## Sass Variables
With Sass, you can store information in variables, like:

- strings
- numbers
- colors
- booleans
- lists
- nulls

Sass uses the $ symbol, followed by a name, to declare variables:
```scss I'm A tab
$variablename: value;
```

