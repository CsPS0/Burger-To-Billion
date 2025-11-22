# Burger to Billion

This guide will help you automate the process of getting the one billion dollars achievement in the game "Burger".

## The Challenge: One Billion Dollars

The most difficult achievement in the game is to accumulate one billion dollars. The key to this is a hidden mechanic: removing the seeds from the burgers. Each seed gives you a small amount of money, but removing all of them from a single burger can yield $100,000. If it's a cheeseburger, you get $1,000,000 per burger.

## Getting Started

### Prerequisites

- The game "Burger" must be installed and running.
- Python 3 must be installed on your computer.

### Installation

1. **Install Python:**
   - If you don't have Python installed, download it from the official website: [https://www.python.org/downloads/](https://www.python.org/downloads/)
   - During the installation, make sure to check the box that says "Add Python to PATH".

2. **Download and Extract the tool:**
   - Download the repository content and extract the folder named `Pepitas` to your desktop.

3. **Install dependencies:**
   - Open the Command Prompt.
   - Navigate to the `Pepitas` folder on your desktop. For example:
    ```
    cd Desktop\Pepitas
    ```
   - Install the required Python libraries using pip:
    ```
    pip install opencv-python pyautogui numpy
    ```

### Usage

1. **Open the game:** The game must be open and visible on your screen. It is recommended to have the game window as large as possible.
2. **Run the script:**
   - Open the Command Prompt.
   - Navigate to the `Pepitas` folder on your desktop.
   - Execute the following command to run the program:
    ```
    python Detector_Pepitas_v2.py
    ```

## How to Use

-   **Running the program:** Once you execute the Python script, the program will start, and you will see it automatically removing the seeds from the burgers.
-   **Stopping the program:**
    -   To pause the script, press the `q` key on your keyboard.
    -   To turn off the program completely, press `Ctrl+C` in the Command Prompt, or close the Command Prompt window.
