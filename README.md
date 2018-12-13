# README

This README would normally document whatever steps are necessary to get the
application up and running.


#Topics to discuss
What is programming?
What is Ruby?
How to run Ruby programs
Basic Data Types
Variables and assignment
Control Structures
#What is Programming?
	Programming is the process of solving problems through code.  
	Different types of programming languages
#Low-level programming languages - C, C++
    Generally interact directly with the hardware layer
    Requires the developer to manage the resources available on the physical computer through their code
    Useful when you have very limited resources or are custom embedded systems

#High-level programming languages - Ruby, Python, Java
    Details of the hardware are taken care of by the language so that developers can solve more general problems
    The language is more expressive, meaning it allows solutions to be written in terms of "what to accomplish" rather than describing each step of "how to accomplish it"
    Useful for creating solutions that work across multiple platforms and when the hardware is not the focus
#What is Ruby?
	Founded by Yukihiro Matsumoto (Matz)  in 1993 (Japan)
    First stable version was released in 1995   
    Syntactically Simple
    Truly Object-Oriented
    Having Iterators and Closures
    Exception Handling
    Garbage Collection
    Portable
    Dynamic
    Ruby interpreter


#Executing Ruby Program
From the command line:

    $ ruby my_filename.rb
	
Irb
        You can also run Ruby using the irb command. It stands for "interactive Ruby".Though this won't let you save your inputs, it's a great way to play around with your code.
#Basic Data Types
		Number
        Integers: whole numbers, e.g. 10
        Floats: decimal numbers, e.g 7.2 or 0.2
        Arithmetic: +, -, *, /, %
        Comparisons: >, <, >=, <=, ==, !=
                String
                Boolean
                    "truthiness" 
                    "falsiness”
                Nil
	

#Converting between data types
        to_s: to string
        to_i: to integer
        to_f: to float
        !! ahead of a value converts to boolean
#Variables
        Meaningful names to variables
        Constants
#Output and Input
        puts allows us to display information in the terminal to the program's user.
        gets.chomp allows us to receive information from the program's user.
#Control Structures
        if / elsif / else
        While
        Comments in ruby #
