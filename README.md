Lists in Python
Names
names = ["Abdul", "Hadi", "Horab", "Aarosh", "Akhtr"]
for name in names:
     print(name)
 Greetings
 names = ["Abdul", "Hadi", "Horab", "Aarosh", "Akhtr"]
for name in names:
   print(f"Hello, {name}! Hope you're having an amazing day!")
Own List
transportation = ["Tesla car", "Yamaha motorcycle", "Boeing jet", "Kawasaki bike"]
for item in transportation:
    print(f"I would like to own a {item}.")
Guest List
dinner_guests = ["Abdul hadi", "Malika Horab", "Aroosh Fatima"]
for guest in dinner_guests:
     print(f"Dear {guest}, You are warmly invited to our home for dinner tonight from the bottom of our hearts.!")
Changing Guest List
dinner_guests = ["Abdul Hadi", "Malika Horab", "Aroosh Fatima"]

for guest in dinner_guests:
    print(f"Dear {guest}, You are warmly invited to our home for dinner tonight from the bottom of our hearts!")

print(f"\nUnfortunately, {dinner_guests[1]} can't make it to the dinner.\n")

dinner_guests[1] = "Akhtar"

for guest in dinner_guests:
    print(f"Dear {guest}, You are warmly invited to our home for dinner tonight from the bottom of our hearts!")

 More Guests
dinner_guests = ["Abdul Hadi", "Malika Horab", "Aroosh Fatima"]

for guest in dinner_guests:
    print(f"Dear {guest}, You are warmly invited to our home for dinner tonight from the bottom of our hearts!\n")

print("Great news! We found a bigger dinner table, so we can invite more people!\n")

dinner_guests.insert(0, "Sadia")

middle_index = len(dinner_guests) // 2
dinner_guests.insert(middle_index, "Ahmed")

dinner_guests.append("Fatima")

for guest in dinner_guests:
    print(f"Dear {guest}, You are warmly invited to our home for dinner tonight from the bottom of our hearts!")

Shrinking Guest List
dinner_guests = ["Sadia", "Abdul Hadi", "Ahmed", "Malika Horab", "Aroosh Fatima", "Fatima"]

print("Unfortunately, the new dinner table won’t arrive in time, so I can invite only two people for dinner.\n")

while len(dinner_guests) > 2:
    removed_guest = dinner_guests.pop()
    print(f"Sorry, {removed_guest}, I can’t invite you to dinner this time.\n")

for guest in dinner_guests:
    print(f"Dear {guest}, you are still warmly invited to our dinner tonight!\n")

del dinner_guests[0]
del dinner_guests[0]

print(f"The guest list is now empty: {dinner_guests}")

 Seeing the World

places = ["Lahore", "Karachi", "Faislabad", "Islamabad", "Rawalpindi"]

print("Original list:")
print(places)

print("\nSorted list (alphabetical order):")
print(sorted(places))

print("\nOriginal list after sorted() was used:")
print(places)

print("\nSorted list (reverse-alphabetical order):")
print(sorted(places, reverse=True))

print("\nOriginal list after reverse sorted() was used:")
print(places)

places.reverse()
print("\nList after reverse() was used:")
print(places)

places.reverse()
print("\nList after reverse() was used again (back to original order):")
print(places)

places.sort()
print("\nList after sort() was used (alphabetical order):")
print(places)

places.sort(reverse=True)
print("\nList after sort() was used (reverse-alphabetical order):")
print(places)

Dinner Guests

dinner_guests = ["Sadia", "Abdul Hadi", "Ahmed", "Malika Horab", "Aroosh Fatima", "Fatima"]

print(f"\nWe are inviting {len(dinner_guests)} people to dinner.")

print("Unfortunately, the new dinner table won’t arrive in time, so I can invite only two people for dinner.\n")

while len(dinner_guests) > 2:
    removed_guest = dinner_guests.pop()
    print(f"Sorry, {removed_guest}, I can’t invite you to dinner this time.\n")

for guest in dinner_guests:
    print(f"Dear {guest}, you are still warmly invited to our dinner tonight!\n")

del dinner_guests[0]
del dinner_guests[0]

print(f"The guest list is now empty: {dinner_guests}")

 Every Function
countries = ["Japan", "Australia", "Canada", "Germany", "Brazil", "India", "Italy"]

print(f"Number of countries: {len(countries)}\n")

print("Original list:")
print(countries)

print("\nList sorted alphabetically:")
print(sorted(countries))

print("\nOriginal list after sorted() was used:")
print(countries)

print("\nList sorted in reverse-alphabetical order:")
print(sorted(countries, reverse=True))

print("\nOriginal list after reverse sorted() was used:")
print(countries)

countries.reverse()
print("\nList after reverse() was used:")
print(countries)

countries.reverse()
print("\nList after reverse() was used again (back to original order):")
print(countries)

countries.append("South Korea")
print("\nList after append() was used (added South Korea):")
print(countries)

countries.insert(len(countries)//2, "Mexico")
print("\nList after insert() was used (added Mexico in the middle):")
print(countries)

removed_country = countries.pop()
print(f"\nList after pop() was used (removed {removed_country}):")
print(countries)

del countries[2]
print("\nList after del was used (removed the country at index 2):")
print(countries)

countries.sort()
print("\nList after sort() was used (alphabetical order):")
print(countries)

countries.sort(reverse=True)
print("\nList after sort() was used (reverse-alphabetical order):")
print(countries)

