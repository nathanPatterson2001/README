# Programming

#### Nothing better than a little coding sesh am I right? 

*Here is some code from a coding assignment that I did previously this semester:*



`from random import *

#Two things are in the main class
class Animal:
    

    def __init__(self, name, animal, mood):
        self.name = name
        self.animal = animal
        self.mood = mood

#description used for final print statement
    def description(self):
        return "{} the {} is {}".format(self.name, self.animal, self.mood)

#animal input. Not apart of class
def main():
    
    animals = []
    
    while (True):
    
        animalName = input("What name of animal?")
        animalType = input("What type of animal?")
        userInput = input("Would you like to add more animals(y/n)?")
    
        moodInt = randint(1,3)
        if moodInt == 1:
            moodInt = "happy"
        if moodInt == 2:
            moodInt = "hungry"
        if moodInt == 3:
            moodInt = "sleepy"
    
        animal = Animal(animalName, animalType, moodInt)
        animals.append(animal)
    
        if userInput != "y":
            break

#Self.mood is equal to the random number generator 1-3
    for animal in animals:
        print(animal.description())

main()`

And here is an image from the web!
![web](https://www.google.com/search?q=shrek+image&rlz=1C5CHFA_enUS857US857&sxsrf=ALeKk03U3OhR6P37Bwpe-Hd3zCkeSuVhtQ:1588988226123&source=lnms&tbm=isch&sa=X&ved=2ahUKEwjLrpS20qXpAhXWZc0KHde6DEMQ_AUoAXoECBEQAw&biw=1054&bih=1018#imgrc=88Lz1YzeoY4sRM)



Go back to [README](READ.md)

