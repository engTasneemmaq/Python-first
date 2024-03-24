# Python-first

# if i want to write more than print statment in one line, i can use semicolon 
# print ("hello python"); print ("i love programming") 

# ------------------------------------------------------------------------
# Comments
# single line comment (ctrl + ? on keyboard)

#  multi lines comment 
# ------------
#
#
#
# ------------

# ------------------------------------------------------------------------

# datatype >>>
# --------------------
# type() built in function
# All data in python is object
# --------------------

# print(type(10)) # int => Integer
# print(type(100)) # int => Integer
# print(type(-10)) # int => Integer

# print(type(100.9)) # float => Floaing point number
# print(type(1.00975567)) # float => Floaing point number
# print(type(-100.9)) # float => Floaing point number

# print(type("Hello Pytho")) # str => String

# print(type([1, 2, 3, 4])) # list => List

# print(type( (1, 2, 3, 4) )) # tuple =>  Tuple

# print(type({"one":1,"Two":2, "Three":3})) # dict => Dictionary

# print(type(2 ==4)) #bool => Boolean

# ------------------------------------------------------------------------
# Variables
# -----------
# Syntax => [Variable Name] [Assignment Operator] [Value]
# 
# Name Convention and Rules
# [1] can start with (a-z A-Z) or Underscore
# [2] can't start with numbers or special characters
# [3] can include (0-9) or underscore
# [4] can't include special char
# [5] Name is not like name [case sevsitive]
# -----------


# myVar = "My Value"
# print(myVar)

# name ="Tasneem Ali" # Single word => Normal
# myName = "Tasneem Ali" # Two words => camelCase
# my_name = "Tasneem Ali" # Two words => snake_case


# ------------------------------------------------------------------------
# Source code: original code you write it in computer
# Translation: conerting source code into machine lang
# Compilation: translate code before run time
# Run-Time: period app to executing commands
# Interpreted: code translated on the fly during execution
# ------------------------------------------------------------------------

# no error (نوع البيانات تخزن بالبدايه ك رقم  Python dynamiclly typed language  بقدر اغير نوع البيانات )
# x= 10
# x= "hello"

# print(x)

# help("keywords") # to display all reserved words

# To assign 
# a, b, c = 1,2,3
# print(a)
# print(b)
# print(c)
# print(a,b,c)

# ------------------------------------------------------------------------
# Escape Sequences Char
# \b => back space
# \newline => Escape new line + \
# \ => Escape back slash
# \' => Escape single quotes
# \" => Escape double quotes
# \n => Line feed char
# /r => Carriage return
# \t => Horizantal Tap
# \xhh => char Hex Value


# Back space
# print("Hello\bworld") #remove char o

# Escape new line + \
# print("Hello \
#       i love \
#       python")

# Escape back slash
# print("I love Pyhton \\")

# Escape single quote
# print('I love Pyhton \'Test\' ')

# Escape double quote
# print("I love Pyhton \"Test\" ")

# Line feed
# print("Hello world\nsecond line")

# Carriage return
# print("123456\rAbcd")

# Horizantal Tap
# print("Hello\tPython")

# char Hex Value
# print("\x4f") # char o


# ------------------------------------------------------------------------
# Concatenation : connect two string


# msg = "I Love"
# lang = "Python"
# print(msg + lang)
# or use " " to space between them
# print(msg + " " + lang)

# ------------------------------------------------------------------------
#  Strings



# myStringOne = 'I Love Single Quote'
# myStringTwo = "I Love Double Quote"
# myStringThree = "I Love Double Quote 'Tasneem' "  # single quote
# myStringFour = 'I Love Single Quote "Tasneem" '   # double quote



# print(myStringOne)
# print(myStringTwo)
# print(myStringThree)
# print(myStringFour)

# multi lines """ or '''
# myStringFive = """First
# Second
# Third"""

# myStringSix = """First
# Second 'Test' "Test"
# Third"""

# myStringSeven = """First
# Second "Test" 'Test'
# Third"""

# print(myStringFive)
# print(myStringSix)
# print(myStringSeven)


# ------------------------------------------------------------------------
# ----------------------------
# Strings Indexing & Slicing
# [1] All data in python is object
# [2] Object contain elements
# [3] Every elements has its own index
# [4] Python use zero based indexing (index start from zero)
# [5] Use square brackets to access element
# [6] Enable accessing parts of Strings, Tuple or Lists 
# ----------------------------

# Indexing (Access single item)

# myString = "I Love Python"
# print(myString[0]) # Index 0 => I
# print(myString[1]) # Index 1 => ""
# print(myString[9]) # Index 9 => t

# negative value from end to start
# print(myString[-1]) # Index -1 => n
# print(myString[-6]) # Index -6 => p

# Slicing (Access multiple sequence items)
# Syntax: [Start:End] end not included
# [Start:End:Steps]

# print(myString[8:11]) #yth
# print(myString[2:7]) #love

# if start is not here will start from zero
# print(myString[:10]) #I Love pyt

# if end is not here will go to the end
# print(myString[10:]) #hon


# print(myString[:]) #print full Strings

#  Steps 
# print(myString[0::1]) # Full data
# print(myString[::1]) # Full data
# print(myString[::2]) # ILov yhn
# print(myString[::3]) # Io tn


# ------------------------------------------------------------------------
# String Methods

# len() number of items
# a = "I Love Python"
# b = "    I Love Python     "

# print(len(a)) #number of items 13
# print(len(b)) #number of items 22

# -----------------------
# [1] Strip
# strip() => remove spaces from left and right
# rstrip() => remove spaces from right
# lstrip() => remove spaces from left

# x = "    I Love Python    "
# print(x.strip())
# print(x.rstrip())
# print(x.lstrip())

# x = "####I Love Python####"
# print(x.strip("#"))
# print(x.rstrip())
# print(x.lstrip("#"))

# x = "#@#@#@I Love Python#@#@#@"
# print(x.strip("#@"))
# print(x.rstrip())
# print(x.lstrip("#@"))

# [2] Title  title() first char  capital letter, replace characters after numbers capital letter 

# s = "i Love 2d Graphics 3g Technology and python"
# print(s.title())

# [3] Capitalize  letters after numbers not change, just first char capital
# s = "i Love 2d Graphics 3g Technology and python"
# print(s.capitalize())

# [4] zfill() 001 001 002 

# c, d, e = '1', '11', '111'
# print(c)
# print(d)
# print(e)

# print(c.zfill(3))
# print(d.zfill(3))
# print(e.zfill(3))

# [5] upper() small letter to capital letter

# t = "tasneem"
# print(t.upper())

# [5] lower() small letter to capital letter

# t = "TASNEEM" capital letter to small letter
# print(t.lower())

# [6] split() return a list of substrings in the string

# m = "I Love Python"
# print(m.split())
# print(type(m.split()))

# n = "I-Love-Python"
# print(n.split())
# print(n.split("-"))

# u = "I-Love-Python-and-Javascript"
# print(u.split("-",2))

# split from right
# k = "I-Love-Python-and-Javascript"
# print(k.rsplit("-",3))

# [7] center() return number of letter

# y = "Tasneem"
# print(y.center(9)) #spaces
# print(y.center(9, "#")) #hashes
# print(y.center(15,"@")) # @


# [8] count() 
# f = "I Love Python and php because php is easy"
# print(f.count("php")) # 2 php words
# print(f.count("php", 0, 25)) #only one php

# [9] swapcase()

# f = "I Love Python"
# h = "i LOVE pYTHON"

# print(f.swapcase())
# print(h.swapcase())

# [10] startswith()

# i = "I Love Python"
# print(i.startswith("I"))
# print(i.startswith("s"))
# print(i.startswith("P", 7, 12))

# [10] endswith()

# i = "I Love Python"
# print(i.endswith("n"))
# print(i.endswith("N"))
# print(i.endswith("e", 2, 6))

# [11] index(substring, Start, End)

# a = "I Love Python"
# print(a.index("P")) # index number 7
# print(a.index("P", 0, 10)) # index number 7
# print(a.index("P", 0, 5)) # substring not found

#  [12] find(substring, Start, End)

# a = "I Love Python"
# print(a.find("P")) # index number 7
# print(a.find("P", 0, 10)) # index number 7
# print(a.find("P", 0, 5)) # if not found letter  -1

# [13] rjust(width, fill char) ljust(width, fill char)

# c = "Tasneem"
# print(c.rjust(10))
# print(c.rjust(10, "#"))

# d = "Tasneem"
# print(c.ljust(10))
# print(c.ljust(10, "#"))

# [14] splitlines()

# e = """First Line
# Second Line
# Third Line"""

# print(e.splitlines()) # return list

# f = "First Line\nSecond Line\nThird Line"

# print(f.splitlines()) # return same list

# [15] expandtabs()

# g = "Hello\tWorld\tI\tLove\tPython"
# print(g.expandtabs(20))

# [16] istitle()
# one = "I Love Python And 3G"
# two = "I Love Python And 3g"
# print(one.istitle())
# print(two.istitle())

# [17] isspace()
# one = " "
# print(one.isspace())

# [18] islower()

# one = "i love python"
# two = "I lOVE python"
# print(one.islower())
# print(two.islower())

# [19] isidentifier()

# one = "tasneem_ali"
# two = "tasneemAli"
# three = "tasneem--ali"
# print(one.isidentifier())
# print(two.isidentifier())
# print(three.isidentifier())

# [20] isalpha()
# x = "AaaaaaBbbbb"
# y = "AaaaaaBbbbb111"
# print(x.isalpha())
# print(y.isalpha())

# [20] isalnum()
# x = "AaaaaaBbbbb"
# y = "AaaaaaBbbbb111"
# print(x.isalnum())
# print(y.isalnum())

# [21] replace(old value, new value, count)

# a = "Hello One Two Three One One"
# print(a.replace("One", "1"))
# print(a.replace("One", "1", 1))

# [22] join(Iterable)
# myList = ["Tasneem", "Ali", "Maqableh"]
# print("-".join(myList))
# print(" ".join(myList))
# print(type("-".join(myList)))



# --------------------------------------------------------------------------
#  String Formating/ old way

# name = "Tasneem"
# age = 34
# rank = 10

# print("My Name is: " + name + "My Age is: " + age) # type error

# print("My Name Is: %s" % "Tasneem")
# print("My Name Is: %s" % name)
# print("My Name Is: %s and My Age is: %d" % (name, age))
# print("My Name Is: %s and My Age is: %d and My Rank is: %f" % (name, age, rank))

# %s => String
# %d => Number
# %f => Float

# ---------------------------------
# -- Strings Formatting New Ways --
# ---------------------------------

# name = "Tasneem"
# age = 34
# rank = 10

# print("My Name is: " + name)
# print("My Name is: " + name + " and My Age is: " + age)  # Type Error

# print("My Name is: {}".format("Tasneem"))
# print("My Name is: {}".format(name))
# print("My Name is: {} My Age: {}".format(name, age))
# print("My Name is: {:s} Age: {:d} & Rank is: {:f}".format(name, age, rank))

# {:s} => String
# {:d} => Number
# {:f} => Float

# n = "Tasneem"
# l = "Python"
# y = 10

# print("My Name is {} Iam {} Developer With {:d} Years Exp".format(n, l, y))

# Control Floating Point Number

# myNumber = 10
# print("My Number is: {:d}".format(myNumber))
# print("My Number is: {:f}".format(myNumber))
# print("My Number is: {:.2f}".format(myNumber))

# Truncate String

# myLongString = "Hello Peoples of Elzero Web School I Love You All"
# print("Message is {}".format(myLongString))
# print("Message is {:.5s}".format(myLongString))
# print("Message is {:.13s}".format(myLongString))

# Format Money

# myMoney = 500162350198

# print("My Money in Bank Is: {:d}".format(myMoney))
# print("My Money in Bank Is: {:_d}".format(myMoney))
# print("My Money in Bank Is: {:,d}".format(myMoney))

# # ReArrange Items

# a, b, c = "One", "Two", "Three"
# print("Hello {} {} {}".format(a, b, c))  # Hello One Two Three
# print("Hello {1} {2} {0}".format(a, b, c))  # Hello Two Three One
# print("Hello {2} {0} {1}".format(a, b, c))  # Hello Three One Two

# x, y, z = 10, 20, 30
# print("Hello {} {} {}".format(x, y, z))
# print("Hello {1:d} {2:d} {0:d}".format(x, y, z))
# print("Hello {2:f} {0:f} {1:f}".format(x, y, z))
# print("Hello {2:.2f} {0:.4f} {1:.5f}".format(x, y, z))

# Format in Version 3.6+

# myName = "Tasneem"
# myAge = 36

# print("My Name is : {myName} and My Age is : {myAge}")
# print(f"My Name is : {myName} and My Age is : {myAge}")

# -----------------------------------------------------------------------------------
# -------------
# -- Numbers --
# -------------

# Integer

# print(type(1))
# print(type(100))
# print(type(10))
# print(type(-10))
# print(type(-110))

# # Float

# print(type(1.500))
# print(type(100.99))
# print(type(-10.99))
# print(type(0.99))
# print(type(-0.99))

# # Complex

# myComplexNumber = 5+6j

# print(type(myComplexNumber))

# print("Real Part Is: {}".format(myComplexNumber.real))
# print("Imaginary Part Is: {}".format(myComplexNumber.imag))

# [1] You Can Convert From Int To Float or Complex
# [2] You Can Convert From Float To Int or Complex
# [3] You Cannot Convert Complex To Any Type

# print(100)
# print(float(100))
# print(complex(100))

# print(10.50)
# print(int(10.50))
# print(complex(10.50))

# print(10+9j)
# print(int(10+9j))

# ----------------------------------------------------------------------------
# --------------------------
# -- Arithmetic Operators --
# --------------------------
# [+] Addition
# [-] Subtraction
# [*] Multiplication
# [/] Division
# [%] Modulus
# [**] Exponent
# [//] Floor Division
# --------------------------

# Addition

# print(10 + 30)  # 40
# print(-10 + 20)  # 10
# print(1 + 2.66)  # 3.66
# print(1.2 + 1.2)  # 2.4

# Subtraction

# print(60 - 30)  # 30
# print(-30 - 20)  # -50
# print(-30 - -20)  # -10
# print(5.66 - 3.44)  # 2.22

# Multiplication

# print(10 * 3)  # 30
# print(5 + 10 * 100)  # 1005
# print((5 + 10) * 100)  # 1500

# Division

# print(100 / 20)  # 5.0
# print(int(100 / 20))  # 5

# Modulus

# print(8 % 2)  # 0
# print(9 % 2)  # 1
# print(20 % 5)  # 0
# print(22 % 5)  # 2

# Exponent

# print(2 ** 5)  # 32
# print(2 * 2 * 2 * 2 * 2)  # 32
# print(5 ** 4)  # 625
# print(5 * 5 * 5 * 5)  # 625

# Floor Division

# print(100 // 20)  # 5
# print(119 // 20)  # 5
# print(120 // 20)  # 6
# print(140 // 20)  # 7
# print(142 // 20)  # 7


# ----------------------------------------------------------------------------------
# -----------------------------
# -- Lists --
# -----------
# [1] List Items Are Enclosed in Square Brackets
# [2] List Are Ordered, To Use Index To Access Item
# [3] List Are Mutable => Add, Delete, Edit
# [4] List Items Is Not Unique
# [5] List Can Have Different Data Types
# -----------------------------

# myAwesomeList = ["One", "Two", "One", 1, 100.5, True]

# print(myAwesomeList)  # Whole List
# print(myAwesomeList[1])  # "Two"
# print(myAwesomeList[-1])  # True
# print(myAwesomeList[-3])  # 1

# print(myAwesomeList[1:4])  # ['Two', 'One', 1]
# print(myAwesomeList[:4])  # ['One', 'Two', 'One', 1]
# print(myAwesomeList[1:])  # ['Two', 'One', 1, 100.5, True]

# print(myAwesomeList[::1])  # ['One', 'Two', 'One', 1, 100.5, True]
# print(myAwesomeList[::2])  # ['One', 'One', 100.5]

# print(myAwesomeList)
# # myAwesomeList[1] = 2
# # myAwesomeList[-1] = False
# myAwesomeList[0:3] = ["A"]
# print(myAwesomeList)


# -------------------
# -- Lists Methods --
# -------------------

# append()

# myFriends = ["Osama", "Ahmed", "Sayed"]
# myOldFriends = ["Haytham", "Samah", "Ali"]

# myFriends.append("Alaa")
# myFriends.append(100)
# myFriends.append(150.200)
# myFriends.append(True)
# myFriends.append(myOldFriends)

# print(myFriends)
# print(myFriends[2])
# print(myFriends[6])
# print(myFriends[7])
# print(myFriends[7][2])

# # extend()

# a = [1, 2, 3, 4]
# b = ["A", "B", "C"]
# c = ["One", "Two"]

# a.extend(b)
# a.extend(c)

# print(a)

# # remove()

# x = [1, 2, 3, 4, 5, "Osama", True, "Osama", "Osama"]
# x.remove("Osama")
# print(x)

# # sort()

# y = [1, 2, 100, 120, -10, 17, 29]
# # y = ["A", "Z", "C"]
# y.sort(reverse=True)
# print(y)

# # reverse()

# z = [10, 1, 9, 80, 100, "Osama", 100]
# z.reverse()
# print(z)


# -------------------
# -- Lists Methods --
# -------------------

# clear()

# a = [1, 2, 3, 4]
# a.clear()
# print(a)

# # copy()

# b = [1, 2, 3, 4]
# c = b.copy()

# print(b)  # Main List
# print(c)  # Copied List

# b.append(5)

# print(b)  # Main List
# print(c)  # Copied List

# # count()

# d = [1, 2, 3, 4, 3, 9, 10, 1, 2, 1]
# print(d.count(1))

# # index()

# e = ["Osama", "Ahmed", "Sayed", "Ramy", "Ahmed", "Ramy"]
# print(e.index("Ramy"))

# # insert()

# f = [1, 2, 3, 4, 5, "A", "B"]
# f.insert(0, "Test")
# f.insert(-1, "Test")

# print(f)

# # pop()

# g = [1, 2, 3, 4, 5, "A", "B"]
# print(g.pop(-3))


# -----------------------------
# -- Tuple --
# -----------
# [1] Tuple Items Are Enclosed in Parentheses
# [2] You Can Remove The Parentheses If You Want
# [3] Tuple Are Ordered, To Use Index To Access Item
# [4] Tuple Are Immutable => You Cant Add or Delete
# [5] Tuple Items Is Not Unique
# [6] Tuple Can Have Different Data Types
# [7] Operators Used in Strings and Lists Available In Tuples
# -----------------------------

# Tuple Syntax & Type Test

# myAwesomeTupleOne = ("Osama", "Ahmed")
# myAwesomeTupleTwo = "Osama", "Ahmed"

# print(myAwesomeTupleOne)
# print(myAwesomeTupleTwo)

# print(type(myAwesomeTupleOne))
# print(type(myAwesomeTupleTwo))

# # Tuple Indexing

# myAwesomeTupleThree = (1, 2, 3, 4, 5)
# print(myAwesomeTupleThree[0])
# print(myAwesomeTupleThree[-1])
# print(myAwesomeTupleThree[-3])

# # Tuple Assign Values

# myAwesomeTupleFour = (1, 2, 3, 4, 5)
# # myAwesomeTupleFour[2] = "Three"
# # print(myAwesomeTupleFour)  # 'tuple' object does not support item assignment

# # Tuple Data

# myAwesomeTupleFive = ("Osama", "Osama", 1, 2, 3, 100.5, True)
# print(myAwesomeTupleFive[1])
# print(myAwesomeTupleFive[-1])

# -----------
# -- Tuple --
# -----------

# Tuple With One Element

# myTuple1 = ("Osama",)
# myTuple2 = "Osama",

# print(myTuple1)
# print(myTuple2)

# print(type(myTuple1))
# print(type(myTuple2))

# print(len(myTuple1))
# print(len(myTuple2))

# # Tuple Concatenation

# a = (1, 2, 3, 4)
# b = (5, 6)

# c = a + b
# d = a + ("A", "B", True) + b

# print(c)
# print(d)

# # Tuple, List, String Repeat (*)

# myString = "Osama"
# myList = [1, 2]
# myTuple = ("A", "B")

# print(myString * 6)
# print(myList * 6)
# print(myTuple * 6)

# # Methods => count()

# a = (1, 3, 7, 8, 2, 6, 5, 8)
# print(a.count(8))

# # Methods => index()

# b = (1, 3, 7, 8, 2, 6, 5)
# # print("The Position of Index Is: " + b.index(7))  # Error
# print("The Position of Index Is: {:d}".format(b.index(7)))
# print(f"The Position of Index Is: {b.index(7)}")

# # Tuple Destruct

# a = ("A", "B", 4, "C")

# x, y, _, z = a

# print(x)
# print(y)
# print(z)


# -----------------------------
# -- Set --
# ---------
# [1] Set Items Are Enclosed in Curly Braces
# [2] Set Items Are Not Ordered And Not Indexed
# [3] Set Indexing and Slicing Cant Be Done
# [4] Set Has Only Immutable Data Types (Numbers, Strings, Tuples) List and Dict Are Not
# [5] Set Items Is Unique
# -----------------------------

# Not Ordered And Not Indexed

# mySetOne = {"Osama", "Ahmed", 100}
# print(mySetOne)
# # print(mySetOne[0])

# # Slicing Cant Be Done

# mySetTwo = {1, 2, 3, 4, 5, 6}
# # print(mySetTwo[0:3])

# # Has Only Immutable Data Types

# # mySetThree = {"Osama", 100, 100.5, True, [1, 2, 3]} # unhashable type: 'list'
# mySetThree = {"Osama", 100, 100.5, True, (1, 2, 3)}

# print(mySetThree)

# # Items Is Unique

# mySetFour = {1, 2, "Osama", "One", "Osama", 1}
# print(mySetFour)

# -----------------
# -- Set Methods --
# -----------------

# clear()

# a = {1, 2, 3}
# a.clear()
# print(a)

# # union()

# b = {"One", "Two", "Three"}
# c = {"1", "2", "3"}
# x = {"Zero", "Cool"}

# print(b | c)
# print(b.union(c, x))

# # add()

# d = {1, 2, 3, 4}
# d.add(5)
# d.add(6)
# print(d)

# # copy()

# e = {1, 2, 3, 4}
# f = e.copy()

# print(e)
# print(f)

# e.add(6)

# print(e)
# print(f)

# # remove()

# g = {1, 2, 3, 4}
# g.remove(1)
# # g.remove(7)
# print(g)

# # discard()

# h = {1, 2, 3, 4}
# h.discard(1)
# h.discard(7)
# print(h)

# # pop()

# i = {"A", True, 1, 2, 3, 4, 5}
# print(i.pop())

# # update()

# j = {1, 2, 3}
# k = {1, "A", "B", 2}
# j.update(['Html', "Css"])
# j.update(k)

# print(j)

# -----------------
# -- Set Methods --
# -----------------

# difference()

a = {1, 2, 3, 4}
b = {1, 2, 3, "Osama", "Ahmed"}
print(a)
print(a.difference(b))  # a - b
print(a)

print("=" * 40)  # Separator

# difference_update()

c = {1, 2, 3, 4}
d = {1, 2, "Osama", "Ahmed"}
print(c)
c.difference_update(d)  # c - d
print(c)

print("=" * 40)  # Separator

# intersection()

e = {1, 2, 3, 4, "X", "Osama"}
f = {"Osama", "X", 2}
print(e)
print(e.intersection(f))  # e & f
print(e)

print("=" * 40)  # Separator

# intersection_update()

g = {1, 2, 3, 4, "X", "Osama"}
h = {"Osama", "X", 2}
print(g)
g.intersection_update(h)  # g & h
print(g)

print("=" * 40)  # Separator

# symmetric_difference()

i = {1, 2, 3, 4, 5, "X"}
j = {"Osama", "Zero", 1, 2, 4, "X"}
print(i)
print(i.symmetric_difference(j))  # i ^ j
print(i)

print("=" * 40)  # Separator

# symmetric_difference_update()

k = {1, 2, 3, 4, 5, "X"}
l = {"Osama", "Zero", 1, 2, 4, "X"}
print(k)
k.symmetric_difference_update(l)  # k ^ l
print(k)

# -----------------
# -- Set Methods --
# -----------------

# issuperset()

a = {1, 2, 3, 4}
b = {1, 2, 3}
c = {1, 2, 3, 4, 5}

print(a.issuperset(b))  # True
print(a.issuperset(c))  # False

print("=" * 50)

# issubset()

d = {1, 2, 3, 4}
e = {1, 2, 3}
f = {1, 2, 3, 4, 5}

print(d.issubset(e))  # False
print(d.issubset(f))  # True

print("=" * 50)

# isdisjoint()

g = {1, 2, 3, 4}
h = {1, 2, 3}
i = {10, 11, 12}

print(g.isdisjoint(h))  # False
print(g.isdisjoint(i))  # True

# ---------------------------
# -- Dictionary --
# ----------------
# [1] Dict Items Are Enclosed in Curly Braces
# [2] Dict Items Are Contains Key : Value
# [3] Dict Key Need To Be Immutable => (Number, String, Tuple) List Not Allowed
# [4] Dict Value Can Have Any Data Types
# [5] Dict Key Need To Be Unique
# [6] Dict Is Not Ordered You Access Its Element With Key
# ----------------------------

# Dictionary

user = {
  "name": "Osama",
  "age": 36,
  "country": "Egypt",
  "skills": ["Html", "Css", "JS"],
  "rating": 10.5
}

print(user)
print(user['country'])
print(user.get("country"))

print(user.keys())
print(user.values())

# Two-Dimensional Dictionary

languages = {
  "One": {
    "name": "Html",
    "progress": "80%"
  },
  "Two": {
    "name": "Css",
    "progress": "90%"
  },
  "Three": {
    "name": "Js",
    "progress": "90%"
  }
}

print(languages)
print(languages['One'])
print(languages['Three']['name'])

# Dictionary Length

print(len(languages))
print(len(languages["Two"]))

# Create Dictionary From Variables

frameworkOne = {
  "name": "Vuejs",
  "progress": "80%"
}

frameworkTwo = {
  "name": "ReactJs",
  "progress": "80%"
}

frameworkThree = {
  "name": "Angular",
  "progress": "80%"
}

allFramework = {
  "one": frameworkOne,
  "two": frameworkTwo,
  "three": frameworkThree
}

print(allFramework)

# ------------------------
# -- Dictionary Methods --
# ------------------------

# clear()

user = {
  "name": "Osama"
}
print(user)
user.clear()
print(user)

print("=" * 50)

# update()

member = {
  "name": "Osama"
}
print(member)
member["age"] = 36
print(member)
member.update({"country": "Egypt"})
print(member)

print("=" * 50)

# copy()

main = {
  "name": "Osama"
}

b = main.copy()
print(b)
main.update({"skills": "Fighting"})
print(main)
print(b)

# keys() + values()

print(main.keys())
print(main.values())

# ------------------------
# -- Dictionary Methods --
# ------------------------

# setdefault()

user = {
  "name": "Osama"
}
print(user)
print(user.setdefault("age", 36))
print(user)

print("=" * 40)

# popitem()

member = {
  "name": "Osama",
  "skill": "PS4"
}
print(member)
member.update({"age": 36})
print(member.popitem())

print("=" * 40)

# items()

view = {
  "name": "Osama",
  "skill": "XBox"
}

allItems = view.items()
print(view)
view["age"] = 36

print(allItems)

print("=" * 40)

# fromkeys()

a = ('MyKeyOne', 'MyKeyTwo', 'MyKeyThree')
b = "X"

print(dict.fromkeys(a, b))

# -------------
# -- Boolean --
# -------------
# [1] In Programming You Need to Known Your If Your Code Output is True Or False
# [2] Boolean Values Are The Two Constant Objects False + True.
# ---------------------------------------------------------------

name = " "
print(name.isspace())

print("=" * 50)

print(100 > 200)
print(100 > 100)
print(100 > 90)

print("=" * 50)

# True Values

print(bool("Osama"))
print(bool(100))
print(bool(100.95))
print(bool(True))
print(bool([1, 2, 3, 4, 5]))

print("=" * 50)

# False Values

print(bool(0))
print(bool(""))
print(bool(''))
print(bool([]))
print(bool(False))
print(bool(()))
print(bool({}))
print(bool(None))

# -----------------------
# -- Boolean Operators --
# -----------------------
# and
# or
# not
# -----------------------

age = 36
country = "Egypt"
rank = 10

print(age > 16 and country == "Egypt" and rank > 0)  # True
print(age > 16 and country == "KSA" and rank > 0)  # False

print(age > 40 or country == "KSA" or rank > 20)  # False
print(age > 40 or country == "Egypt" or rank > 20)  # True

print(age > 16)  # True
print(not age > 16)  # Not True = False

# --------------------------
# -- Assignment Operators --
# --------------------------
# =
# +=
# -=
# *=
# /=
# **=
# %=
# //=
# --------------------------

x = 10  # Var One
y = 20  # Var Two

# Var One = Self [Operator] Var Two
# Var One [Operator]= Var Two

# x += y
x -= y

print(x)

# --------------------------
# -- Comparison Operators --
# --------------------------
# [ == ] Equal
# [ != ] Not Equal
# [ > ] Greater Than
# [ < ] Less Than
# [ >= ] Greater Than Or Equal
# [ <= ] Less Than Or Equal
# --------------------------

# Equal + Not Equal

print(100 == 100)
print(100 == 200)
print(100 == 100.00)

print("#" * 50)

print(100 != 100)
print(100 != 200)
print(100 != 100.00)

print("#" * 50)

# Greater Than + Less Than

print(100 > 100)
print(100 > 200)
print(100 > 100.00)
print(100 > 40)

print("#" * 50)

print(100 < 100)
print(100 < 200)
print(100 < 100.00)
print(100 < 40)

print("#" * 50)

# Greater Than Or Equal + Less Than Or Equal

print(100 >= 100)
print(100 >= 200)
print(100 >= 100.00)
print(100 >= 40)

print("#" * 50)

print(100 <= 100)
print(100 <= 200)
print(100 <= 100.00)
print(100 <= 40)

print("#" * 50)

# ---------------------
# -- Type Conversion --
# ----------------------

# str()

a = 10
print(type(a))
print(type(str(a)))

print("#" * 50)

# tuple()

c = "Osama"  # String
d = [1, 2, 3, 4, 5]  # List
e = {"A", "B", "C"}  # Set
f = {"A": 1, "B": 2}  # Dictionary

print(tuple(c))
print(tuple(d))
print(tuple(e))
print(tuple(f))

# list()

c = "Osama"  # String
d = (1, 2, 3, 4, 5)  # Tuple
e = {"A", "B", "C"}  # Set
f = {"A": 1, "B": 2}  # Dictionary

print(list(c))
print(list(d))
print(list(e))
print(list(f))

print("#" * 50)

# set()

c = "Osama"  # String
d = (1, 2, 3, 4, 5)  # Tuple
e = ["A", "B", "C"]  # List
f = {"A": 1, "B": 2}  # Dictionary

print(set(c))
print(set(d))
print(set(e))
print(set(f))

print("#" * 50)

# dict()

d = (("A", 1), ("B", 2), ("C", 3))  # Tuple
e = [["One", 1], ["Two", 2], ["Three", 3]]  # List

print(dict(d))
print(dict(e))

# ----------------
# -- User Input --
# ----------------

fName = input('What\'s Is Your First Name?')
mName = input('What\'s Is Your Middle Name?')
lName = input('What\'s Is Your Last Name?')

fName = fName.strip().capitalize()
mName = mName.strip().capitalize()
lName = lName.strip().capitalize()

print(f"Hello {fName} {mName:.1s} {lName} Happy To See You.")

# ---------------------------
# -- Practical Slice Email --
# ---------------------------

theName = input('What\'s Your Name ?').strip().capitalize()
theEmail = input('What\'s Your Email ?').strip()

theUsername = theEmail[:theEmail.index("@")]
theWebsite = theEmail[theEmail.index("@") + 1:]

print(f"Hello {theName} Your Email Is {theEmail}")
print(f"Your Username Is {theUsername} \nYour Website Is {theWebsite}")

# email = "Osama@elzero.org"
# print(email[:email.index("@")])

# -------------------------------------
# -- Practical Your Age Full Details --
# -------------------------------------

# Input Age
age = int(input('What\'s Your Age ? ').strip())

# Get Age in All Time Units
months = age * 12
weeks = months * 4
days = age * 365
hours = days * 24
minutes = hours * 60
seconds = minutes * 60

print('You Lived For:')
print(f"{months} Months.")
print(f"{weeks:,} Weeks.")
print(f"{days:,} Days.")
print(f"{hours:,} Hours.")
print(f"{minutes:,} Minutes.")
print(f"{seconds:,} Seconds.")

# --------------------
# --  Control Flow  --
# -- If, Elif, Else --
# -- Make Decisions --
# --------------------

uName = "Osama"
uCountry = "Kuwait"
cName = "Python Course"
cPrice = 100

if uCountry == "Egypt":

  print(f"Hello {uName} Because You Are From {uCountry}")
  print(f"The Course \"{cName}\" Price Is: ${cPrice - 80}")

elif uCountry == "KSA":

  print(f"Hello {uName} Because You Are From {uCountry}")
  print(f"The Course \"{cName}\" Price Is: ${cPrice - 60}")

elif uCountry == "Kuwait":

  print(f"Hello {uName} Because You Are From {uCountry}")
  print(f"The Course \"{cName}\" Price Is: ${cPrice - 50}")

else:

  print(f"Hello {uName} Because You Are From {uCountry}")
  print(f"The Course \"{cName}\" Price Is: ${cPrice - 30}")

  # ---------------
# -- Nested If --
# ---------------

uName = "Osama"
isStudent = "Yes"
uCountry = "Egypt"
cName = "Python Course"
cPrice = 100

if uCountry == "Egypt" or uCountry == "KSA" or uCountry == "Qatar":

  if isStudent == "Yes":

    print(f"Hi {uName} Because U R From {uCountry} And Student")
    print(f"The Course \"{cName}\" Price Is: ${cPrice - 90}")

  else:

    print(f"Hi {uName} Because U R From {uCountry}")
    print(f"The Course \"{cName}\" Price Is: ${cPrice - 80}")


elif uCountry == "Kuwait" or uCountry == "Bahrain":

  print(f"Hi {uName} Because U R From {uCountry}")
  print(f"The Course \"{cName}\" Price Is: ${cPrice - 50}")

else:

  print(f"Hi {uName} Because U R From {uCountry}")
  print(f"The Course \"{cName}\" Price Is: ${cPrice - 30}")

  # ----------------------------------
# -- Ternary Conditional Operator --
# ----------------------------------

country = "A"

if country == "Egypt" : print(f"The Weather in {country} Is 15")
elif country == "KSA" : print(f"The Weather in {country} Is 30")
else : print("Country is Not in The List")

# Short If

movieRate = 18
age = 18

if age < movieRate :

  print("Movie S Not Good 4U") # Condition If True

else :

  print("Movie S Good 4U And Happy Watching") # Condition If False

print("Movie S Not Good 4U" if age < movieRate else "Movie S Good 4U And Happy Watching")

# Condition If True | If Condition | Else | Condition If False

# -------------------------------------------------
# -- Calculate Age Advanced Version and Training --
# -------------------------------------------------

# Write A Very Beautiful Note
print("#" * 80)
print(" You Can Write The First Letter Or Full Name of The Time Unit ".center(80, '#'))
print("#" * 80)

# Collect Age Data
age = input("Please Write Your Age").strip()

# Collect Time Unit Data
unit = input("Please Choose Time Unit: Months, Weeks, Days ").strip().lower()

# Get Time Units
months = int(age) * 12
weeks = months * 4
days = int(age) * 365

if unit == 'months' or unit == 'm':

  print("You Choosed The Unit Months")
  print(f"You Lived For {months:,} Months.")

elif unit == 'weeks' or unit == 'w':

  print("You Choosed The Unit Weeks")
  print(f"You Lived For {weeks:,} Weeks.")

elif unit == 'days' or unit == 'd':

  print("You Choosed The Unit Days")
  print(f"You Lived For {days:,} Days.")

  # --------------------------
# -- Membership Operators --
# --------------------------
# in
# not in
# --------------------------

# String

name = "Osama"
print("s" in name)
print("a" in name)
print("A" in name)

print("#" * 50)

# List

friends = ["Ahmed", "Sayed", "Mahmoud"]
print("Osama" in friends)
print("Sayed" in friends)
print("Mahmoud" not in friends)

print("#" * 50)

# Using In and Not In With Condition

countriesOne = ["Egypt", "KSA", "Kuwait", "Bahrain", "Syria"]
countriesOneDiscount = 80

countriesTwo = ["Italy", "USA"]
countriesTwoDiscount = 50

myCountry = "Italy"

if myCountry in countriesOne:

  print(f"Hello You Have A Discount Equal To ${countriesOneDiscount}")

elif myCountry in countriesTwo:

  print(f"Hello You Have A Discount Equal To ${countriesTwoDiscount}")

else:

  print("You Have No Discount")


  # ----------------------------------
# -- Practical Membership Control --
# ----------------------------------

# List Contains Admins
admins = ["Ahmed", "Osama", "Sameh", "Manal", "Rahma", "Mahmoud", "Enas"]

# Login
name = input("Please Type Your Name ").strip().capitalize()

# If Name is In Admin
if name in admins:

  print(f"Hello {name} Welcome Back")

  option = input("Delete Or Update Your Name ?").strip().capitalize()

  # Update Option
  if option == 'Update' or option == 'U':

    theNewName = input("Your New Name Please ").strip().capitalize()

    admins[admins.index(name)] = theNewName

    print("Name Updated.")

    print(admins)

  # Delete Option
  elif option == 'Delete' or option == 'D':

    admins.remove(name)

    print("Name Deleted")

    print(admins)

  # Wrong Option
  else:

    print("Wrong Option Choosed")

else:

  status = input("Not Admin, Add You Y, N ? ").strip().capitalize()

  if status == "Yes" or status == "Y":

    print("You Have Been Added")

    admins.append(name)

    print(admins)

  else:

    print("You Are Not Added.")

    # -------------------
# -- Loop => While --
# -------------------
# while condition_is_true
#   Code Will Run Until Condition Become False
# -----------------------

a = 0

while a < 15:

  print(a)

  a += 1  # a = a + 1

print("Loop is Done")  # True Become False

while False:

  print("Will Not Print")

  # ----------------------------
# -- Loop => While Training --
# ----------------------------
# while condition_is_true
#   Code Will Run Until Condition Become False
# -----------------------

myF = ["Os", "Ah", "Ga", "Al", "Ra", "Sa", "Ta", "Ma", "Mo", "Wa"]

# print(len(myF))  # List Length [10]

a = 0

while a < len(myF):  # a < 10

  print(f"#{str(a + 1).zfill(3)} {myF[a]}")

  a += 1  # a = a + 1

else:

  print("All Friends Printed To Screen.")

# print(myF[0])
# print(myF[1])
# print(myF[2])
# print(myF[3])
# print(myF[4])
# print(myF[5])
# print(myF[6])
# print(myF[7])
# print(myF[8])
# print(myF[9])
  
  # ----------------------------
# -- Loop => While Training --
# -- Simple Bookmark Manage --
# ----------------------------

# Empty List To Fill Later
myFavouriteWebs = []

# Maximum Allowed Websites
maximumWebs = 5

while maximumWebs > 0:

  # Input The New Website
  web = input("Website Name Without https:// ")

  # Add The New Website To The List
  myFavouriteWebs.append(f"https://{web.strip().lower()}")

  # Decrease One Number From Allowed Websites
  maximumWebs -= 1  # maximumWebs = maximumWebs - 1

  # Print The Add Message
  print(f"Website Added, {maximumWebs} Places Left")

  # Print The List
  print(myFavouriteWebs)

else:

  print("Bookmark Is Full, You Cant Add More")

# Check If List Is Not Empty
if len(myFavouriteWebs) > 0:

  # Sort The List
  myFavouriteWebs.sort()

  index = 0

  print("Printing The List Of Websites in Your Bookmark")

  while index < len(myFavouriteWebs):

    print(myFavouriteWebs[index])

    index += 1  # index = index + 1

    # ----------------------------
# -- Loop => While Training --
# -- Simple Bookmark Manage --
# ----------------------------

# Empty List To Fill Later
myFavouriteWebs = []

# Maximum Allowed Websites
maximumWebs = 5

while maximumWebs > 0:

  # Input The New Website
  web = input("Website Name Without https:// ")

  # Add The New Website To The List
  myFavouriteWebs.append(f"https://{web.strip().lower()}")

  # Decrease One Number From Allowed Websites
  maximumWebs -= 1  # maximumWebs = maximumWebs - 1

  # Print The Add Message
  print(f"Website Added, {maximumWebs} Places Left")

  # Print The List
  print(myFavouriteWebs)

else:

  print("Bookmark Is Full, You Cant Add More")

# Check If List Is Not Empty
if len(myFavouriteWebs) > 0:

  # Sort The List
  myFavouriteWebs.sort()

  index = 0

  print("Printing The List Of Websites in Your Bookmark")

  while index < len(myFavouriteWebs):

    print(myFavouriteWebs[index])

    index += 1  # index = index + 1

    # ----------------------------
# -- Loop => While Training --
# -- Simple Password Guess --
# ----------------------------

tries = 4

mainPassword = "Osama@123"

inputPassword = input("Write Your Password: ")

while inputPassword != mainPassword:  # True

  tries -= 1  # tries = tries - 1

  print(f"Wrong Password, { 'Last' if tries == 0 else tries } Chance Left")

  inputPassword = input("Write Your Password: ")

  if tries == 0:

    print("All Tries Is Finished.")

    break

    print("Will Not Print")

else:

  print("Correct Password")


  # -----------------
# -- Loop => For --
# -----------------
# for item in iterable_object :
#   Do Something With Item
# -----------------------------
# item Is A Vairable You Create and Call Whenever You Want
# item refer to the current position and will run and visit all items to the end
# iterable_object => Sequence [ list, tuples, set, dict, string of charcaters, etc ... ]
# ---------------------------------------------------------------

myNumbers = [1, 2, 3, 4, 5, 6, 7, 8, 9]

for number in myNumbers:

  # print(number * 17)

  if number % 2 == 0:  # Even

    print(f"The Number {number} Is Even.")

  else:

    print(f"The Number {number} Is Odd.")

else:

  print("The Loop Is Finished")

myName = "Osama"

for letter in myName:

  print(f" [ {letter.upper()} ] ")


  # -----------------
# -- Loop => For --
# --  Trainings  --
# -----------------

# Range

myRange = range(1, 101)

for number in myRange:

  print(number)

# Dictionary

mySkills = {
  "Html": "90%",
  "Css": "60%",
  "PHP": "70%",
  "JS": "80%",
  "Python": "90%",
  "MySQL": "60%"
}

print(mySkills['JS'])
print(mySkills.get("Python"))

for skill in mySkills:

  # print(skill)

  print(f"My Progress in Lang {skill} Is: {mySkills.get(skill)}")

  # -----------------
# -- Loop => For --
# -- Nested Loop --
# -----------------

peoples = ["Osama", "Ahmed", "Sayed", "Ali"]

skills = ['Html', 'Css', 'Js']

for name in peoples:  # Outer Loop

  print(f"{name} Skills Is: ")

  for skill in skills:  # Inner Loop

    print(f"- {skill}")

# Dictionary

peoples = {
  "Osama": {
    "Html": "70%",
    "Css": "80%",
    "Js": "70%"
  },
  "Ahmed": {
    "Html": "90%",
    "Css": "80%",
    "Js": "90%"
  },
  "Sayed": {
    "Html": "70%",
    "Css": "60%",
    "Js": "90%"
  }
}

print(peoples["Osama"])
print(peoples["Ahmed"])
print(peoples["Sayed"])

print(peoples["Osama"]['Css'])
print(peoples["Ahmed"]['Css'])
print(peoples["Sayed"]['Css'])

for name in peoples:

  print(f"Skills and Progress For {name} Is: ")

  for skill in peoples[name]:

    print(f"{skill.upper()} => {peoples[name][skill]}")

    # ---------------------------
# -- Break, Continue, Pass --
# ---------------------------

myNumbers = [1, 2, 3, 5, 7, 10, 13, 14, 15, 19]

# Continue

for number in myNumbers:

  if number == 13:

    continue

  print(number)

print("#" * 50)

# Break

for number in myNumbers:

  if number == 13:

    break

  print(number)

print("#" * 50)

# Pass

for number in myNumbers:

  if number == 13:

    pass

  print(number)

  # ------------------------------
# -- Advanced Dictionary Loop --
# ------------------------------

mySkills = {
  "HTML": "80%",
  "CSS": "90%",
  "JS": "70%",
  "PHP": "80%"
}

print(mySkills.items())

#######################

for skill in mySkills:

  print(f"{skill} => {mySkills[skill]}")

#######################

for skill_key, skill_progress in mySkills.items():

  print(f"{skill_key} => {skill_progress}")

#######################

myUltimateSkills = {
  "HTML": {
    "Main": "80%",
    "Pugjs": "80%"
  },
  "CSS": {
    "Main": "90%",
    "Sass": "70%"
  }
}

for main_key, main_value in myUltimateSkills.items():

  print(f"{main_key} Progress Is: ")

  for child_key, child_value in main_value.items():

    print(f"- {child_key} => {child_value}")

    
