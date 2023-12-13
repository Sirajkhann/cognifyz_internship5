# cognifyz_internship5
string = "123"

# this will automatically generate reverse

rev = ""
for char in string:
    rev = char + rev

print("Palindrome") if string == rev else print("Not Palindrome")

print("string: " + str(string))

print("rev: " + str(rev))
