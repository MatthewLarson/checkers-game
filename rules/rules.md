# Checkers Rules

## Objective

Be the first player to **capture all of your opponent's pieces** or leave them with **no legal moves**.

---

## Players & Board

- Checkers is played by **2 players**.
- The game uses an **8 × 8 board** with alternating light and dark squares.
- Each player begins with **12 pieces**.
- **Only the dark squares are used** during the game. Pieces never move onto the light squares.

---

## Setup

1. Position the board so that each player has a **dark square in the bottom-left corner**.
2. Each player places their 12 pieces on the dark squares of the **three rows closest to them**.
3. The two center rows begin empty.
4. Traditionally, the player with the **dark pieces moves first**.

---

# Movement

## Regular Pieces

A normal checker may move:

- **One square diagonally forward**
- Only onto an **empty dark square**
- Regular pieces cannot normally move backward

For example:

```text
. ■ . ■ . ■ . ■
■ . ■ . ■ . ■ .
. ■ . ● . ■ . ■
■ . ◇ . ◇ . ■ .
```

The `●` piece may move diagonally forward to either `◇` square if it is empty.

---

# Capturing

You capture an opponent's piece by **jumping over it**.

A capture is possible when:

1. An opponent's piece is diagonally adjacent to your piece.
2. The square immediately beyond that piece is empty.
3. Your piece jumps over the opponent and lands on the empty square.
4. The jumped piece is removed from the board.

```text
● = Your piece
○ = Opponent
◇ = Landing square

● . . .
. ○ . .
. . ◇ .
```

The `●` jumps over the `○` and lands on `◇`.

## Captures Are Mandatory

If you have a legal capture available, **you must make a capture** instead of making a normal move.

If more than one capture is available, you may choose which legal capture to make.

---

# Multiple Jumps

If a piece makes a capture and can immediately capture another piece from its new position, it must continue jumping.

A single turn can therefore capture several pieces.

```text
●
  ○
    ◇
      ○
        ◇
```

The same piece continues jumping until it has **no additional legal captures**.

---

# Kings

When a regular piece reaches the **last row on the opponent's side of the board**, it becomes a **King**.

Kings are usually marked by:

- Stacking a second checker on top of the piece, or
- Using a special King marker.

## King Movement

A King may move:

- One square diagonally **forward**
- One square diagonally **backward**

Kings may also capture pieces in either direction.

> Kings still move only one square at a time unless they are jumping over an opponent's piece.

---

# Becoming a King During a Jump

If a regular piece reaches the opponent's back row during a capturing move, it becomes a King.

Its turn ends after reaching the King row. The newly crowned King may begin moving and capturing backward on its **next turn**.

---

# Winning the Game

You win if your opponent:

- Has **no pieces remaining**, or
- Still has pieces but **cannot make any legal move**

---

# Draws

A game may be declared a draw when neither player can reasonably force a win.

This commonly happens when:

- Both players have only a small number of Kings remaining.
- The same positions repeat without progress.
- Both players agree to a draw.

Specific tournament rules may define additional conditions for declaring a draw.

---

# Quick Reference

RuleStandard CheckersBoard8 × 8Starting pieces12 per playerPlayable squaresDark squares onlyNormal movement1 square diagonally forwardCapturingJump over an opponentCapturing mandatoryYesMultiple jumpsYesKing movementForward and backwardKing flying movementNoGoalCapture or block all opposing pieces