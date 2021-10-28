import time
import random


def print_pause(message_to_print):

    print(message_to_print)
    time.sleep(2)

def request_restart():
    print_pause("Do you want to play again?")
    mall = input("yes\n" "No\n")
    if mall == 'yes':
        main()
    elif mall == 'no':
        exit()
    else:
        print_pause("Sorry, I don't understand.")
        request_restart()

def instructions():
    print_pause("You find yourself in a large mall filled with luxury items.")
    print_pause("To your front is a shoe store.")
    print_pause("To your left is a bag store.")
    print_pause("To your right is a makeup store.")
    print_pause("To your back is the exit door.")
    print_pause("Enter 1 to go to the shoe store.")
    print_pause("Enter 2 to go to the bag store.")
    print_pause("Enter 3 to go the makeup store")
    print_pause("Enter 4 to exit the mall")
    print_pause("What would you like to do next?")





def main():
    main = random.choice(["1", "2", "3", "4"])
    
    #print_pause()
    instructions()
    # while True:
    print_pause("Please enter a number")
    mall = input("1. shoe\n" "2. bag \n" "3. makeup \n" "4.Exit\n")
    mall = random.choice(mall)
    if mall == '1':
        print_pause("Enter shoe store")
        print_pause("you find yourself staring at shoes of different colors")
        print_pause("you try to buy a shoe.")
        print_pause("Your card was bounced at the cashier.")
        print_pause("you are about to be thrown out by security")
        print_pause("Enter 5 to exit the shoe store quietly")
        mall = input("5. Exit shoe store\n")
        if mall == '5':
            print_pause("You have lost,the game has ended.")
            request_restart()
        
            
            
    elif mall == '2':
        print_pause(" Enter bag store")
        print_pause("You find yourself staring at a limited edition bag.")
        print_pause("you are broke and you cant afford any bag here.")
        print_pause("Enter 6 to exit the bag store")
        mall = input("6. Exit bag store\n")
        if mall == '6':
            print_pause("You have lost,the game has ended.")
            request_restart()
    elif mall == '3':
        print_pause("Enter into the world of makeup")
        print_pause("You stare at newly released makeup.")
        print_pause("You pick up a few pigments and palletes ")
        print_pause("The cashier gives you a gift card")
        print_pause("Enter 7 to exit the makeup store happily")
        mall = input("7. Exit makeup store\n")
        if mall == '7':
            print_pause("You have won,the game has ended.")
            request_restart()
    elif mall == '4':
        print_pause("You dont want anything here exit the mall.")
        request_restart()
main()
