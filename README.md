# Book - Creation

* Use Jupyter Book
* Jupyter book seems to work well with Linux than windows

## Windows Operating System - Laptop/Desktop

* Install/enable WSL2
* Create a linux distribution
* Install Python
* Install Juypter book
* Follow Jupyter documentation and create the book

## Book Build

```
cd ~/git/book-how-to
jupyter-book build life-book
```

* <http://172.28.192.96:5500/life-book/_build/html/intro.html>

## Publish to github pages - Fixes needed

* .nojekyll file - Add a .nojekyll file to final output directory html 
* Find in *.html: "../_static -- Replace with: /static-jb-2023
* Find in: "_static -- Replace with: /static-jb-2023
* remove the _static from build\html output directory
* images with respect to book can i put in separate directory? my-images? see how it works?

## TODO

basics-cs
java-beginner

* <http://172.28.192.96:5500/java-beginner/_build/html/intro.html>

cd ~/git/book-how-to
jupyter-book build java-beginner


jupyter-book create computer-basics
jupyter-book build computer-basics