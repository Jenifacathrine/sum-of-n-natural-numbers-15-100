# sum-of-n-natural-numbers-15-100
n = int(input("Enter a number: "))
sum_of_numbers = 0
for i in range(1, n+1):
    sum_of_numbers += i
print("The sum of first", n, "natural numbers is:", sum_of_numbers)

