#Racing
####Peter the rabbit vs Rafael the turtle

This is a simulation pitting the unfocused, but fast, rabbit (Peter) against the slower, but more focused, turtle (Rafael).

####Details

- Both turtle and rabbit will be of the Animal class. The Animal class has attributes of speed and focus.
- Peter and Rafael's attributes moves each turn by predetermined attributes and by `distraction`. If distraction > focus, the the animal stops for that turn.
- Distraction is determined by `Math.random() * 10`
- On line 22 and 24, Peter and Rafael's attributes can be tweaked in the order of name, speed, focus:
```JavaScript
peter = new Animal("Peter", 6, 4);

rafael = new Animal("Rafael", 3, 9);
```
