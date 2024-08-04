# CIS567-integrated-lab-1
Lab1

# Read two integers from input
start = int(input())
end = int(input())

# Check if the second integer is less than the first
if end < start:
    print("Second integer can't be less than the first.")
else:
    # Initialize the current value to the starting integer
    current_value = start
    
    # Use a while loop to print the numbers in increments of 5
    while current_value <= end:
        print(current_value, end=' ')
        current_value += 5
    
    # Print an enter at the end
    print()
