Angular Konami Code
===================

> A [Konami Code](http://pt.wikipedia.org/wiki/C%C3%B3digo_Konami) directive to help Angular applcations do amazing stuff to surprise their users!

![](http://www.itecportal.com/wp-content/uploads/2013/09/the_code_by_decibel_design-d4c34gt.jpg)

## Install

As this component is composed of an angular module which contains a directive, to install it you should use whatever package manager you prefer, import *angular-konami.js* to your HTML, and include **konami** as a dependency to your main Angular module.

## Usage

Add the directive *konami* as an attribute to any DOM element you have. The attribute's value should be an Angular expression that will get evaluated when the user types the correct Konami Code. Examples:

```
// Simple counter expression.
<hero konami-code="life++"></hero>

// Scope method expression. For this to work, you must have the function defined to your scope.
<hero konami-code="extraLife()"></hero>
```

### Custom keys

You can also use this directive with custom activating keys. To do that, simply add another attribute to the element called *konami-keys*, passing an array of key codes as it's value. Example:

```
<hero konami-code="hadouken()" konami-keys="[40, 39, 65]"></hero>
```

![](http://i598.photobucket.com/albums/tt68/xXONEXx/Decorated%20images/hadouken.png)

## License

The MIT License (MIT)

Copyright (c) 2014 Lucas Constantino Silva

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
