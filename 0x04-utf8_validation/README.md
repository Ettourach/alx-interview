#Interview exemple at ALX using python
#start

For the “0x04. UTF-8 Validation” project, we will need to apply ours knowledge in bitwise operations, understanding of the UTF-8 encoding scheme, and Python programming skills to validate whether a given dataset represents a valid UTF-8 encoding. Here’s a list of concepts and resources that will be helpful:

#Concepts Needed:

1.Bitwise Operations in Python:
Understanding how to manipulate bits in Python, including operations like AND (&), OR (|), XOR (^), NOT (~), shifts (<<, >>).
Python Bitwise Operators

2.UTF-8 Encoding Scheme:
Familiarity with the UTF-8 encoding rules, including how characters are encoded into one or more bytes.
Understanding the patterns that represent a valid UTF-8 encoded character.
UTF-8 Wikipedia
Characters, Symbols, and the Unicode Miracle
The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets

3.Data Representation:
How to represent and work with data at the byte level.
Handling the least significant bits (LSB) of integers to simulate byte data.

4.List Manipulation in Python:
Iterating through lists, accessing list elements, and understanding list comprehensions.
Python Lists

5.Boolean Logic:
Applying logical operations to make decisions within the program.

#By studying these concepts and utilizing the resources provided,we will be equipped to tackle the UTF-8 validation project, effectively applying bitwise operations and logical reasoning to determine the validity of UTF-8 encoded data.

#Requirements/task

I will Writing a method that determines if a given data set represents a valid UTF-8 encoding.

Prototype: def validUTF8(data)
Return: True if data is a valid UTF-8 encoding, else return False
A character in UTF-8 can be 1 to 4 bytes long
The data set can contain multiple characters
The data will be represented by a list of integers
Each integer represents 1 byte of data, therefore you only need to handle the 8 least significant bits of each integer

#end
