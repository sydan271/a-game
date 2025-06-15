# K. Easiest Problem, Right?

**Time limit per test:** 1 second  
**Memory limit per test:** 256 megabytes

An and Binh are playing a game with a pile of `n` stones. An goes first, and they take turns removing stones from the pile.  
On each turn, a player can remove either **1 stone** or **a number of stones that divides evenly into the remaining number of stones**.  
The player who cannot make a move loses the game.

Assume both players play optimally. Given the number of stones `n` at the start of the game, determine who will win.

This is a very easy problem. To make it even easier, you just need to answer `q` questions where each question gives you a value `n`, and you must determine the winner.

## Input

- The first line contains a single positive integer `q` (`q ≤ 1000`) — the number of queries.
- Each of the next `q` lines contains a positive integer `nᵢ` (`nᵢ ≤ 10¹⁰`) — the number of stones in the i-th query.

## Output

- Output `q` lines.
- Each line contains either `An` or `Binh` (without accents), the name of the winner of the game.

## Example

**Input**
3
1
3
4

**Output**
An
An
Binh
