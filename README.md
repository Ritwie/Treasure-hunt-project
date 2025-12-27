print("Welcome to Treasure Island")
print("Your mission is to find a treasure")

crossroad = input("You are at a crossroad where do you want to go? Type Left or Right").lower()



if crossroad == "Left":
    print("Trapped in a cave and Game Over!!")
else:
    print("You have a reached a lake.There is an island in the middle of the lake")
    boat = input("Type wait to wait for a boat or swim to swim across").lower()
if boat == "swim":
    print("Crocodile attack and Game Over!!")
else:
    print("You have reached the magic doors")
    door = input("Which door would you like to chose? Red, Blue,Yellow=").lower()  
if door == "Red":
     print("Game Over...BOOO!!!")
elif door == "Blue":
    print("Game Over...BOOO!!!")
else:
    print("You Found The Treasure!!")
