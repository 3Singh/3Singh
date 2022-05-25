#Asking user details before the start of the quiz

while True:
    try:
        name= input("Please enter you name: ")
        if name.isalpha():
            break
    except ValueError:
        print("Please only enter name with letters")

print("Hello " + name) 
