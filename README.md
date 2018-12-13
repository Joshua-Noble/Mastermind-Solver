# Mastermind-Solver
Python Implementation of Donald Knuth's Five-Guess Algorithm

### Introduction
Note: This is a personal project, and all code is original. 

After a night of playing Mastermind, I started this project as a personal challenge. The idea was to improve my ability in converting algorithms into code, while also considering efficiency. More importantly, I had to prove to my father that he wasn't "the best Mastermind player of his time."

### Rules
The rules of the challenge are as follows:
1. I am not allowed to look at ANY code implementations of Mastermind algorithms in ANY language
2. I am not allowed to ask any peers to examine/debug my code, until it is complete
3. I must follow the five-guess algorithm, as it is stated on the Mastermind Wikipedia page (link below)
4. I am allowed to research more info about the actual algorithm, in order to understand it better, however the articles/pages must not contain any code examples or implementations of the algorithm (links used provided below)
5. I must remember that this is a personal project and that enjoyment is an important element to successful completion

### Why Python?
I chose Python for this project as it is a great language for implementing ideas quickly, and I wanted to improve my Python skills. However, Python is computationally inefficient compared to some other languages, and this algorithm would most likely achieve better results in a lower-level language. If time permits, I'd like to try to recreate this project in C++ and compare the computation speed.

### Final Notes
While extremely effective in solving the game of Mastermind (4, 6) in the fewest moves possible, this algorithm is not optimized in terms of computational speed. It runs in a time-complexity of roughly O(N^2) (where N is the number of elements in the set S, see Wiki page for more details) and as such, the time needed for calculating guesses grows exponentially as we increase the number of pegs and/or colours. For playing variations of the game that require more pegs/colours, such as the (5, 8) variation, there may be a better approach.

### Sources
Details of algorithm can found on [Wikipedia](https://en.wikipedia.org/wiki/Mastermind_(board_game)#Five-guess_algorithm "Five-Guess Algorithm")

The following two posts were the only other sources used in helping me understand the algorithm, as I found the Wikipedia description of step 6 a bit confusing:

[Math Stack Exchange 1](https://math.stackexchange.com/questions/1192961/knuths-mastermind-algorithm)

[Math Stack Exchange 2](https://math.stackexchange.com/questions/2014141/knuths-mastermind-algoritm-the-last-step)
