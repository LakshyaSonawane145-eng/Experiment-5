# Experiment-5
->Aim : Study of Dictionaries

**Theory**:
- A dictionary is a mutable and unordered data structure that stores data in key : value pairs.

- Dictionaries are created using curly braces {}.

- Values are retrieved using unique keys, allowing fast and efficient access.

- Duplicate keys are not allowed; the latest value assigned to a key overwrites the previous one.

- The len() function is used to find the number of key–value pairs in a dictionary.

- Dictionaries allow adding new keys, updating existing values, and removing elements using built-in methods.

- Dictionaries are commonly used to store structured and real-world data in Python.

  **Algorithm**:
- Start
- Create dictionaries using {}
- Handle duplicate keys (latest value retained automatically)
- Update values using dictionary[key] = value
- Retrieve values safely using dictionary.get(key, default)
- Accept user input using input()
- Validate login using if dictionary.get(key) == value
- Find the highest value using max(dictionary, key=dictionary.get)
- Display results using print()
- Stop

- ✅ Algorithm – Problem 1
- (Create dictionary and update value)
Start
Create a dictionary products with product names as keys and prices as values
Display the original dictionary
Update the value of key "Book" to 65
Display the updated dictionary
Stop

- ✅ Algorithm – Problem 2
- (Search student marks using .get() method)
Start
Create a dictionary students_marks with student names as keys and marks as values
Read the student name from the user
Use get() method to retrieve marks
If the name exists, display the marks
Else, display "Student not found"
Stop

- ✅ Algorithm – Problem 3
- (User login validation using dictionary)
Start
Create a dictionary users with usernames as keys and passwords as values
Read username and password from the user
Compare entered password with the value stored for the username
If both match, display "Login Successful"
Else, display "Login Failed"
Stop

- ✅ Algorithm – Problem 4
- (Find topper from marks dictionary)
Start
Create a dictionary marks with student names as keys and marks as values
Use max() function with key=marks.get to find highest marks
Store the topper name
Display the topper name and their marks
Stop

**Conclusion**:
Python dictionaries provide an efficient way to store and manage data using unique key–value pairs.
These algorithms demonstrate the use of Python dictionaries for data storage, searching, updating, authentication, and comparison using built-in functions like get() and max(). 
The integrated algorithm highlights how dictionary operations like updating, safe retrieval, searching, and analysis can be easily performed using built-in commands, making dictionaries powerful and practical for real-world applications
