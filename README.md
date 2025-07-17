a = int(input("Enter your Number: "))
print("Your number is:\n", a)

b = input("Yes/no: ")
print('''DO YOU WANT TO CHECK WHETHER IT IS LUCKY OR NOT:\n''', b)

if b.lower() == "yes":
    print("OK, let's check if it's lucky.")
    # Example lucky condition: number is divisible by 7
    if a % 7 == 0:
        print("Your number is lucky! 🎉")
    else:
        print("Sorry, your number is not lucky.")
elif b.lower() == "no":
    print("Okay, not checking.")
else:
    print("Invalid input. Please type 'yes' or 'no'.")
