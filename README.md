# Shuffle-Deck-of-Cards
Shuffle Deck of Cards-----------------python---------------------

import itertools, random
card list(itertools.product(range(1,14),['Spade','Heart','Diamond','Club']))
random.shuffle(card)
print("You got:")
for i in range(5):
   print(card[i][0], "of", card[i][1])

  output:
  
  You got:
5 of Heart
1 of Heart
8 of Spade
12 of Spade
4 of Spade


