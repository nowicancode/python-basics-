
#it is to show how to stone the name in a variable called 'name'

first_name=input("please enter your first name ")
sue_name=input("please enter your sue name ")

#storing two variables in one caled full name

full_name=first_name+ " "+ sue_name
gender = input("Are you male or female? ")

#how to use the if statements to compare two thing in this case age

#this also includes 'elif' whis is used to compare more than two things

if gender== 'male':
    print("welcome mr",full_name)
elif gender == 'female':
    print("welcome miss",full_name)
else:
    print("Invalid input. Please specify 'male' or 'female'.")
   
    #another variable called ,int, is used which allowes you to use a number.

age=int(input("what is your age? "))

if age > 18:
    print("let us procceed :)")
else:
    print("sorry you are not old enough:(")
