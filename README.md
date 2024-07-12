# Getting Started

## Table of contents
1. [Introduction](#introduction)
2. [Variables](#variables)
3. [Data Types](#datatypes)


## Introduction

Javascript is a pretty flexible language. Initially used to be just for browser related stuff,but now is more flexible as u can use it in servers, mobile apps, etc.

For a long time, JavaScript evolved without compatibility issues. New features were added to the language while old functionality didn’t change.

That had the benefit of never breaking existing code. But the downside was that any mistake or an imperfect decision made by JavaScript’s creators got stuck in the language forever.

This was the case until 2009 when ECMAScript 5 (ES5) appeared. It added new features to the language and modified some of the existing ones. To keep the old code working, most such modifications are off by default. You need to explicitly enable them with a special directive: "use strict".

<a id="introduction"></a>

## Variables

Use the `let` keyword to define variables. Javascript implicitly type casts, so no need to declare the data type explicitly. For example:
```
let str = "Hello world!!!"
console.log(str)
```

The `var` keyword also pretty much does the same thing(old script).
```
var x = 10
```

### Variable Naming
* The name must contain only letters, digits, or the symbols $ and _.
* The first character must not be a digit.
* Case sensitive
* Other language letters(non latin) are allowed
* Cannot be a reserved word

You can ignore using `let` or `var` in theory in the modern script, but its a bad practice. Also it still gives an error in `"use strict"`

### Constants

Use the keyword `const`. Its a widespread practice to use uppercase letters for constants, so its better to follow that convention
```
const COLOR_BLUE = '#00F'
```

But constants that are calculated in run time need not be written in caps. For example, a constant that calculates the number of valid items after reading data.

<a id="variables"></a>

## Data Types



<a id="datatypes"></a>