##Task1
from colorama import init, Fore
init(autoreset=True)

# Taking inputs
num1 = int(input(Fore.RED + "Enter the first number: "))
num2 = int(input(Fore.RED + "Enter the second number: "))

# Calculations and output
print()
print(Fore.MAGENTA + "Addition:", num1 + num2)
print(Fore.MAGENTA + "Subtraction:", num1 - num2)
print(Fore.MAGENTA + "Multiplication:", num1 * num2)
print(Fore.MAGENTA + "Division:", num1 / num2)


##Task2
from colorama import init, Fore, Style
init(autoreset=True)

# Taking user input
first_name = input(Fore.RED + "Enter your first " + Fore.MAGENTA + "name" + Fore.RED + ": ")
last_name = input(Fore.RED + "Enter your last " + Fore.MAGENTA + "name" + Fore.RED + ": ")

# Output greeting
print()
print(Fore.CYAN + "Hello, " + Fore.WHITE + first_name + " " + last_name + Fore.CYAN + "! Welcome to the " + Fore.MAGENTA + "Python" + Fore.CYAN + " program.")
