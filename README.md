# noun_pls
A lightweight library that will give you a single noun or list nouns.

To use, clone the repo or use `pip install noun_pls`.

- Library of 12380 nouns
## Features
- Get a random noun
```
from noun_pls.noun_pls import Nouns
  
N = Nouns()
N.random_word()
 
> rower

```

- Get a random list of unique nouns of given size
```
from noun_pls.noun_pls import Nouns
  
N = Nouns()
N.random_list(10)
  
> ['save', 'rower', 'strait', 'drinkware', 'slide', 'chalice', 'bribery', 'nerve', 'motorcycle', 'Garlic press']
```
