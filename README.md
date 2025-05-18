name = input("enter your name : ")
print("hello", name)
name = input("enter your name : ")
if all(c.isalnum() or c.isspace() for c in name):
    print("hello", name)
else:
    print("rong name !")
