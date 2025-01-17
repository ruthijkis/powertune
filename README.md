# PowerTune

PowerTune is a Python program designed to optimize power settings on Windows systems based on the current user activity. The program switches between performance-oriented and energy-saving power plans to enhance performance during high activity periods and conserve energy when activity is low.

## Features

- Automatically detects current user activity level.
- Switches to High Performance power plan during periods of high activity.
- Switches to Power Saver power plan during periods of low activity.

## Installation

1. Ensure you are running this script on a Windows operating system.
2. Ensure Python 3.x is installed on your system.
3. Clone the repository or download the `powertune.py` file.

## Usage

Run the script using Python:

```bash
python powertune.py
```

The script will determine the current activity level and switch the power plan accordingly.

## Customization

The `get_current_activity` function contains a dummy implementation for determining user activity based on the time of day. You can customize this function to better suit your needs, such as monitoring CPU usage, running applications, or other indicators of user activity.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.