# aoc-2015-01-java

Advent of Code (https://adventofcode.com), 2015, day 1, coded in Java.

Excerpt from the exercise description:

    Santa is trying to deliver presents in a large apartment building, but he can't find the right floor — the
    directions he got are a little confusing. He starts on the ground floor (floor 0) and then follows the instructions
    one character at a time.
    
    An opening parenthesis, (, means he should go up one floor, and a closing parenthesis, ), means he should go down
    one floor.
    
    The apartment building is very tall, and the basement is very deep; he will never find the top or bottom floors.
    
    For example:

    - (()) and ()() both result in floor 0.
    - ((( and (()(()( both result in floor 3.
    - ))((((( also results in floor 3.
    - ()) and ))( both result in floor -1 (the first basement level).
    - ))) and )())()) both result in floor -3.

    To what floor do the instructions take Santa?

Goal: parse a text input composed entirely of ( and ) and return the difference between the counts of those two symbols.
