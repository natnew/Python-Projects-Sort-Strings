# Python Projects: Sort Strings 🐍
This repo contains python code that sorts some strings.<br>
Run the code.


Python
```python
print()
message = 'Welcome to my humble abode!'
number = '192746'
print(message)
print(number)

message_sorter = sorted(message)
number_sorted = sorted(number)

print(message_sorter)
print(number_sorted)

print('Sort strings by words:')
message_sorter_word = sorted(message.split())
print(message_sorter_word)
```

Output
```python
Welcome to my humble abode!
192746
[' ', ' ', ' ', ' ', '!', 'W', 'a', 'b', 'b', 'c', 'd', 'e', 'e', 'e', 'e', 'h', 'l', 'l', 'm', 'm', 'm', 'o', 'o', 'o', 't', 'u', 'y']
['1', '2', '4', '6', '7', '9']
Sort strings by words:
['Welcome', 'abode!', 'humble', 'my', 'to']
```
