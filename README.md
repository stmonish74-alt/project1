#project1
This is my first Github project
<br>
Author-MONISH ST
# even_odd_checker.py

def check_even_odd(number):
    if number % 2 == 0:
        return f"{number} is Even"
    else:
        return f"{number} is Odd"

# Example usage
if __name__ == "__main__":
    num = int(input("Enter a number: "))
    print(check_even_odd(num))

