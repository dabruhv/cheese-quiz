# cheese-quiz
import random



print("question 1)")
print()
print()
print("enter your score please")

num = int(input())

if num >= 9000:
    print("YOU ARE EPIC IMPASTA MONGUS SUS!!!!!!!!!!!!!!!!!!!!!!!!")
elif num < 9000:
    print("get gud skrub ur bad at am0guz")


print()
print()
print("question 2)")

print()
print()

for i in range(10,100,5):
    print(i)


print()
print()

for j in range(0,12):
    print("sus cheese pls")


print()
print()

pantry=[]

class cheese: 
    def __init__(self):
        self.xpos = random.randrange(0,300)
        self.ypos = random.randrange(0,300)
        self.melted = False
    def melt(self):
        melt = random.randrange(1,60)
        if melt <= 30:
            self.melted = True
        elif melt > 30 and melt <= 60:
            self.melted = False
    def __del__(self): #destructor
        print("cheese melt:,((((((((((((((((")

class bleu(cheese):
    def __init__(self):
        self.name = "bleu"
        cheese.__init__(self)

    def printInfo(self):
        print("I am bleu cheese and im at (", self.xpos, self.ypos,")")

class swiss(cheese):
    def __init__(self):
        self.name = "swiss"
        cheese.__init__(self)

    def printInfo(self):
        print("I am swiss cheese and im at (", self.xpos, self.ypos,")")

class cheddar(cheese):
    def __init__(self):
        self.name = "cheddar"
        cheese.__init__(self)

    def printInfo(self):
        print("I am cheddar cheese and im at (", self.xpos, self.ypos,")")

class american(cheese):
    def __init__(self):
        self.name = "merica"
        cheese.__init__(self)

    def printInfo(self):
        print("i Am MeRiCa ChEeSe AnD iM aT (", self.xpos, self.ypos,")")


s= swiss()
pantry.append(s)
c= cheddar()
pantry.append(c)
a= american()
pantry.append(a)
b= bleu()
pantry.append(b)
