H2OXML : HTML to OpenXML Converter
==================================

Forked from https://github.com/ffmad/HTMLtoOpenXML

A simple PHP script supporting php 8.3 that takes HTML code and converts it into open XML code. (for Docx)

INSTALLATION
============

`composer require bersyatina/htmltoopenxml`

WHAT H2OXML CAN DO
==================

For now it can deal with :
  - Paragraphs
  - Bold, italic and underlined text (<strong|b|em|i|u>)
  - Bullet lists

Many more can be done (the wysiwyg editor had only simple functions)


HOW TO USE IT
=============

```
$parser = new HTMLtoOpenXML\Parser();

$ooXml = $parser->fromHTML($html);

```
