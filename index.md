# Testing markdown
## This is ann 'h2' header
### 'h3' and so on ...


![Microsoft logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQnt253Qlda-6a5x8LltLHZD4IWMCmk7LOQ9Q&s)


Code for twttr.py:
```python
text = input("Input: ")

vowels = ["A", "E", "I", "O", "U"]

result = ""

for letter in text:
    if not letter.upper() in vowels:
        result += letter

print(f"Output: {result}")
```
