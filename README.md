
# 1. capitalize() - Capitalizes the first character and converts others to lowercase
s = "hello world"
print(s.capitalize())  # Output: "Hello world"

# 2. casefold() - Converts the string to lowercase (more aggressive than lower)
s = "HELLO"
print(s.casefold())  # Output: "hello"

# 3. center() - Centers the string in a field of a specified width
s = "hello"
print(s.center(10, '*'))  # Output: "**hello***"

# 4. count() - Counts occurrences of a substring in the string
s = "hello world"
print(s.count('l'))  # Output: 3

# 5. encode() - Encodes the string into bytes
s = "hello"
print(s.encode('utf-8'))  # Output: b'hello'

# 6. endswith() - Checks if the string ends with the specified suffix
s = "hello world"
print(s.endswith('world'))  # Output: True

# 7. expandtabs() - Replaces tab characters with spaces
s = "hello\tworld"
print(s.expandtabs(4))  # Output: "hello   world"

# 8. find() - Returns the lowest index where a substring is found
s = "hello world"
print(s.find('world'))  # Output: 6

# 9. format() - Formats the string using placeholders
name = "Alice"
age = 30
print("Hello, {}! You are {} years old.".format(name, age))  # Output: "Hello, Alice! You are 30 years old."

# 10. format_map() - Performs string formatting with a dictionary
data = {'name': 'Alice', 'age': 30}
print("Hello, {name}! You are {age} years old.".format_map(data))  # Output: "Hello, Alice! You are 30 years old."

# 11. index() - Returns the index of the first occurrence of a substring
s = "hello world"
print(s.index('world'))  # Output: 6

# 12. isalnum() - Checks if the string is alphanumeric
s = "hello123"
print(s.isalnum())  # Output: True

# 13. isalpha() - Checks if the string contains only alphabetic characters
s = "hello"
print(s.isalpha())  # Output: True

# 14. isdecimal() - Checks if the string contains only decimal characters
s = "12345"
print(s.isdecimal())  # Output: True

# 15. isdigit() - Checks if the string contains only digits
s = "12345"
print(s.isdigit())  # Output: True

# 16. isidentifier() - Checks if the string is a valid identifier
s = "hello"
print(s.isidentifier())  # Output: True

# 17. islower() - Checks if all characters are lowercase
s = "hello"
print(s.islower())  # Output: True

# 18. isnumeric() - Checks if the string contains only numeric characters
s = "12345"
print(s.isnumeric())  # Output: True

# 19. isspace() - Checks if the string contains only whitespace
s = "   "
print(s.isspace())  # Output: True

# 20. istitle() - Checks if the string is in title case
s = "Hello World"
print(s.istitle())  # Output: True

# 21. isupper() - Checks if all characters are uppercase
s = "HELLO"
print(s.isupper())  # Output: True

# 22. join() - Joins a sequence of strings with the specified separator
words = ["hello", "world"]
print(" ".join(words))  # Output: "hello world"

# 23. ljust() - Left-aligns the string in a field of the specified width
s = "hello"
print(s.ljust(10, '*'))  # Output: "hello*****"

# 24. lower() - Converts all characters to lowercase
s = "HELLO"
print(s.lower())  # Output: "hello"

# 25. lstrip() - Removes leading whitespace or specified characters
s = "   hello"
print(s.lstrip())  # Output: "hello"

# 26. partition() - Splits the string into three parts: before, separator, and after
s = "hello world"
print(s.partition(' '))  # Output: ('hello', ' ', 'world')

# 27. replace() - Replaces a substring with another substring
s = "hello world"
print(s.replace('world', 'everyone'))  # Output: "hello everyone"

# 28. rfind() - Returns the highest index where a substring is found
s = "hello world"
print(s.rfind('l'))  # Output: 9

# 29. rindex() - Returns the index of the last occurrence of a substring
s = "hello world"
print(s.rindex('l'))  # Output: 9

# 30. rjust() - Right-aligns the string in a field of the specified width
s = "hello"
print(s.rjust(10, '*'))  # Output: "*****hello"

# 31. rpartition() - Splits the string into three parts from the right
s = "hello world"
print(s.rpartition(' '))  # Output: ('hello', ' ', 'world')

# 32. rsplit() - Splits the string from the right
s = "apple,banana,orange"
print(s.rsplit(',', 1))  # Output: ['apple,banana', 'orange']

# 33. rstrip() - Removes trailing whitespace or specified characters
s = "hello   "
print(s.rstrip())  # Output: "hello"

# 34. split() - Splits the string into a list at the specified separator
s = "apple,banana,orange"
print(s.split(','))  # Output: ['apple', 'banana', 'orange']

# 35. splitlines() - Splits the string at line breaks
s = "hello\nworld"
print(s.splitlines())  # Output: ['hello', 'world']

# 36. startswith() - Checks if the string starts with a specified prefix
s = "hello world"
print(s.startswith('hello'))  # Output: True

# 37. strip() - Removes leading and trailing whitespace or specified characters
s = "   hello   "
print(s.strip())  # Output: "hello"

# 38. swapcase() - Swaps the case of all characters
s = "Hello World"
print(s.swapcase())  # Output: "hELLO wORLD"

# 39. title() - Converts the first character of each word to uppercase
s = "hello world"
print(s.title())  # Output: "Hello World"

# 40. upper() - Converts all characters to uppercase
s = "hello"
print(s.upper())  # Output: "HELLO"

# 41. zfill() - Pads the string with zeros to the specified width
s = "42"
print(s.zfill(5))  # Output: "00042"

# 42. removeprefix() - Removes the specified prefix from the string (Python 3.9+)
s = "TestHook"
print(s.removeprefix('Test'))  # Output: "Hook"



In Python, variable names must follow certain rules to ensure that the code is valid and works properly. Here's a breakdown of the key rules for naming variables in Python:

1. Valid Characters
  
Variable names can contain:
Letters (a-z, A-Z)
Digits (0-9), but not as the first character.
Underscores (_)
  
2. First Character
  
The first character of a variable name must be a letter or an underscore (_).
Cannot start with a number.
Examples of valid first characters:

x
_variable
var1
Examples of invalid first characters:

1variable (starts with a number)
  
3. Case Sensitivity
  
Python is case-sensitive, meaning that uppercase and lowercase letters are treated as different characters.
Examples:

myVariable and myvariable are two different variables.
  
4. Keywords (Reserved Words)
  
Python has a set of reserved words (also known as keywords), which are part of the language syntax. These cannot be used as variable names.
Some examples of Python keywords:

if, else, while, for, def, class, True, False, import, None, etc.
You can check the list of reserved keywords in Python using the keyword module:

import keyword
print(keyword.kwlist)
  
5. Length of the Name
  
Python does not impose any strict limit on the length of variable names, but it is recommended to keep them meaningful and not too long.
  
6. Use of Underscores in Python Naming:
  
Single Leading Underscore (_variable): Indicates internal use, suggesting "private" (not strictly enforced).
Double Leading Underscore (__variable): Triggers name mangling to avoid subclass conflicts.
Single Trailing Underscore (variable_): Used to avoid conflicts with Python keywords (e.g., class_).
Double Leading and Trailing Underscore (__variable__): Reserved for special methods (e.g., __init__, __str__).
  
7. No Spaces
  
Variable names cannot contain spaces. Use underscores instead if needed.
Valid: my_variable Invalid: my variable

8. No Special Characters
  
You cannot use special characters such as @, #, $, %, etc., in variable names.
  
9. Global vs Local Variables
  
If you want to use a variable globally across multiple functions, make sure you declare it at the top of the script. If a variable is only meant for a specific function, it should be declared within that function scope.
Examples of Valid Variable Names:

x = 10
total_amount = 100.5
user_name = "Alice"
myVariable = 45
_class = "Test"
totalAmount1 = 25
Examples of Invalid Variable Names:
  
1variable = 10  # Starts with a number
class = "example"  # Reserved keyword
user-name = "Bob"  # Contains a hyphen
total@amount = 30  # Contains a special character

  VALID NAMES:
  
  my_variable = 10
totalAmount = 25
_class = "test"
  
  INVALID NAMES:
  
  1variable = 10  # Starts with a number
class = "test"  # Reserved keyword
my variable = 5  # Contains space
