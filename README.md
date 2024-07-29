# Knight's Puzzle in Chess

Let's try to understand the knight's puzzle in chess.

The diagram below represents the knight puzzle model. The knight has to travel to each and every square on the chessboard only once. It is difficult to complete this puzzle.

![Knight Puzzle](https://github.com/user-attachments/assets/77a4d7b0-f939-4f50-be3c-2faeeb8d9e5c)

Today, let's build a code to complete this puzzle.
```console
#include <iostream>
#include <vector>
using namespace std;`
```
Let's include the libraries and the namespace .


# Task1 : List out the possible squares for the Knight next move

```console
int moveX[8] = {2, 1, -1, -2, -2, -1, 1, 2};
int moveY[8] = {1, 2, 2, 1, -1, -2, -2, -1};`
```

This lines are used to represent the next move of the knight using x axis and y axis , there are only 8 moves possible for the knight to move . In the code you can see for movex[0] = 2 and movey[0] = 1 . Thee position of the next knight move is two steps in x axis and 1 step in y axis compared to the current position .
![image](https://github.com/user-attachments/assets/c27c4d09-0ec6-4e24-a0fa-7e2eb6072085)

