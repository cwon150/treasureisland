# treasureisland

print("Welcome to Treasure Island.")
print("Your mission is to find the treasure.")
choice1 = input('You\'re at a crossroad. Where do you want to go? Type "left" or "right" \n Answer: ').lower()
if choice1=="left":
    choice2 = input('You\'ve come to a lake. There is an island in middle of the lake.Type "wait" to wait for a super speed boat.'
                    'Type "swim" to swim across like a fast and furious shark.\n Answer: ').lower()
    if choice2=="wait":
        choice3 = input('You arrive at the remote island unharmed. There is a house with 3 mysterious doors. One red, one yellow and one blue (Also, you can type other colour). Which colour do you choose?\n').lower()
        if choice3=="red":
            print("You have chosen 'red'. It's a room full of fire. Game Over")
        elif choice3=="yellow":
            print("You have chosen 'yellow'. You found the treasure.You win!")
        elif choice3=="blue":
            print("You have chosen 'blue'. You enter a room of beasts. Game Over.")
        else:
            print("You chose a door that does not exist. Game Over")
    else:
        print("You have chosen 'swim'. You will attacked by a angry gigantic trout. Game Over")
else:
    print("You choose 'right' so you fall into a hole. Game Over.")

