[![Version](https://img.shields.io/badge/Version-1.0.2-red.svg)](version) [![License](https://img.shields.io/badge/License-BSD--Clause_3-green.svg)](LICENSE) [![Readme em Português e Inglês](https://img.shields.io/badge/README-en%2Fpt--br-blue)](#)

```bash
                                                                  _               
             _ __  _ __ _____  ___ __ ___   _____  __    ___  ___| |_ _   _ _ __  
            | '_ \| '__/ _ \ \/ / '_ ` _ \ / _ \ \/ /   / __|/ _ \ __| | | | '_ \ 
            | |_) | | | (_) >  <| | | | | | (_) >  <    \__ \  __/ |_| |_| | |_) |
            | .__/|_|  \___/_/\_\_| |_| |_|\___/_/\_\___|___/\___|\__|\__,_| .__/ 
            |_|                                    |_____|                 |_|     v1.0.2  
Requirements

    Installed Debian 13 Trixie

    Superuser permissions
    bash

su root

Installed Git
bash

apt install git

(Important) Clone the repository from the directory:
bash

 cd /

Usage Instructions

    Clone the repository to your Debian 13 system.

bash

# With git already installed on your machine, clone the repository
git clone https://github.com/mathewalves/Proxmox-Debian13.git

# Access the downloaded folder with the 'cd' command
cd /Proxmox-Debian13

    Make the script executable.

bash

# Give execution permission to the setup
chmod +x ./setup

    Run the setup.

bash

./setup

Additional Packages

The script installs some additional packages to enhance the experience and provide additional functionalities. The packages include:

    'sudo': Essential tool to grant administrative permissions to the selected user.

    'nala': An application that enhances the graphical interface of 'apt'.

    'neofetch': A system information display tool with a colorful and user-friendly interface.

    'net-tools': A classic set of network utilities, such as ifconfig and route.

    'nmap': A powerful network scanning and security auditing tool.

Make sure to review the official documentation for each package for more details on their functionalities.
Features

    Proxmox Installation: The script automatically installs Proxmox on the Debian 13 base.

    Additional Packages: These additional packages are installed to enhance the user experience and provide useful tools for the system and Proxmox environment.

    Bridge Creation: Facilitates network configuration by creating a bridge named vmbr0. You can choose to configure manually or use DHCP.
