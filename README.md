#Racing
####Peter the rabbit vs Rafael the turtle

This is a simulation pitting the unfocused, but fast, rabbit (Peter) against the slower, but more focused, turtle (Rafael).
User simply has to click ok on each alert or confirmation in order to view the progress of each turn in the race.
The race will end when one of the animal reaches 100 miles.

since this simulation is based on probabilities, there is no guarantee that Rafael will always win. Howver, both Peter's and Rafael's attributes has been tuned so that Rafael will win the majority of the time.

####Details

- Both turtle and rabbit will be of the Animal class. The Animal class has attributes of name, speed, and focus.
- Peter and Rafael's attributes moves each turn by predetermined attributes and by `distraction`. If distraction > focus, the the animal stops for that turn.
- Distraction is determined by `Math.random() * 10` on line 41
- On line 22 and 24, Peter and Rafael's attributes can be tweaked in the order of name, speed, focus:
```JavaScript
peter = new Animal("Peter", 6, 4);

rafael = new Animal("Rafael", 3, 9);
```
