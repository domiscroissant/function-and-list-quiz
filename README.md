# function-and-list-quiz
import random
inventory = [" ", " ", " "]
Money left = 20

def ItemShop():
    Money Left = 20
    while: Money > 0 
    money
        if:

        else:
        
        choice = input("press p to purchase potion, press f for food, k for key, or q to quit:")
        if choice == "p":
            if inventory[0]!=="potion":
                inventory[0]=="potion":
                print("you got potion")
        elif choice == "f":
            if inventory[1]!=="food":
                inventory[1]=="food":
                print("you got food")
        elif choice == "k":
            if inventory[2]!=="key":
                inventory[2]=="key":
                print("you got key")
        else:
            print:
            print("bye")
            
    return MoneyLeft
#the one that works-------------------------------------------------------------------------------------------       
DoExit = False
room = 1
while DoExit == False:
    print("--------------------")
    print("welcome to the shop, you have", Money, "coins")
    print("your items:", end = " ")
    print("Shop items:", "Potions: $5, Food: $3, keys $10")
    for i in range (len(inventory)):
        print(inventory[i], end = " ")
    print()
    def ItemShop()
    

    if room == 1:
        choice = input("you are in room 1 you can go south")
        if choice == 'south':
            room = 2
    if room == 2:
        choice = input("you are in room 2")

inventory = [" ", " ", " "]#blank inventory
money = 25

def shop(money):
    doExit = False #variable that runs loop like gameOver
    while doExit == False:
        print("----------------------------")
        print("welcome to da shop you have $", money)
        print("your inventory", end=" ")
        print(inventory)
        print("press q to quit, p to buy potion($5), f for food($3), k for key($10)")
        choice=input()
        if choice == "q":
            doExit = True #to quit the loop
            print("goodbye")
            
        elif choice == "f" and money >= 3:
            inventory[1]="food"
            print("you got food")
            money -= 3
        elif money < 3:
            print("you dont't have enough money")            
            
        elif choice == "p" and money >= 5:
            inventory[0]="potion"
            print("you got a potion")
            money -= 5
        elif money < 5:
            print("you dont't have enough money")
            
        elif choice == "k" and money >= 10:
            inventory[2]="key"
            print("you got a key")
            money -= 10
        elif money < 10:
            print("you dont't have enough money")
            
            

#function call
money = shop(money)
#-----------------------------------------------------------------------------------------------
