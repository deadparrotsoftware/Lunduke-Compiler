Lunduke-Compiler
================

A compiler for a made up dialect of the Lunduke Language (And you though lisp dialects were weird :P) 

The Lunduke-SDK has never been released and I've always been interested in the compiler but it's never been released so I'm going to write my own.

Grammar is mostly guess work based off a screen shot of LDE and unfortunately doesn't draw on the wiki which seems to be missing(if anyone has that description please let me know).

### Plan :

* Create Grammar

* Removed Left Recursion from the Grammar

* Left Factor the Grammar

* Write a Parser

* Write a compiler based on the parse tree

At Step 4 at the moment but will have to refine the Grammar significantly especially if details are released about the language.

### License :

* This software is MIT licensed see link for details

* http://www.opensource.org/licenses/MIT

### Get Involved:

Using Javacc, Google it to know more about the syntax.

To buil the Grammar:

    sudo apt-get install javacc
    cd Javacc Parser
    javacc LundukeGrammar.jj
    javac LundukeParser.java
    java LundukeParser # Takes input from stdin or file

### Note on copy right:

* I don't own copy right on the name Lunduke-Language or Lunduke-SDK or anything of the sort. If someone does I'll change the name.

### PS to Bryan:

If I need to change the name(or you just want me too) let me know and I will do so immediately.
