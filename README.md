🎯 Higher or Lower – Instagram Followers Game

A fun Python console game that challenges players to guess which celebrity has more followers on Instagram. Inspired by the classic Higher or Lower format, this project uses real-like celebrity data and keeps score as long as the user guesses correctly.


🚀 Features

* Randomly selects two celebrities from a dataset

* Compares Instagram follower counts

* Keeps score for consecutive correct guesses

* ASCII art visuals for better game experience

* Simple and interactive command-line interface


🧠 How It Works

1. The game displays two celebrity profiles: A and B.

2. You guess which one has more Instagram followers by typing 'A' or 'B'.

3. If you're correct, your score increases and B becomes the next A.

4. The game continues until you make an incorrect guess.


🖥️ Example Gameplay

Compare A: Ariana Grande, a Musician, from United States

VS

Against B: Cristiano Ronaldo, a Footballer, from Portugal

Who has more followers? Type 'A' or 'B': b

You're right! Current score: 1

📁 Project Structure


.
├── main.py             # Main game logic
├── art.py              # Contains ASCII art (logo and vs)
├── game_data.py        # Contains the celebrity dataset
├── README.md           # You're here!


📦 Requirements

* Python 3.x

This project uses only built-in libraries like random, so no extra installations are needed.


✅ How to Run

python main.py

Make sure art.py and game_data.py are in the same directory as main.py.


🌟 Future Improvements

* Add more celebrity data or update existing ones

* Implement categories (e.g., musicians vs. athletes)

* Web or GUI version using Flask or Tkinter


