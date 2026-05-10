import random

i = 0
chislo = random.randint(0, 100)
print("Число загаданно")

while True:
    
    user = int(input("Введите Число: "))

    if user < chislo:
        print(" " * 100)
        print("Слишком мало")
        print(" " * 100)
        i += 1

    if user > chislo:
        print(" " * 100)
        print("Слишком много")
        i += 1
        print(" " * 100)
        
    if user == chislo:
        print(" " * 200)
        print("_" * 100)
        print("Ты выйграл, количество попыток = ", i)
        print("_" * 100)
        print(" " * 200)
        break
