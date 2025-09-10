[![Version](https://img.shields.io/badge/Version-1.0.1-red.svg)](version) [![License](https://img.shields.io/badge/License-BSD--Clause_3-green.svg)](LICENSE) [![Readme em PortuguГЄs e InglГЄs](https://img.shields.io/badge/README-en%2Fpt--br-blue)](#)

```bash
                                                                  _               
             _ __  _ __ _____  ___ __ ___   _____  __    ___  ___| |_ _   _ _ __  
            | '_ \| '__/ _ \ \/ / '_ ` _ \ / _ \ \/ /   / __|/ _ \ __| | | | '_ \ 
            | |_) | | | (_) >  <| | | | | | (_) >  <    \__ \  __/ |_| |_| | |_) |
            | .__/|_|  \___/_/\_\_| |_| |_|\___/_/\_\___|___/\___|\__|\__,_| .__/ 
            |_|                                    |_____|                 |_|     v1.0.1  
```

[![Language](https://img.shields.io/badge/рџЊЋ-English:-blue)](#)

# Proxmox VE Installer on Debian 13 Trixie

This setup/script automates the installation of Proxmox on Debian 12 and the creation of a bridge to facilitate network configuration.

**Note: This script is designed to run on a Debian 13 system. Make sure to have superuser permissions before executing the script.**

## Requirements

- Installed Debian 13 Trixie
- Superuser permissions
  ```bash
  su root
  ```
- Installed Git
  ```bash
  apt install git
  ```
- (Important) Clone the repository from the directory:

  ```bash
   cd /
  ```

## Usage Instructions

1. Clone the repository to your Debian 13 system.
```bash
# With git already installed on your machine, clone the repository
git clone https://github.com/pixmagit/pve_deb13.git

# Access the downloaded folder with the 'cd' command
cd /pve_deb13
```
2. Make the script executable.
```bash
# Give execution permission to the setup
chmod +x ./setup
```

3. Run the setup.
```bash
./setup
```

## Additional Packages

The script installs some additional packages to enhance the experience and provide additional functionalities. The packages include:

1. **'sudo':** Essential tool to grant administrative permissions to the selected user.
2. **'nala':** An application that enhances the graphical interface of 'apt'.
3. **'neofetch':** A system information display tool with a colorful and user-friendly interface.
4. **'net-tools':** A classic set of network utilities, such as ifconfig and route.
5. **'nmap':** A powerful network scanning and security auditing tool.

Make sure to review the official documentation for each package for more details on their functionalities.

## Features

1. **Proxmox Installation:** The script automatically installs Proxmox on the Debian 13 base.

2. **Additional Packages:** These additional packages are installed to enhance the user experience and provide useful tools for the system and Proxmox environment.

3. **Bridge Creation:** Facilitates network configuration by creating a bridge named vmbr0. You can choose to configure manually or use DHCP.

## Updates and Support

For support or to report issues, [ open an issue](https://github.com/mathewalves/Proxmox-Debian12/issues).

## License
This script is distributed under the [BSD 3-Clause License](https://opensource.org/licenses/BSD-3-Clause).

## Acknowledgments

Thank you for using the Proxmox Installation Script on Debian 13
If you come across any improvements or would like to contribute, feel free to create a pull request. Your contributions are welcome to enhance this script.

We appreciate your participation in the community and your contribution to the ongoing development of this script.

**Enjoy Proxmox!** рџљЂ

---

[![Language](https://img.shields.io/badge/рџ‡§рџ‡·-PT--BR:-green)](#)


# Instalador do Proxmox VE no Debian 13 Trixie

Este setup/script automatiza a instalaГ§ГЈo do Proxmox sobre o Debian 13 e a criaГ§ГЈo da bridge para facilitar a configuraГ§ГЈo de redes.

**Nota: Este script foi projetado para ser executado em um sistema Debian 13. Certifique-se de ter permissГµes de superusuГЎrio antes de executar o script.**

## Requisitos

- Debian 13 Trixie instalado
- PermissГµes de superusuГЎrio
  ```bash
  su root
  ```
- Git instalado
  ```bash
  apt install git
  ```
- (Importante) Clonar o repositГіrio apartir do diretГіrio:

  ```bash
   cd /
  ```

## InstruГ§Гµes de Uso

1. Clone o repositГіrio para o seu sistema Debian 13.
```bash
# Com o git jГЎ instalado na sua mГЎquina clone o repositГіrio
git clone https://github.com/pixmagit/pve_deb13.git

# Acesse a pasta baixada com o comando 'cd'
cd /pve_deb13
```
2. Torne o script executГЎvel.
```bash
# DГЎ permissГЈo de execuГ§ГЈo para o setup
chmod +x ./setup
```

3. Execute o setup.
```bash
./setup
```

## Pacotes Adicionais

O script instala alguns pacotes adicionais para melhorar a experiГЄncia e fornecer funcionalidades adicionais. Os pacotes incluem:

1. **'sudo':** Ferramenta essencial para conceder permissГµes administrativas ao usuГЎrio selecionado.
2. **'nala':** Uma aplicaГ§ГЈo que melhora a interface grГЎfica do 'apt'.
3. **'neofetch':** Uma ferramenta de exibiГ§ГЈo de informaГ§Гµes do sistema com uma interface colorida e amigГЎvel.
4. **'net-tools':** Conjunto de utilitГЎrios clГЎssicos de rede, como ifconfig e route.
5. **'nmap':** Uma poderosa ferramenta de exploraГ§ГЈo de rede e auditoria de seguranГ§a.

Certifique-se de revisar a documentaГ§ГЈo oficial de cada pacote para obter mais detalhes sobre suas funcionalidades.

## Funcionalidades

1. **InstalaГ§ГЈo do Proxmox:** O script instala automaticamente o Proxmox sobre a base do Debian 12.

2. **Pacotes Adicionais:** Esses pacotes adicionais sГЈo instalados para melhorar a experiГЄncia do usuГЎrio e fornecer ferramentas Гєteis para o sistema e para o ambiente Proxmox.

3. **CriaГ§ГЈo de Bridge:** Facilita a configuraГ§ГЈo de redes criando uma bridge chamada `vmbr0`. VocГЄ pode optar por configurar manualmente ou usar DHCP.

## AtualizaГ§Гµes e Suporte

Para obter suporte ou relatar problemas, [abra uma issue](https://github.com/mathewalves/Proxmox-Debian12/issues).

## LicenГ§a

Este script Г© distribuГ­do sob a licenГ§a [BSD 3-Clause](https://opensource.org/licenses/BSD-3-Clause).

## Agradecimentos

Se vocГЄ identificar oportunidades de melhoria ou quiser contribuir, sinta-se Г  vontade para criar um pull request. Estamos abertos a colaboraГ§Гµes para aprimorar esta ferramenta.

Agradecemos por fazer parte da comunidade e por contribuir para o desenvolvimento contГ­nuo deste script.

**Divirta-se com o Proxmox!** рџљЂ
