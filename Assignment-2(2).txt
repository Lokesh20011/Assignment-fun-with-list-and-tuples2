# Program to create a dictionary of alphabets and their ASCII values

alphabets = "abcdefghijklmnopqrstuvwxyz"

ascii_values = {alphabet: ord(alphabet) for alphabet in alphabets}

print(ascii_values)