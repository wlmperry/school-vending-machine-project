# School Vending Machine Review Project

This was a project completed for Dr. Safari's Programming 2 course, at Elizabeth City State University. The project involved creating a vending machine simulation using Python, where users can select items and make payments.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Project Overview

This application simulates a coffee vending machine that:
- Displays a coffee drink selection menu
- Allows user to make an order
- Accepts coins as currency
- Processes order by checking change against price and checking machine's ingredient reserves
- Handles errors in user input or insufficient funds
- Offers change back to users if they overpay
- Deducts ingredients from machine's reserves for each drink made
- Allows case-insensitive commands such as, 'help', 'report', and 'exit'
- Machine holds a state of on/off which can be manipulated by user
- Tracks machine's earnings, drinks sold, and ingredient reserves, which can be displayed to the user in a report

The project was completed as part of an exercise to practice basic programming concepts such as loops, conditionals, functions, user input handling, and exception handling, and the list data structure.

## Features

- **Item Selection:** Users can choose from a list of available drinks.
- **Balance Tracking:** The machine keeps track of the user's current balance.
- **Payment Simulation:** Users can insert money and pay for items.
- **Error Handling:** Displays messages for invalid selections or insufficient balance.
  
### Example of Features:
- View drink options (esspresso, latte, cappuccino).
- Insert a specific amount (coins).
- Make selections based on item price.
- Change balance accordingly.

## Installation Instructions

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/wlmperry/school-vending-machine-project.git
    ```

2. Navigate into the project directory:
    ```bash
    cd school-vending-machine
    ```

3. Ensure you have Python installed (Python 3.10.12 is recommended). You can check this by running:
    ```bash
    python --version
    ```

4. Run the script to start the vending machine
    ```bash
    python main.py
    ```

5. No additional dependencies are required, as this is a simple script.

## Usage

1. To run the project, navigate to the project folder and execute the Python script:
    ```bash
    python main.py
    ```

2. Follow the on-screen prompts to select an item, insert money, and complete your purchase.

Example output: Welcome, please make a selection: 1. Espresso | 2. Latte | 3. Cappuccino

Type 'exit' to power off machine or 'report' to view machine logs.
Or type 'help' then press [Enter] for additional information.

>>> 2

You selected LATTE which costs $2.50. Checking resources...

Success! Please insert money --> [||] -->
How many quarters?

## Technologies Used

- Python 3.10.12
- Basic Python libraries (`input`, `print`, `os`)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Dr. Safari for the inspiration and guidelines provided in the Programming 2 course.
- Inspiration from real-world vending machines.
- General programming community and online resources for helpful tips.

---

## Contributing

Contributions are welcome! Please fork the repository, create a new branch, make your changes, and submit a pull request.

Ensure that your code adheres to the PEP 8 style guide and is well-documented.