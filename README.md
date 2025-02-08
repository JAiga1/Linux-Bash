# System Information and Security Manager

## Overview
This script is a comprehensive system information and security auditing tool for Linux. It includes various utilities for monitoring processes, checking system health, performing security audits, encrypting and decrypting files, managing directories, and more.

## Features
- **System Information Display**: Provides details on CPU usage, memory usage, disk space, and network information.
- **Security Audit**: Checks for file permission issues, outdated software packages, and executable file risks.
- **System Health Check**: Monitors CPU usage, memory utilization, disk space, and network connectivity.
- **Process Monitoring**: Displays a list of active processes and their resource consumption.
- **File & Directory Management**: Delete directories, display structures, and manage files securely.
- **Encryption & Decryption**: Uses OpenSSL to encrypt and decrypt files with AES-256 encryption.
- **Network Analysis**: Displays active TCP and UDP connections, network interfaces, and status.
- **Hardware Information**: Shows CPU, memory, and disk details, along with a detailed hardware summary.
- **File Compression**: Supports zipping and unzipping of files and directories.
- **Process Management**: Allows users to terminate specific processes by PID.
- **Log Management**: Displays and archives log files for system monitoring.

## Installation
1. Ensure you have the necessary permissions to run scripts:
   ```bash
   chmod +x system_manager.sh
   ```
2. Install dependencies if not available:
   ```bash
   sudo apt install tree zip unzip lshw openssl
   ```

## Usage
Run the script using:
```bash
./system_manager.sh
```

### Menu Options:
- **1. Display System Information**: Shows CPU, memory, disk, and network details.
- **2. Display Log Files**: Lists system log files and allows archiving.
- **3. Display Directory Structure**: Shows a tree structure of a directory.
- **4. Kill a Process**: Terminates a process using its PID.
- **5. Delete a Directory/File**: Deletes a directory or file after confirmation.
- **6. Display Network Information**: Displays active network connections and interfaces.
- **7. Display Hardware Information**: Shows CPU, memory, and disk details.
- **8. Encrypt a File**: Encrypts a file using AES-256 encryption.
- **9. Decrypt a File**: Decrypts a file previously encrypted using the script.
- **10. Monitor Processes**: Displays top running processes by CPU usage.
- **11. System Health Check**: Analyzes system health based on resource utilization.
- **12. Security Audit**: Performs security checks on file permissions and outdated packages.
- **13. Zip Files or Directories**: Compresses files or directories into a zip file.
- **14. Unzip a File**: Extracts files from a zip archive.
- **15. Quit**: Exits the script.

## Security Considerations
- Run the script with administrative privileges (`sudo`) for full functionality.
- Be cautious when deleting directories or killing processes.
- Store encryption passphrases securely, as they are required for decryption.
- Regularly check log files to identify system issues or security threats.

## License
This script is provided under the MIT License. You are free to use, modify, and distribute it as needed.

## Author
Developed by **Jaiganesh** as part of Linux Bash scripting and security auditing tools.

