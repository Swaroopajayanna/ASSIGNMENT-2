# ASSIGNMENT-2
# Task 1: Check if a Number is Even or Odd

num = int(input("Enter the number : "))
if num % 2 == 0:
    print(f"{num} is an even number.")
else:
    print(f"{num} is an Odd number.")


# Task-2: Program to calculate the sum of integers from 1 to 50

total_sum = 0

# Iterate over numbers from 1 to 50
for number in range(1, 51):
    total_sum += number

# Display the final sum
print("The sum of integers from 1 to 50 is:", total_sum)
