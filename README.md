# Example of a Java Program
> This is a simple program I wrote just to show you how
> to easily compile Java.

## Compiling
> To compile this program, just simply run:
>
        javac Main.java
>
> Then to start the compiled program run:
>
        java Main
>
## What's going on?
> Since the Main.java is our starting point of the program, we compile
> that file and Java will automatically compile files linked to it.
> Java will assume that the name of our program is called "Main" since
> the starting point is in our Main.java file.
> So to run our program called "Main" we need to tell java to run it using the
> "java" command and providing the name of our program which in our case is
> "Main".

## An easier way to compile
>
        shopt -s globstar
        javac **/*.java
>
> Here we are enabling globbing and then compiling every .java file
