# Exercise for Lab 5+6
# Creators: Heath Arroyo & Selase Mortty
## Software Description:
   Exercise for Lab 5+6 contains a Python program that takes the user's input in the form of age, first and last name, and height. This input is then run through calculations and a print statment is presented to the user that pairs their names, age, and height together.
## Installation
Run the command line and enter in the command:
```git
    git clone https://github.com/ArroyoHeath/LabExercise-5-6.git 
```
    
## Usage 
```python
    fName = input(prompt = "What is your first name?")             #prompt to the user that asks them for their first name; their input is then assigned to fName
    lName = input(prompt = "What is your last name?")              #prompt to the user asking them for their last name; their input is then assigned to lName
    height = input(prompt = "What is your height in inches?")    #prompt to the user asks them for their height in inches; user input then assigned to height
    age = input(prompt = "How old are you?")                    #prompt to the user asking them their age; user input for age is then assigned to age
    ageDays = int(age) * 365                                    #the age in days is approximated by multiplying age in years by 365 days
    heightFt = int(height) / 12                           #the height in feet is calculated by dividing the inches by 12
    heightIn  = int(height) % 12                            ##the remaining inches is calculated by finding the remainder 
    print("Your name is " + str(fName) + " " + str(lName) + ", you are at least " + str(ageDays) + " days old, and you are " + str(int(heightFt)) + " feet and " + str(heightIn) + " inches tall.") #output statement that pairs all the info together and displays it to the user
```

## How To Contribute
   Since this is simply an exercise, if you want to contribute its really simple. The program must still complete the basic function of taking in user input and then displaying it for the user in a print statement. Contribute by adding meaningful lines of code that gather input from the user. Make sure that that data is then added to the final output staement. See the "Code of Conduct" to familiarize yourself with our rules.