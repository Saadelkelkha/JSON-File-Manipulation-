# JSON-File-Manipulation-
This script succinctly demonstrates the process of interacting with JSON files in Python, encompassing reading, modifying, and saving data.

# Read Original File:

Opens "data.json" in read mode.
Loads JSON content into a dictionary using json.load().
Prints the original file content.

# Modify Dictionary:

Adds a new key-value pair ("langage": "Python") to the dictionary.

# Write Modified Data:

Opens "data.json" in write mode.
Saves the modified dictionary with json.dump() and 2-space indentation.

# Read Modified File:

Opens "data.json" in read mode.
Loads the modified JSON content into a dictionary.
Prints the content after the modification.
