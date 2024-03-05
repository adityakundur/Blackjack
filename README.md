Adityas Blackjack Game in Python

Description

This project is a command-line Blackjack game implemented in Python. It uses the colorama library for colored output to enhance user experience and random for shuffling the deck of cards. The game is played against a dealer, with simple Blackjack rules applied. The objective is to achieve a hand value closer to 21 than the dealer's hand without going over.

Features

- Colored output for suits and messages using the colorama library.
- Automatic shuffling of the deck when necessary.
- Player options to Hit or Stick.
- Dealer plays according to standard Blackjack rules (hits until their hand value is at least 17).
- Ace handling as either 1 or 11 depending on the hand's score.
- Check for Blackjack (an ace with a 10 or face card).
- Basic betting system with a starting pot.

Prerequisites

- To run this game, you'll need Python installed on your system. The game also requires the colorama package for colored output. If you don't have colorama installed, you can install it using pip:
bash
Copy code
pip install colorama

How to Run

Clone this repository or download the .py file to your local machine. Navigate to the directory containing the game file in your terminal or command prompt, and run the following command:

bash
Copy code
python Blackjack.py

How to Play

After starting the game, you'll be prompted to place your bet.
You and the dealer will each be dealt two cards. One of the dealer's cards is hidden.
You can choose to 'Hit' to take another card or 'Stick' to hold your current hand.
The dealer reveals their hidden card and hits until their hand value is at least 17.
If your hand value is closer to 21 than the dealer's without going over, you win the round.
The game prompts you to play another round or quit.

Rules

- Number cards count as their face value.
- Jacks, Queens, and Kings (face cards) are worth 10 points.
- Aces can be worth 1 or 11 points, whichever is more beneficial to the hand.
- Going over 21 is
