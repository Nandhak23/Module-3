Exp.No:3a
STRING - FIND AND REPLACE
AIM

To write a Python function to accept a string, identify a word to be replaced, and replace it with a new word provided by the user.
ALGORITHM

    Begin the program.
    Input the original string str1 and the word to be replaced replace_str.
    Ask the user to input the new replacement word str2.
    Use the replace() method in Python to replace all occurrences of replace_str in str1 with str2.
    Store the modified string in str3.
    Display the original string (str1) and the modified string (str3).
    Terminate the program.

PROGRAM

def replacestr(m, n):
    r=input()
    print("The old string is",m)
    
    print("the new string is",m.replace(n,r))

OUTPUT

WhatsApp Image 2025-04-28 at 20 24 47_f1800502
RESULT

Thus a Python function to accept a string, identify a word to be replaced, and replace it with a new word provided by the user has been implemented and executed.
