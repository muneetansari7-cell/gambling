# gamblingimport random

print("------------Welcome to Zenin gambling------------")

for i in range(5):
    ash = int(input("enter a numbers between 1 to 50 :"))

    num = random.randint(1,50)

    if ash == num:
        print("good")

    elif ash>50:
        print("choose vailid number")
        exit()

    else:
        print("try again")

