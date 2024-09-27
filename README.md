## Typing Test

This is a simple speed typing test implemented using Python's `curses` library. The objective is to test and improve your typing speed by providing a random text for you to type as quickly and accurately as possible.

### Features

- Displays a random text for the user to type.
- Calculates and displays the Words Per Minute (WPM) while typing.
- Highlights typing errors in red.
- Provides instant feedback on typing speed and accuracy.

### Prerequisites

- Python 3.x

### Installation

1. Clone the repository:

```bash
git clone https://github.com/Raviteja-5976/Typing_Test.git
cd Typing_Test
```

2. Make sure you have the required dependencies:

```bash
pip install curses
```

### Usage

1. Run the main script:

```bash
python code/main.py
```

2. Follow the on-screen instructions:
   - Press any key to start the test.
   - Type the displayed text as quickly and accurately as possible.
   - The WPM (Words Per Minute) will be displayed in real-time.
   - Press the `Esc` key to exit the test at any time.

### File Structure

- `code/main.py`: The main script for the typing test.
- `text.txt`: A file containing lines of text to be used for the typing test. Ensure this file is in the same directory as `main.py`.

### How It Works

1. `start_screen(stdscr)`: Displays the welcome screen.
2. `display_text(stdscr, target, current, wpm)`: Displays the target text, current user input, and WPM.
3. `load_text()`: Loads a random line of text from `text.txt`.
4. `wpm_test(stdscr)`: Runs the typing test, calculates WPM, and checks for typing accuracy.
5. `main(stdscr)`: Initializes color pairs and starts the typing test.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### Contributing

Contributions are welcome! Please open an issue or submit a pull request.

### Contact

If you have any questions or suggestions, feel free to open an issue or contact me at my GitHub profile [Raviteja-5976](https://github.com/Raviteja-5976).
