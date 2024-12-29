# Write a Python function reverse_string(s) that takes a string and returns the reversed version of the string without using built-in functions like reverse().


def r_s(s):

    r_s=""

    for char in reversed(s):

        r_s+=char

    return r_s

print(r_s("Hello"))




![reverse](https://github.com/user-attachments/assets/2c2e4fe9-b7f8-4d21-81bf-d9d0a11e0ba7)
