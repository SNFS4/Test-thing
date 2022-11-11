import random
import math

Butterfinger = 0
Hersheys = 0
Reeces = 0
MandMs = 0
Children = 0
Rocks = 0

inventory = [Butterfinger, Hersheys, Reeces, MandMs, Children, Rocks]



def Candy():
    treat = random.randrange(0, 100)
    Bruh = random.randrange(1, 5)
    if treat < 15 :
        inventory[0] += Bruh
    elif treat < 35 :
        inventory[1] += Bruh
    elif treat < 70 :
        inventory[2] += Bruh
    elif treat < 80 :
        inventory[3] += Bruh
    elif treat < 98 :
        inventory[4] += Bruh
    else:
        inventory[5] += Bruh
        
    
    
    
Candy()
Candy()
Candy()
Candy()
Candy()
print("You have", inventory[4], "Sour Patch Kids")
print("You have", inventory[0], "Butterfingers")
print("You have", inventory[1], "Hersheys")
print("You have", inventory[2], "Reeces")
print("You have", inventory[5], "rocks")
print("You have", inventory[3], "M&Ms")
print("Your final amount of candy is", inventory)
