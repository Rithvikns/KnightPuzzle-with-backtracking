# Knight's Puzzle in Chess

Let's try to understand the knight's puzzle in chess.

The diagram below represents the knight puzzle model. The knight has to travel to each and every square on the chessboard only once. It is difficult to complete this puzzle.

![Knight Puzzle](https://github.com/user-attachments/assets/77a4d7b0-f939-4f50-be3c-2faeeb8d9e5c)

Today, let's build a code to complete this puzzle.

```cpp
#include <iostream>
#include <vector>

using namespace std;


```cpp
int moveX[8] = {2, 1, -1, -2, -2, -1, 1, 2};
int moveY[8] = {1, 2, 2, 1, -1, -2, -2, -1};
