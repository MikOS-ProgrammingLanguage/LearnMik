# __2.0 Get Started__

Now that we covered what mik is and why one may use it, we can finally start, right?
Well... no. Unfortunately not. To run any program we need a compiler (which is just a program that takes source code and generates machine code). Therefore we first need:

## __2.1 Installation guide__

You have two options to install the Mik compiler (mic):

1. Via the [website]("https://mikpl.gq/Download.html")
2. Via Github. Which i will cover here

First run the following command

    git clone https://github.com/MikOS-ProgrammingLanguage/MicNewDawn.git

Then go into the directory you cloned the repo to and execute the following command

    λ> cd your/path/MicNewDawn
    λ> make
    λ> export PATH="your/path/MicNewDawn/:$PATH"
    λ> mic -install

The mik compiler as well as the mik package manager should now be ready to use!

## __2.2 Mic and Mip__

### __Mic__

mic, which is an acronym for Mik compiler, is the tool that compiles your programs!

### __Mip__

mip, which is an acronym for Mik package manager, is a package manager that lets you: download packages, initialize your project, and manage your projects!

## __2.3 Hello World!__

Now that we covered all that boring stuff, let's start programming. And what would be a better example than the good old _"Hello, World!"_

First create a file ending in _.mik_

Then write the following [code](../examples/02/hello_world.mik):

    puts("Hello, World!")

Simple, right? Yes! Puts is just a function that takes a string as an argument and prints it to stdio (Your terminal)
