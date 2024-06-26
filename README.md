# Password Strength Checker

This project is a simple password strength checker application built using Python's `tkinter` library. It evaluates the strength of a given password based on various criteria and provides a rating from 0 to 7, indicating how strong the password is.

## Features

- **Password Strength Evaluation**: The application checks for the presence of uppercase letters, lowercase letters, digits, and special characters in the password.
- **Password Length Check**: It evaluates the password length and assigns points accordingly.
- **Common Password Check**: The application checks the entered password against a predefined list of common passwords.
- **Visual Feedback**: Provides visual feedback using different colors and messages to indicate the password strength.

## Getting Started

### Prerequisites

- Python 3.x
- `tkinter` library (usually comes pre-installed with Python)

### Files Structure

- `main.py`: The main script containing the password strength checker logic and GUI setup.
- `list1.txt`, `list2.txt`, `list3.txt`: Text files containing lists of common passwords to check against.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/password-strength-checker.git
    cd password-strength-checker
    ```
2. Make sure you have the required text files (`list1.txt`, `list2.txt`, `list3.txt`) in the appropriate directory as specified in the script.

### Running the Application

Run the main script using Python:
```bash
python code.py

```

## Usage

1. Open the application.
2. Enter the password you want to check in the text box.
3. Click on the "Check Strength" button.
4. A new window will appear showing the strength of the password along with a color-coded message:
    - **Red**: Weak Password
    - **Orange**: Mediocre Password
    - **Green**: Strong Password
    - **Dark Green**: Very Strong Password

## Screenshots

![Screenshot (205)](https://github.com/Belard4l/PRODIGY_CS_03/assets/123712274/2dcd9c52-c91e-4d77-b9a6-c897288f2618)
![Screenshot (206)](https://github.com/Belard4l/PRODIGY_CS_03/assets/123712274/b1f0eb1e-64ac-4066-8d13-cd17433db1a0)
![Screenshot (207)](https://github.com/Belard4l/PRODIGY_CS_03/assets/123712274/b7a67f62-1dd5-4ac0-bf07-c69206c0ce23)

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.
Feel free to reach out if you have any questions or suggestions!

Happy coding!
