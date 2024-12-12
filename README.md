# Neofetch-macOS
Simple script to install neofetch on macOS

Neofetch Installation Script for macOS

This script automates the installation of Neofetch on macOS, utilizing Homebrew as the package manager. If Homebrew is not installed, it will install it for you before installing Neofetch.
Requirements

    macOS
    Homebrew (If not installed, the script will install it automatically)

Features

    Installs Homebrew if not already installed.
    Installs Neofetch via Homebrew.
    Verifies if Neofetch was installed successfully.

Installation

    Download the Script
    First, download the script install_neofetch.sh to your macOS machine.

    Give Execution Permissions
    Open your terminal and navigate to the folder where the script is located. Then, make the script executable:

chmod +x install_neofetch.sh

Run the Script
Now, you can run the script to install Neofetch:

    ./install_neofetch.sh

    The script will:
        Check if Homebrew is installed. If not, it will install it.
        Install Neofetch using Homebrew.
        Check if Neofetch was successfully installed.

Usage

After installation, you can simply run the following command to display system information with Neofetch:

neofetch

Example output:

                   _                                   
 _ __  _   _ _ __ | |_ _   _ _ __   __ _ _ __ __ _ _ __ 
| '_ \| | | | '_ \| __| | | | '_ \ / _` | '__/ _` | '_ \
| | | | |_| | | | | |_| |_| | | | | (_| | | | (_| | | | |
|_| |_|\__,_|_| |_|\__|\__,_|_| |_|\__,_|_|  \__,_|_| |_|
                                                         
System: macOS (Version)
Kernel: Darwin (Kernel version)
CPU: Intel Core i7
RAM: 16 GB

Troubleshooting

If you encounter issues during installation, ensure that you have an active internet connection for downloading Homebrew and Neofetch. You can also check if Homebrew is working correctly by running:

brew doctor

License

This script is open source and licensed under the MIT License.
