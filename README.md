# Bomb_question
# : Imagine that you are defusing a bomb which will explode in n second.

countdown_time = int(input("Enter countdown time: "))

print(f"The bomb will explod in {countdown_time} seconds!")
for i in range(countdown_time, 0, -1):
        print(i)

user_input = input("Quick! Which wire to cut? Red or Blue? ")

if(user_input == 'Blue'):
        print("You cut the blue wire...\nThe bomb has been defused. Congratulations, you saved the day!")

elif(user_input == 'Red'):
        print("You cut the red wire...\nBOOM!!! The bomb exploded")
