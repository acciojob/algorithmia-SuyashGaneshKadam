# Algorithmia

## Instructions

Once upon a time in the land of Algorithmia, there lived a wise and skillful librarian named Merlin. His library was filled with books containing the knowledge of the world, but there was a problem - the books were not properly organized, making it difficult for the inhabitants of Algorithmia to find the knowledge they sought.

One day, a young student named Ada visited the library to find a book on the magical secrets of sorting. She noticed the disarray of the library and offered to help Merlin sort the books. Merlin, impressed by Ada's enthusiasm, decided to test her problem-solving skills.

He presented Ada with a challenge: a box filled with scrolls, each labeled with a number. Merlin asked Ada to sort the scrolls in ascending order, but with a twist - the scrolls were enchanted and could only be compared and merged with each other.
Merlin explained the enchantment's rules:
The scrolls could be divided into smaller groups, but each group must be sorted individually before merging.

The sorted groups could only be merged in pairs, comparing and combining the scrolls in ascending order.
Ada realized that this magical sorting challenge was a perfect opportunity to apply her knowledge of divide-and-conquer algorithms. She was determined to impress Merlin with her sorting skills and help bring order to the library.
Can you help Ada sort the enchanted scrolls according to the rules Merlin described?

```Input:
An array of integers representing the numbers on the enchanted scrolls.
Output:
A new array containing the integers in ascending order, sorted according to the enchantment's rules.
```

```
console.log(sortScrolls([5, 2, 1, 8, 3, 7]));
// Output: [1, 2, 3, 5, 7, 8]

console.log(sortScrolls([38, 27, 43, 3, 9, 82, 10]));
// Output: [3, 9, 10, 27, 38, 43, 82]

console.log(sortScrolls([21, 14, 0, -5, 9]));
// Output: [-5, 0, 9, 14, 21]


```
