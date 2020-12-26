### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:

  def check_for_ace(self, card):
    if card.value = 1:  # Being a Boolean expression, it should be double equals '==' to compare the two values.
      return True
    else                # Missing colon after the else.
      return False
   

  dif highest_card(self, card1 card2):  # Missing comma between card1 and card2. Spelling error, 'dif' should be 'def'.
  if card1.value > card2.value:  # Indentation of the whole if statement is incorrect, it should be indented in "by one"
    return card                         # 'card' is not defined. This should probably be 'card1'.
  else:
    return card2
  


def cards_total(self, cards): # Rather than a function, this seems to be a class' method. Should be indented in.
  total                       # Wrong syntax to define an empty variable.
  for card in cards:
    total += card.value
    return "You have a total of" + total # This should be lined up with the 'for' statement rather than being indented.
# The lack of one whitespace after 'of' would display the total right after the 'of' word (example: 'of33') however total is most likely an INT type, so, contatenation would not work. Two possible solutions below:
# 1. return "You have a total of", total (the comma will add a space and str and int should be displayed with no errors)
# 2. return f"You have a total of {total}" (using an f string) 
  
```
