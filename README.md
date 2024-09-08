# Keylogger: Efficient Keystroke Monitoring

<p align="center">
  <img src="https://github.com/kalmux1/KeyLogger/blob/main/Assets/keylogger.png" alt="Keylogger Tool" width="350">
</p>

## Overview

This tool is designed to monitor and log keystrokes efficiently using Python. It captures keystrokes in real-time and stores them in a text file. This can be useful for various applications, including debugging and monitoring.

## ✨ Features

- **Real-Time Logging**: Captures keystrokes as they are typed.
- **File Storage**: Logs are saved in a text file for easy review.
- **Error Handling**: Basic error handling for file operations.

## 📚 Requirements

- Python 3.x
- `pynput` library (Install via `pip install pynput`)

## 🚀 Getting Started

1. **Clone the repository**:
    ```bash
    git clone https://github.com/kalmux1/KeyLogger.git
    cd KeyLogger
    ```

2. **Install the required library**:
    ```bash
    pip install pynput
    ```

3. **Run the keylogger**:
    ```bash
    python keylogger.py
    ```

## 🛠️ How It Works

- **write_log(data)**: Writes keystroke data to a log file.
- **keylog(key)**: Processes the keypress events and formats them.
- **listner()**: Starts the keylogger and logs keystrokes with timestamps.

## 🤝 Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any improvements or bug fixes.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📫 Contact

If you have any questions or suggestions, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/nitin-jaiswal1/) or open an issue on GitHub.
