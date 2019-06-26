# Python-Projects
My beginner projects 

#Mario.py...

print("Height: ")
h = int(input())
1<=h<=23
i = 0

while(h<1 or h>23):
    print("Invalid input")
    h = int(input())

for i in range(h):
    print(" " * (h-i) + "#" * (i+2))
