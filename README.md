# Sikuliator Test Format Specification

## General concerns
The format must strike a balance between simpleness and expressiveness.
It must be simple enough to allow tests that are easy to read.
A complex format with a lot of syntactic noise would mean low readability.
Following the original idea to use Python would most likely lead to the usage of many complex patterns and the inclusion of other libraries.
A more declarative style is probably suited.


## Version 1
Due to the limited time for the initial project a simple format based on XML will be used.
Only one parameter is allowed to keep it simple.
It is based on reusable sequences.
Simple actions like entering text and clicking are represented by XML elements.
An XML schema in [XSD](http://www.w3.org/TR/xmlschema11-1/) is used to describe the format.
