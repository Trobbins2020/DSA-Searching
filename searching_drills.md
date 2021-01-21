# How many searches?

## Given a sorted list 3, 5, 6, 8, 11, 12, 14, 15, 17, 18 and using the recursive binary search algorithm, identify the sequence of numbers that each recursive call will search to try and find 8.

- I 3,5,6,8,11 => 11 is halfway and doesn't match
- II 6,8,11 => 6 is halfway and doesn't match
- III 6,8 => 8 would match being the halfway point

## Given a sorted list 3, 5, 6, 8, 11, 12, 14, 15, 17, 18 and using the recursive binary search algorithm, identify the sequence of numbers that each recursive call will search to try and find 16.

- I 12, 14, 15, 17, 18 => 12 is middle and doesn't match
- II 15, 17, 18 => 15 is smaller but not match
- III 17 => not a match, returns null/error depend on the implementation
