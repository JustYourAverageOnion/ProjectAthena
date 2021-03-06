# ProjectAthena
A compilation of simple chess algorithms :)

## Algorithmic solutions for different chess problems [link](https://www.geeksforgeeks.org/tag/chessboard-problems/)
- **Knight's Tour Problem** [link](https://en.wikipedia.org/wiki/Knight's_tour)
    > A knight is placed on the first block of an empty board and, moving according to the rules of chess, must visit each square exactly once.
    - **Some of the algorithms tried here are as mentioned below**
        - [x] *Naive Algorithm* [link](https://www.geeksforgeeks.org/the-knights-tour-problem-backtracking-1/)
            - For every possible position of the knight on the chess board, the sequence for the tour is pre-fed to the program.
            - Based on the user input the corresponding tour is chosen and traversed.
            - To view : [link](https://justyouraverageonion.github.io/ProjectAthena/nt-naive.html)
        - [ ] *Backtracking Algorithm* [link](https://www.geeksforgeeks.org/the-knights-tour-problem-backtracking-1/)
            - Add one of the next moves to solution vector and recursively check if this move leads to a solution.
                - If the move chosen in the above step doesn't lead to a solution then remove this move from the solution vector and try other alternative moves.
                - If none of the alternatives work then no solution exists.
            - To view : [link](https://justyouraverageonion.github.io/ProjectAthena/nt-bactrack.html)
        - [ ] *Warnsdorff's Algorithm* [link](https://www.geeksforgeeks.org/warnsdorffs-algorithm-knights-tour-problem/)
            - There are 2 rules according to this algorithm
                - The knight is moved so that it always proceeds to the square from which the knight will have the fewest onward moves.
                - When calculating the number of onward moves for each candidate square, we do not count moves that revisit any square already visited.
            - To view : [link](https://justyouraverageonion.github.io/ProjectAthena/nt-warnsdorff.html)
        - [ ] *Divide and Conquer Algorithm* [link](https://www.youtube.com/watch?v=9fSFC00ZKPg)
            - Divide the board into 4 quadrants with 4 diamonds.
                - When the knight is placed in the board finish the diamond containing the square and all the same diamonds in the other quadrants.
                - When one set of diamonds are done move to the next set of diamonds and finish traveling the squares.
            - To view : [link](https://justyouraverageonion.github.io/ProjectAthena/nt-divideNconquer.html)
- **N Queens Problem** [link](https://en.wikipedia.org/wiki/Eight_queens_puzzle)
    > To find out how many queens can be placed on a chess board such that no two queens attack each other.
    - **Some of the algorithms tried here are as mentioned below**
        - [ ] *Naive Algorithm* [link](https://www.geeksforgeeks.org/n-queen-problem-backtracking-3/)
            - Generate all possible configurations of queens on board and print a configuration that satisfies the given constraints.
            - To view : [link](https://justyouraverageonion.github.io/ProjectAthena/nq-naive.html)
        - [ ] *Backtracking Algorithm* [link](https://www.geeksforgeeks.org/n-queen-problem-backtracking-3/)
            - Start from the leftmost column
            - Fill up the next column such that none of the existing queens clash 
                - If the queens clash then move to the next row
                - If moving the current queen is not feasible the move the previous queen and repeat the process.
            - To view : [link](https://justyouraverageonion.github.io/ProjectAthena/nq-bactrack.html)
        - [ ] New constraint [link](https://www.sciencealert.com/if-you-like-chess-and-free-money-we-have-some-really-really-good-news)
            - Have to think about it :)
- **N Knights Problem** [link](https://www.codechef.com/problems/KNIGHTS)
    > To find out how many knights can be placed on a chess board such that no two knights attack each other **given some of the cells are blocked by non attacking pawns**. Since placing knights simply on the board is a little too easy to have algorithms -.- [link](https://en.wikibooks.org/wiki/Chess/Puzzles/Placement/32_Knights/Solution).
    - **Some of the algorithms tried here are as mentioned below**
        - [x] *Odd/Even Position Algorithm*
            - Find the no of pawns placed on a dark square and a light square.
                - If more light square pawns are present then print knights on every alternate dark square except for those dark squares with pawns.
                - Else print knights on every alternate light square except for those light squares with pawns.
            - To view : [link](https://justyouraverageonion.github.io/ProjectAthena/nn-naive.html)
- **Queens and Knights Problem** [link](http://vector.org.uk/art10003900)
    > To be able to place an equal number of knights and queens on a chessboard such that no piece attacks any other piece. 
    - **Some of the algorithms tried here are as mentioned below**
        - [ ] *Naive Algorithm*
            - Generate all possible configurations of knights and queens on board and print a configuration that has the highest no of knights and queens that satisfies the given conditions.
            - To view : [link](https://justyouraverageonion.github.io/ProjectAthena/qn-naive.html)

## Assets
- Chess emoji - [link](https://emojipedia.org/search/?q=chess)
- Problem statement - Have linked where it was appropriate
- Algorithms - Same here :)
