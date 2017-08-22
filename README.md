# Support package

Main purpose of this library is to provide legacy prefixing as easily as SCSS's mixins allow.
And be to use, when you are not able to use any prefixing JS library in your project.

Library is consisted of few: 

* Mixins
* Functions
* Extendable classes
* and Color palette - *to keep your colors nice and organized*

### Prefixing

Simple

```
@include display(flex)
```

Gives you all the prefixes you need

```
display: -webkit-flex;
display: -webkit-box;
display: -moz-box;
display: -moz-flex;
display: -ms-flexbox;
display: flex;
```

*Note: Other functions are yet to be described.*

## Installing

Simply clone the repo inside of your project and include main.scss. That's it...
