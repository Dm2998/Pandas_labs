# Pandas_labs
Data Analisis Semestre 5 lab 2, Lab9

def is_dog(word):
    return word.lower() == "dog"
# Example usage:
word = "Dog"
result = is_dog(word)
if result:
    print(f"'{word}' is a dog!")
else:
    print(f"'{word}' is not a dog.")
'Dog' is a dog!

///////////////////////
#create a function that grabs the email website domain from a string in the from.
#user@domain 
# so for example, passing "user@domain.com" would return: domain.com


# Example usage:
email_address = "user@domain.com"
domain = get_email(email_address)
if domain is not None:
    print("Domain:", domain)
else:
    print("Invalid email format")


/////////////////////////////////

# Dictionaries.
d = {'key1':'item1', 'key2':'item2'}
{'key1':'item1','key2':"item2"}
{'key1': 'item1', 'key2': 'item2'}


# 1. what is 7 to the power pf 4?
7**4
2401


#split this string
s = "hi there Sam!"
word = s.split()
print(word)
['hi', 'there', 'Sam!']
#given variables.


# Diameter of Earth is 12,742 kilometers
planet = "Earth"
diameter = 12742  # Diameter of Earth in kilometers
# Print the values
print("Planet:", planet)
print("Diameter:", diameter, "kilometers")
Planet: Earth
Diameter: 12742 kilometers








