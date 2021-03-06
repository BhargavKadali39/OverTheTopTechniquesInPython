# OverTheTopTechniquesInPython
<h1> UNDER PROGRESS </h1>
Simplifying commonly used techniques for more optimized representation.

Python is a God's boon for the programmer's who belong to c,c++,java background.
Similarly very easy to learn if you're trying to learn programming as a beginner.

You would've already figured out what's the purpose of this repo,  
yes it's about simplified approaches toward daily use case techniques and methodology.  
I've previously posted some repository's regarding the similar use case like  
* [swapping-numbers](https://github.com/BhargavKadali39/Swapping_in_python)  
* [pattern-printing ](https://github.com/BhargavKadali39/Pattern-printing-in-python) which consists of a total 6 repos as per today (day this repo is posted).
* [Removing duplicates from a list](https://github.com/BhargavKadali39/Python_Data_Structure_Cheat_Sheet) program inside the given python file.  
BTW you can check out the Python_Data_Structure_Cheat_Sheet created by me for more detailed view of how they work.

Let's get to the topics I covered in this repo,
# concatenating strings
# string reverse
# combining lists using ZIP() function
# list to dict using zip()
# The _ operator
# Multiple user input
# The Walrus(:=) operator
# Passing N no.of arguments in a function
# passing values into tuples
*
*
*
<h2>concatenating strings</h2>
When we take input from user and store every char as a seperate element in a list we don't have to use a loop to join them all.
using join() command we can achieve that easily

    my_input = ["h","e","l","l","o"]
    my_output = "".join(my_input)
    print(my_output)
    
    output: hello
    
That's how it's done.
<h2>string reverse</h2>
This : is the Slice operator in python.
lemme shoe how to reverse a string using it.

        my_string = "im healthy and happy"
        print(my_string[::-1])
        
        output: yppah dna yhtlaeh mi

<h2>Using ZIP() function for list</h2>
We can add multiple lists together if they all have the same length.

        list_1 = ["you","so"]
        list_2 = ["are","smart"]
        for list_1,list_2 in zip(list_1,list_2):
            print(list_1,list_2)
            
            output:     you are
                        so smart

<h2>Walrus operator</h2>
Note: In order to make this operator work you need to have the latest python version,  
which is availabe on official python website.


The walrus operator is used to assign value and initialize at the same time while condition checking, therefore optimizing the code.

        my_list = [1,2,3,4,5]
        if (n:=len(my_list)>4):
            print(n)
            
            Output: True
