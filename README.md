# Take input from the user
user_input = input("Enter a string: ")

# Define vowels
vowels = "aeiouAEIOU"

# Count vowels
vowel_count = sum(1 for char in user_input if char in vowels)

# Print the result
print("Number of vowels:", vowel_count)
