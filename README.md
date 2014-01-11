Beaki is a script designed specifically for lazy neckbeards who want to quickly create Powerpoint-like presentations.

It takes a simple text file formatted in the wikipedia's articles syntax, and outputs a LateX/Beamer document, ready to be compiled.
Look at the example file for the syntax.

Installation
========
Create a .beaki directory in your $home folder, then copy the preamble.tex file in the .beaki folder:
mkdir ~/.beaki && cp preamble.tex ~/.beaki
You can modify this file to your likings, change the colours and the theme (default is Warsaw).
Then make the script executable and put it in the right place:
chmod +x beaki && sudo mv beaki /usr/bin

Usage
=====
First, type your presentation (the first 4 lines stand for the title, your name, institute and date in that order).
When you're done, simply run:
beaki your_file
to generate the pdf document.
