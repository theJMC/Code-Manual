# Python Best Practices

## EAFP - `Easier to ask Forgiveness than Permission`

- Example:
  ```python
  # Do this:
  favNumber = 42
  userInput = input("Enter your favourite number")
  try:
    print("Your number is only " + abs(favNumber - userInput) + " away from mine!")
  except NameError as e:
    print("Please enter ONLY a number!!")
    print(e)

  # Not this:
  favNumber = 42
  userInput = input("Enter your favourite number")
  if type(userInput) == int: 
    print("Your number is only " + abs(favNumber - userInput) + " away from mine!")
  else:
    print("Please enter ONLY a number!!")
  ```
- It makes your code run faster and more efficient, the user does not mind if the program fails gracefully, only if it fails hard.

