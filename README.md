# Hello-world
Repository created for exercises in Python.
I am Forestriver. Learning Python, hungry for new technologies )

# factorial

def factorial(x):
    if x == 0:
        return 1
    return x * factorial(x - 1)


anti_vowel

def anti_vowel(n):
    if n == "":
        return n
    elif n[0] in "AEIOUaeiou":
        return anti_vowel(n [1: ])
    else:
        return n[0] + anti_vowel(n [1: ])
        
