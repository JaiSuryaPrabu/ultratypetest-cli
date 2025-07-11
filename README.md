# Ultratypetest-CLI ⌨️

![Ultratypetest-CLI Demo](acc_ss.png)

A blazingly fast, lightweight, and insightful Command-Line Interface (CLI) tool for testing your typing speed, tracking your progress, and identifying areas for improvement. Built with Python and `curses`.

---

## ✨ Features

- **Interactive Typing Tests:** Test your skills against a variety of sentences in a clean, terminal-based interface.
- **Real-time Feedback:** Get instant visual feedback with an intuitive underscore cursor and color-coded characters (green for correct, red for incorrect).
- **WPM & Accuracy Tracking:** Every test calculates your Words Per Minute (WPM) and accuracy.
- **Persistent History:** Automatically saves the results of every test so you can see your progress over time.
- **Insightful Statistics:**
    - View your overall **average WPM**, **best W.P.M**, and **average accuracy**.
    - A dedicated **Key Statistics** page visualizes your accuracy for each character on a keyboard layout, helping you pinpoint keys you need to practice.
- **Cross-Platform:** Works on Windows, macOS, and Linux.
- **Lightweight & Fast:** Starts instantly with minimal dependencies.

---

## 🚀 Installation

There are two ways to install Ultratypetest-CLI, depending on your needs.

### For Non-Developers (The Easy Way)

This is the recommended method for most users. You get a single executable file that runs without needing to install Python or any dependencies.

1.  Go to the [**Releases Page**](https://github.com/your-username/ultratypetest-cli/releases) of this repository.
2.  Under the latest release, find the file for your operating system (e.g., `Ultratypetest-windows.zip`, `Ultratypetest-macos.zip`).
3.  Download and unzip the file.
4.  You will find a single executable file inside (e.g., `ultratypetest.exe`). You can now run the application directly from your terminal!

### For Developers (via `pip`)

> Head over to the PyPi official [page](https://pypi.org/project/ultratypetest-cli/)

If you have Python installed and are comfortable with the command line, you can install the tool using `pip` (or `uv`).

```bash
# Install the package from PyPI
pip install ultratypetest-cli #or
uv pip install ultratypetest-cli

# Now you can run it from anywhere
ultratypetest
```

---

##  Usage

Once installed, simply run the command in your terminal:

```bash
ultratypetest
```

This will launch the application and present you with the main menu. Use the **arrow keys** (`↑` / `↓`) to navigate the menu and **Enter** to select an option.

### Menu Options

-   **Start Test:** Begins a new typing test.
    -   Press any key to start the timer.
    -   Press `ESC` at any time to cancel the test and return to the menu.
-   **View History:** Shows a log of your past test results (WPM, Accuracy, Duration).
-   **View Stats:** Displays your all-time best WPM, average WPM, and average accuracy.
-   **View Key Stats:** Shows the keyboard layout with each key color-coded by your accuracy, helping you identify weaknesses.
-   **Quit:** Exits the application.

---

## 🛠️ Contributions

Interested in contributing or running from the source?

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/JaiSuryaPrabu/ultratypetest-cli.git
    cd ultratypetest-cli
    ```

2.  **Create a virtual environment:**
    We recommend using `uv` for a fast setup.
    ```bash
    # Install uv if you don't have it
    pip install uv

    # Create and activate the virtual environment
    uv sync
    ```

3.  **Install dependencies:**
    ```bash
    uv pip install -e .
    ```
    The `-e .` installs the project in "editable" mode.

4.  **Run the application:**
    ```bash
    python -m ultratypetest_cli
    ```

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
