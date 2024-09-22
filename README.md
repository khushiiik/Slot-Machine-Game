# Slot Machine Game 🎰

A simple slot machine game built with JavaScript that allows users to deposit money, place bets, and spin the reels to test their luck!

## Features

1. Deposit money to start playing.
2. Select the number of lines to bet on (1-3).
3. Place your bet per line.
4. Spin the slot machine and check if you won.
5. Get winnings based on the symbols matched.
6. Option to play again until you run out of money.

## Game Rules

- **Symbols**:  
  💎 (Diamond), 🌭 (Hotdog), 🍎 (Apple), 💥 (Explosion)
- **Symbol Count**:  
  💎: Appears 2 times  
  🌭: Appears 4 times  
  🍎: Appears 6 times  
  💥: Appears 8 times
- **Symbol Values**:  
  💎: 5x  
  🌭: 4x  
  🍎: 3x  
  💥: 2x
- **Winning Condition**: If all the symbols in a row match, you win an amount based on the symbol value and your bet.

## How to Play

1. **Deposit Money**: The game starts by asking the player to deposit an amount.
2. **Bet on Lines**: Choose how many lines (1-3) you want to bet on.
3. **Place Your Bet**: Enter the bet per line. Your total bet will be `bet * number of lines`.
4. **Spin**: The reels spin, and if the symbols in a row match, you win!
5. **Play Again**: You can keep playing until you run out of money.
