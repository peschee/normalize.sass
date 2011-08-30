normalize.css
=============

Normalize.css is a customisable CSS file that makes browsers render all elements more consistently and in line with modern standards. We researched the differences between default browser styles in order to precisely target only the styles that need normalizing.

[Check out the demo](http://shkm.github.com/normalize.sass/demo.html)

normalize.sass
--------------

Normalize.sass is simply a sass version of normalize.css. It was generated with sass-convert and pored over for clarity.

What does it do?
-----------

* Preserves useful defaults, unlike many CSS resets.
* Normalizes styles for a wide range of elements.
* Corrects bugs and common browser inconsistencies.
* Improves usability with subtle improvements.
* Explains what code does using detailed comments.

How to use it
-----------

It is suggested that you read through the `normalize.sass` file and customise it to meet the design requirements of a project, rather blindly including it as a "black box".

Generate the sass with:  
```sass normalize.sass > normalize.css```

Alternatively, generate and minify:  
```sass -t compressed normalize.sass > normalize.css```

Prefer SCSS syntax?  
```sass-convert normalize.sass normalize.scss```

Browser support
-----------

* Google Chrome
* Mozilla Firefox 3+
* Apple Safari 4+
* Opera 10+
* Internet Explorer 6+

License
-----------

Public domain

Acknowledgements
------------

Normalize.css is a project by [Nicolas Gallagher](http://github.com/necolas) and [Jonathan Neal](http://github.com/jonathantneal).