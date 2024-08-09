# Card Game Project: Snailspace-Inspired

## Overview

This repository features a personal card game project inspired by the game **Snailspace**, which is described in *Original Card Games* by David Parlett. The game concept is adapted for personal use and is not intended for publication or distribution.

## Important Notice

The game described in this project is inspired by **Snailspace** from *Original Card Games* by David Parlett. This project is a personal creation and is not intended to infringe on any copyrights. It is solely for personal use and is not intended for publication or download. Please respect the intellectual property rights of the original author and publisher.

## Game Description

### Snailspace

- **Players:** 2 (Human vs. Human or Player vs. Computer)
- **Cards:** 52
- **Type:** Positional

#### Objective

To add cards to a 5x5 grid in a spiral direction to form and score combinations similar to those in Cribbage, including:
- Pairs
- Prials (Three of a kind)
- Double Pair Royals (Four of a kind)
- Sequences (Runs) of three or more
- Flushes of three or more (with some restrictions)

#### Setup

1. Deal 25 cards face down to create a 5x5 grid, placing the next card face up at the center.
2. Deal 13 cards to each player.

#### Play

1. Each player, starting with the non-dealer, plays a card face up in a spiral order:
   - First card goes to the right of the starter.
   - Next card below, next to the left, and so on, completing the spiral to the top right.
   - Each player will have one card left at the end of their turn to choose from.

#### Scoring

Score points based on combinations made in the row or column of the played card:
- **Pair:** 2 points
- **Prial:** 6 points
- **Double Pair Royal:** 12 points
- **Run (Sequence) of three:** 3 points
- **Run of four:** 4 points
- **Run of five:** 5 points
- **Flush of three:** 3 points
- **Flush of four:** 4 points
- **Flush of five:** 5 points

Note: In runs, Ace counts as low (1). Flushes require all cards to be touching without interruption by cards of different suits.

#### Example

Here’s a sample play:

- **Annie:** diamondJ = pair (2), spade8 = 0, heartJ = prial (6), etc.
- **Benny:** heart10 = 0, club9 = run of 3, spade10 = run of 3, etc.

Total Scores:
- **Annie:** 27
- **Benny:** 43

### Variant

Instead of scoring as you go, complete the spiral and then:
- Dealer scores each of the five columns (verticals) as separate Cribbage hands.
- Non-dealer scores each of the five rows (horizontals) similarly.

## Player vs. Computer Version

In addition to the traditional human vs. human gameplay, a **Player vs. Computer** version of the game has been created. The computer opponent uses a basic AI to simulate play and provide a challenging experience. This version allows single-player mode and can be useful for practice or solo enjoyment.

## Installation

To use this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repository.git

Acknowledgments

Snailspace from Original Card Games by David Parlett for the inspirational game concept.

