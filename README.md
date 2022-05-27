# unique-in-order
This function takes a string sequence and returns a list of characters which preserves the original order while no character repeats itself consecutively. For example:

uniqueInOrder('AAAABBBCCDAABBB') == ['A', 'B', 'C', 'D', 'A', 'B']

uniqueInOrder('ABBCcAD')         == ['A', 'B', 'C', 'c', 'A', 'D']

uniqueInOrder([1,2,2,3,3])       == [1,2,3]
