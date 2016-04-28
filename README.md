# Wireframe Winners Selection
Web application we used for selecting the names that were participating at the Wireframe Raffle

This program uses an uniform pseudo-random number generator algorithm to get a random index for the array containing every participant's name:

    winner = list[floor(random() * list.count)];
    
Assuming:
  - `random()` a function returning a pseudo-random value between 0 and 1, including 0 but excluding 1.
  - `list` an array containing the participants' names.
  - `.count` the property of the array storing it's length.
