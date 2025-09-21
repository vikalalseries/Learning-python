#Want to add continuous?
num1 = float(input("Enter a number: "))
num2 = float(input("Enter another number: "))
print(f"The sum is: {num1 + num2}")

while True:
    choose = input("Do you want to add another number? (y/n): ")
    if choose.lower() == 'y':
        num3 = float(input("Enter the third number: "))
        print(f"The new sum is: {num1 + num2 + num3}")
    elif choose.lower() == 'n':
        choose1 = input("what you want break(b) or continue(c) (b/c): ")
        if choose1.lower() == 'c':
            continue
        else:
            print("Bhag jao ab yaha se, tumhara kaam ho gya hai")
            break
    else:
        print("Invalid choice! Please type 'y' or 'n'.")


