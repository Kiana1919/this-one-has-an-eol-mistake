# this-one-has-an-eol-mistake

""""
Program Goals:
1. Get the input from the user!
2. Convert that input to an INT
3. Add that input to a list
4. Pull values from specific index positions
""""

#create funtions that will perform those actions above

def mainProgram():
    while True:
            print("Hello, there! Let's work with lists!")
            print("Choose one of the following options.  Type a number ONLY!")
            choice = input("""1. Add to list,
2. Return the value at an index position
3. End Program  """)
            if choice == "1":
                addToList()
            elif choice == "2":
                indexValues
            elif choice == "3":
                break
            #we need to add an exit program AAAAAND error catching!



def addToList():
    newItem = input("Please type an integer! ")
    myList.append(int(newItem))
    print(myList)

def indexValues():
    indexPos = input("At what indexposition would you like to look?")
    print(myList[int(indexPoss)])
    
if __name__  == "__main__":
        mainProgram()
