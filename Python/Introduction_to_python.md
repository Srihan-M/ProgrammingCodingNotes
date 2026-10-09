---

Title: "Python 101"
Date: 2026-10-04
Author: "Srihan Manukonda"

---
 

<br>

# Section 1: Introduction to <kbd>*Python*
I am going to start the document off by writing my notes on *Python* as it is a language that can be the blueprint of many different languages. Though learning *Python* is a simple thing, through its simplicity it can evolve into a complex coding language to do just about anything. As you evolve as a developer *Python* evolves and adapts with you.\
\
Did you know that *Python* 
* Started out as a Christmas Project 
* Is actually named after a Comedy Show

    <br>

    ### <kbd>Python 101 

    Though *Python* seems complex, it is actually pretty simple to learn and is widely considered best for beginners.

    * Here are some basics 

        1. **Print** is a basic function mainly used to send messages to the console or to output a message.
            ```python
                print("Lets Start Learning Python")
                
                #Output:Lets Start Learning Python
            ``` 

        2. **Variables** are a main part of coding language. In *Python* if you want to input a variable it is fairly simple. **Variables** can be inputted as many things, such as strings, lists, integers, floats, etc. 
            ```python
                Variable_String = "Lets Start Learning Python"
                Variable_Integer = 9
                Variable_Float = 9.99
                Variable_List = ["Lets", "Start", "Learning", "Python"]
                print(Variable_String)
                
                #Output:Lets Start Learning Python
            ```
        3. **Comments** may not seem essential until you actually start writing a *Python* script and you find out, it is near impossible to find a single function or remember what a function does exactly. You create a comment by using a # for a **single line** but if you want a **multi-line** then you can use a triple quotation mark """.
            ```python
                print("Lets Start Learning Python")
                #This prints Lets Start Learning Python
                """This is a longer way to say
                This prints Lets Start Learning Python"""
                #Output:Lets Start Learning Python
            ```
        4. **Input** is the best way to make your code interactive. Though inputs **always** return strings so if you need to convert it to a float or an integer, you **cannot** forget to convert it or else your code will fail.
            
            ```python
                python = input("Do you want to start learning Python?")
                if python == "yes":
                    print("Lets Start Learning Python")
                
                #Input:yes
                #Output:Lets Start Learning Python
            ``` 
        5. **Math** is a crucial concept anywhere and in *Python* it is essential in a lot of code. You can start using it by using + to add, - to subtract, / to divide and * to multiply. Those are the basics after that // is floor division(this means when you divide it **rounds down the decimal** e.g. 8//3 = 2 {Because 2.67 goes down to 2} and 5//2 = 2), the next is exponents like ** so 2 to the power of 2 would be 2**2. Also comparison is found in *Python*. If you want to say if X is = 2 , you would say if X == 2. If you want to say if X is **not** = 2, it becomes if X != 2. Then less than and greater than stay the same X > 2 and X < 2 but if you want to say greater than or equal to you say X >= 2 and less than or equal to becomes X <= 2.
            ```python
                Add = (2+2)
                Minus = (2-2)
                Multiply = (2*2)
                Divide = (2/2)
                Floor_Divide = (2//2)
                Exponents = (2**2)
                if x == 1000:
                    equal = True
                if x != 1000:
                    equal = False
                if x < 1000:
                    less = True
                if x > 1000:
                    greater = True
                if x >= 1000:
                    greater_equal = True
                if x <= 1000:
                    less_equal = True 
             ``` 
        6. **Conditional Statements** are also a part that is extremely useful. Just about every major *Python* file that you use in your day to day life probably uses Conditional Statements. The Conditional Statements are **If, Elif, Else**. You probably already know what **if** and **else** are. Example [if X == 1000: print("x==1000") else: print("x!=1000")]. **Elif** is like if someone told you that you can't buy 10 ice creams but instead of just leaving, you ask if you can buy 5 ice creams instead of 10.
            ```python
                ice_cream = 5 

                if ice_cream == 10:
                    print("Yes I will buy 10 Ice creams")
                elif ice_cream == 5:
                    print("I will buy 5 Ice Creams instead of 10")
                else:
                    print("I'm Leaving.")

                Output:
                    I will buy 5 Ice Creams instead of 10
            ```
    
