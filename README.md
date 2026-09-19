# MASA Scientific Precision Calculator

Advanced scientific computational calculator featuring trigonometric, logarithmic, and statistical functions

## Technical Architecture

The application is architected with modular separation of concerns adhering to modern clean code standards:

- **Component Layering**: Isolated view layouts, state managers, and service controllers.
- **Defensive Engineering**: Robust input sanitization and exception management.
- **Modern Design Standards**: High-contrast dark-mode interface styled for optimal usability and visual polish.

## Preview

![Application Interface](screenshots/app_interface.png)

## Features

- Comprehensive scientific function set: sin, cos, tan, log, ln, factorial, and power.
- Radian and Degree mode switching with real-time angle conversion.
- Memory storage registers (M+, M-, MR, MC) for multi-step calculations.
- Formatted mathematical display with historical expression evaluation.

## Prerequisites

- Python 3.10 or higher
- Required packages:

```bash
pip install customtkinter pillow requests
```

## Execution

Launch the application via Python:

```bash
python "Scientific Calculator using Tkinter in Python/index.py"
```

## Project Structure

```
.
├── Scientific Calculator using Tkinter in Python
├── screenshots/
│   └── app_interface.png
├── .gitignore
├── LICENSE             # MIT License
└── README.md           # Developer documentation
```

## License

This project is licensed under the terms of the MIT License. Refer to the `LICENSE` file for details.
