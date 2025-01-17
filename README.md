#Welcome the user - collect the user's name and age
print('Hi! What is your name?')
user = input("Type your name here:")
print("Hi " + user )
print("What is your age " + user)
age = input("Type your age here:")
print("So young!" + age )
#Ask the user how it can help them
print("How can I help you today?")
#From https://ipcisco.com/lesson/user-input-in-python/
#Allow the user to choose from a amenu/list of options on how they can continue the conversation
def mainMenu():
    print("Menu:")
    print("1. Option 1")
    print("2. Option 2")
    print("3. Option 3")
    print("4. Exit")

    while True:
        choice = input("Enter your choice: ")

        if choice == "1":
            # Code for option 1
            print("Option 1 selected")
        elif choice == "2":
            # Code for option 2
            print("Option 2 selected")
        elif choice =="3":
            #Code for option 3
            print("Option 3 selected")
        elif choice == "4":
            print("You have exited the chatbox!")
            break
        else:
            print("Invalid choice. Please try again.")

if __name__ == "__main__":
    mainMenu()  
    
#code from https://www.google.com/search?q=choose+from+a+menu+python&sca_esv=402dcc00bb4ec1a3&rlz=1CAPIDD_enUS1112&sxsrf=ADLYWILDgSA9Zs30kVB8KTz6iIX6F2Yucw%3A1735011022378&ei=zipqZ_bcFqK0wN4Pioy98AQ&ved=0ahUKEwj2-63du7-KAxUiGtAFHQpGD04Q4dUDCBA&uact=5&oq=choose+from+a+menu+python&gs_lp=Egxnd3Mtd2l6LXNlcnAiGWNob29zZSBmcm9tIGEgbWVudSBweXRob24yCBAhGKABGMMEMggQIRigARjDBDIIECEYoAEYwwRIkQpQwQVY4ghwAngBkAEAmAFsoAHgAqoBAzMuMbgBA8gBAPgBAZgCBKAC_QHCAgoQABiwAxjWBBhHwgIIEAAYBxgIGB7CAgsQABiABBiGAxiKBZgDAIgGAZAGCJIHAzIuMqAHiBY&sclient=gws-wiz-serp
