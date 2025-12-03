import random
import random

# Define the minimum and maximum possible values for a standard die
MIN_VALUE = 1
MAX_VALUE = 6

# Simulate the roll of the first die
die1_result = random.randint(MIN_VALUE, MAX_VALUE)

# Simulate the roll of the second die
die2_result = random.randint(MIN_VALUE, MAX_VALUE)

# Calculate the total score
total_score = die1_result + die2_result

# Print the results
print(f"Result of Die 1: {die1_result}")
print(f"Result of Die 2: {die2_result}")
print(f"Total score from both dice is: {total_score}")
