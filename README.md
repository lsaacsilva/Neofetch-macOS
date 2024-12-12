# Neofetch-macOS
Simple script to install neofetch on macOS

# Neofetch Installation Script for macOS

This script automates the installation of **Neofetch** on macOS, utilizing **Homebrew** as the package manager. If Homebrew is not installed, it will install it for you before installing Neofetch.

## Requirements

- macOS
- **Homebrew** (If not installed, the script will install it automatically)

## Features

- Installs **Homebrew** if not already installed.
- Installs **Neofetch** via **Homebrew**.
- Verifies if Neofetch was installed successfully.

## Installation

1. **Download the Script**  
   First, download the script `install_neofetch.sh` to your macOS machine.

2. **Give Execution Permissions**  
   Open your terminal and navigate to the folder where the script is located. Then, make the script executable:

   ```bash
   chmod +x install_neofetch.sh

3. **Run the Script**
   Now, you can run the script to install Neofetch:
   
   ```bash
    ./install_neofetch.sh

    ## The script will:
        Check if Homebrew is installed. If not, it will install it.
        Install Neofetch using Homebrew.
        Check if Neofetch was successfully installed.

Usage

After installation, you can simply run the following command to display system information with Neofetch:

```bash
neofetch
