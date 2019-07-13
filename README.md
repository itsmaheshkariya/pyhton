# meri-vaishu
## Hello World.

```
print("Hello, World!")
C:\Users\Your Name>python helloworld.py
```
## Basic if.
```
if 5 > 2:
  print("Five is greater than two!")
```
## Variables.
```
x = 5
y = "John"
print(x)
print(y)
```
### Assign Value to Multiple Variables.
```
x, y, z = "Orange", "Banana", "Cherry"
print(x)
print(y)
print(z)
```
### Concatinate.
```
x = "Python is "
y = "awesome"
z =  x + y
print(z)
```
### Addition.
```
x = 5
y = 10
print(x + y)
```
### Python Numbers.
```
x = 1    # int
y = 2.8  # float
z = 1j   # complex

print(type(x))
print(type(y))
print(type(z))
```
### Multiline Strings.
```
a = """Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua."""
print(a)
```
### Get the character at position 1.
```
a = "Hello, World!"
print(a[1])
```
#### Substring. Get the characters from position 2 to position 5.
```
b = "Hello, World!"
print(b[2:5])
```
#### The strip() method removes any whitespace from the beginning or the end:.
```
a = " Hello, World! "
print(a.strip()) # returns "Hello, World!"
```
#### The len() method returns the length of a string:.
```
a = "Hello, World!"
print(len(a))
```
#### The lower() method returns the string in lower case:.
```
a = "Hello, World!"
print(a.lower())
```
#### The upper() method returns the string in upper case:.
```
a = "Hello, World!"
print(a.upper())
```
#### The replace() method replaces a string with another string:.
```
a = "Hello, World!"
print(a.replace("H", "J"))
```
#### The split() method splits the string into substrings if it finds instances of the separator:.
```
a = "Hello, World!"
print(a.split(",")) # returns ['Hello', ' World!']
```
## Python Collections (Arrays).
```
thislist = ["apple", "banana", "cherry"]
print(thislist)
```

### To change the value of a specific item, refer to the index number:.
```
thislist = ["apple", "banana", "cherry"]
thislist[1] = "blackcurrant"
print(thislist)
```
### Loop Through a List.
```
thislist = ["apple", "banana", "cherry"]
for x in thislist:
  print(x)
```
### Check if Item Exists.
```
thislist = ["apple", "banana", "cherry"]
if "apple" in thislist:
  print("Yes, 'apple' is in the fruits list")
```
### List Length.
```
thislist = ["apple", "banana", "cherry"]
print(len(thislist))
```
### Add Items.
```
thislist = ["apple", "banana", "cherry"]
thislist.append("orange")
print(thislist)
```
### Insert an item as the second position:
```
thislist = ["apple", "banana", "cherry"]
thislist.insert(1, "orange")
print(thislist)
```
### Remove Item
```
thislist = ["apple", "banana", "cherry"]
thislist.remove("banana")
print(thislist)
```
##### The pop() method removes the specified index, (or the last item if index is not specified):
```
thislist = ["apple", "banana", "cherry"]
thislist.pop()
print(thislist)
```
##### The del keyword removes the specified index:
```
thislist = ["apple", "banana", "cherry"]
del thislist[0]
print(thislist)
del thislist

```
##### The clear() method empties the list:
```
thislist = ["apple", "banana", "cherry"]
thislist.clear()
print(thislist)
```
##### Make a copy of a list with the copy() method:
```
thislist = ["apple", "banana", "cherry"]
mylist = thislist.copy()
print(mylist)
```
##### Make a copy of a list with the list() method:
```
thislist = ["apple", "banana", "cherry"]
mylist = list(thislist)
print(mylist)
```
