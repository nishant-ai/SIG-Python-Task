1. <b>Use List Comprehension to</b>:

    i  - Create a list of all alphabets in english - both Capitals and Smalls.

    ii - Create a list of first n even and odd numbers and add each element of
        both list to print a new list : even[i] + odd[i] = result[i]

        e.g:- n=5
        even =  [2, 4, 6, 8, 10]
        odd =   [1, 3, 5, 7, 9]
        result= [3, 7, 11, 15, 19]
    
2. <b>Create a program to store the given data of multiple Books in a "Dictionary" - a temporary data holder</b>.

    Data to hold: 1. Name of Book
                  2. Price of Book
                  3. Author of Book

    e.g: 
    Input:

        name="The Great Gatsby"
        price=210
        author="F. Scott Fitzgerald" 

        name="The Shoe Dog",
        price=400,
        author="Phil Knight"

    Output: 

        books = [
        {
            name: The Great Gatsby,
            price: 210,
            author: F. Scott Fitzgerald
        },
        {
            name: The Shoe Dog,
            price: 400,
            author: Phil Knight
        }
        ]
    
    Note: You have to store each dictionary (containing data of one book) in a common list
    Try to Store upto 5 books data, and attach the I/O Screenshot to the task upload.

3. <b>Create a program that take input a list of strings and a string,
    and outputs all the strings in the list which are sub strings of the string.</b>

        Input: l = ["abc", "abcde", "abba", "bbaa", "Manbhia", "zcxd"]
             str = "ab"

        Output: abc, abcde, abba
    
    Note* => " Output must be in single line separated by ',' "


## <b>OPTIONAL CHALLENGE: En-Route-Salute</b>

Commander Lambda loves efficiency and hates anything that wastes time.
She's a busy lamb, after all! She generously rewards henchmen who identify
sources of inefficiency and come up with ways to remove them.
You've spotted one such source, and you think solving it will help you build
the reputation you need to get promoted.

Every time the Commander's employees pass each other in the hall,
each of them must stop and salute each other - one at a time -
before resuming their path. A salute is five seconds long, so each 
exchange of salutes takes a full ten seconds 
(Commander Lambda's salute is a bit, er, involved). 
You think that by removing the salute requirement, 
you could save several collective hours of employee time per day. 
But first, you need to show her how bad the problem really is.

Write a program that counts how many salutes are exchanged during a typical walk
along a hallway. The hall is represented by a string. 
    For example: "--->-><-><-->-"

Each hallway string will contain three different types of characters: 
    '>', an employee walking to the right; 
    '<', an employee walking to the left; 
    and '-', an empty space. 
Every employee walks at the same speed either to right or to the left, 
according to their direction. Whenever two employees cross, 
each of them salutes the other. They then continue walking until they reach the end,
finally leaving the hallway. In the above example, they salute 10 times.

Write a function answer(s) which takes a string representing employees walking 
along a hallway and returns the number of times the employees will salute. 
s will contain at least 1 and at most 100 characters, each one of -, >, or <.

**TestCases**

    Input:
        (string) s = ">----<"
    Output:
        (int) 2

    Input:
        (string) s = "<<>><"
    Output:
        (int) 4

<b>Hint</b>: 
    Try to Focus on what the question really wants! 
    Donot get confused in the Storyline! 😄
    Its an easy question (Concepts used: Loops and Conditionals)
    

