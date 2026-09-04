<<<<<<< HEAD
# Hades OS

<div align="center">

[![Status](https://img.shields.io/badge/Status-In%20Development-orange?style=for-the-badge)](https://github.com/Tarcisiocyber/HadeOs)
[![Base](https://img.shields.io/badge/Base-CachyOS-blue?style=for-the-badge)](https://cachyos.org/)
[![Kernel](https://img.shields.io/badge/Kernel-Linux-yellow?style=for-the-badge)](https://www.kernel.org/)
[![Desktop](https://img.shields.io/badge/Desktop-KDE%20Plasma-blueviolet?style=for-the-badge)](https://kde.org/)
[![License](https://img.shields.io/badge/License-GPLv3-red?style=for-the-badge)](LICENSE)

**A modern Linux distribution focused on Cybersecurity**

[About](#about) • [Features](#features) • [Getting Started](#getting-started) • [Roadmap](#roadmap) • [Contributing](#contributing)
=======
# HadeOs
````markdown
<div align="center">

# 💀 Hades OS

### Uma distribuição Linux baseada em Arch Linux (CachyOS) focada em Cibersegurança

> **"Das profundezas do Submundo nasce um novo sistema operacional."**

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-orange?style=for-the-badge)
![Base](https://img.shields.io/badge/Base-CachyOS-blue?style=for-the-badge)
![Kernel](https://img.shields.io/badge/Kernel-Linux-yellow?style=for-the-badge)
![Desktop](https://img.shields.io/badge/Desktop-MATE-green?style=for-the-badge)
![Licença](https://img.shields.io/badge/Licença-GPLv3-red?style=for-the-badge)
>>>>>>> 49806e3 (tentado_corrigir_wifi)

</div>

---

<<<<<<< HEAD
## About

**Hades OS** is a modern Linux distribution based on **Arch Linux** and **CachyOS**, specifically designed for cybersecurity professionals, developers, and students. The project combines high performance with security-focused tools, providing a robust and customizable environment for advanced users.

The name *Hades*, inspired by the Greek god of the underworld, represents strength, stability, and depth—core values of this distribution.

### Key Characteristics

- **Performance-Oriented**: Built on CachyOS with optimized kernel configurations
- **Security-Focused**: Pre-configured with essential cybersecurity tools and hardened defaults
- **Developer-Friendly**: Complete development toolchain and package management via Pacman
- **Rolling Release**: Always up-to-date with the latest packages and improvements
- **Modern UI**: KDE Plasma desktop environment with powerful customization options
- **Highly Customizable**: Arch-based philosophy—you control every aspect of your system

---

## Features

- ✅ **CachyOS Foundation**: Leveraging the performance optimizations of CachyOS
- ✅ **Pacman Package Manager**: Fast and efficient dependency resolution
- ✅ **Rolling Release Model**: Continuous updates without major version jumps
- ✅ **Optimized Linux Kernel**: Performance and security enhancements
- ✅ **KDE Plasma Desktop**: Modern, powerful, and highly customizable graphical interface
- ✅ **Security Tools**: Pre-configured with essential cybersecurity utilities
- ✅ **Automation Scripts**: Streamline common tasks and deployments
- ✅ **Extensible Architecture**: Ready for custom tools and exclusive features

---

## System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| Processor | 64-bit | Modern multi-core processor |
| RAM | 4 GB | 8 GB or more |
| Storage | 20 GB | 40 GB SSD |
| Internet | Optional | Recommended for updates |

---

## Getting Started

### Building the ISO

#### Prerequisites

- Arch Linux or CachyOS system
- `archiso` package installed
- `mkarchiso` utility available
- Sudo privileges

#### Build Instructions

```bash
# Clone the repository
git clone https://github.com/Tarcisiocyber/HadeOs.git
cd HadeOs

# Build the ISO image (requires sudo)
sudo mkarchiso -v .

# The resulting ISO will be located in ./out/
```

#### Post-Build

The compiled ISO can be:
- Written to a USB drive using tools like `dd` or `balena-etcher`
- Used directly in virtual machines (VirtualBox, QEMU, etc.)
- Tested for proper boot and functionality

### Installation

1. Boot from the Hades OS ISO
2. Follow the guided installation process
3. Configure your system (networking, users, etc.)
4. Reboot and enjoy Hades OS

---

## Project Structure

```
HadeOs/
├── archiso/              # Archiso configuration files
├── configs/              # System configuration files
├── packages/             # Custom packages and PKGBUILD files
├── scripts/              # Automation and utility scripts
├── wallpapers/           # Default wallpapers and themes
├── assets/               # Project assets and resources
├── README.md             # This file
└── LICENSE               # GPL v3 License
=======
# 📖 Sobre o Projeto

O **Hades OS** é uma distribuição Linux baseada no **Arch Linux**, utilizando o **CachyOS** como base.

O projeto nasceu com o objetivo de oferecer um sistema operacional moderno, rápido e seguro para estudantes, desenvolvedores e profissionais da área de tecnologia, com foco especial em **Cibersegurança**, **Desenvolvimento de Software** e **Alto Desempenho**.

O nome **Hades** é inspirado no deus do submundo da mitologia grega, representando poder, estabilidade e profundidade.

---

# 🎯 Objetivos

- 🔐 Ambiente voltado para Cibersegurança
- ⚡ Alto desempenho
- 💻 Ferramentas para desenvolvimento
- 🐧 Experiência baseada no Arch Linux
- 🛠️ Sistema altamente personalizável
- 📚 Excelente para estudos e aprendizado

---

# ✨ Recursos

- ✅ Baseado no CachyOS
- ✅ Gerenciador de pacotes Pacman
- ✅ Rolling Release
- ✅ Kernel Linux otimizado
- ✅ Ambiente gráfico MATE
- ✅ Ferramentas próprias do Hades OS
- ✅ Scripts de automação
- ✅ Preparado para receber futuras funcionalidades exclusivas

---

# 📂 Estrutura do Projeto

```text
HadesOS
├── archiso/
├── configs/
├── packages/
├── scripts/
├── wallpapers/
├── assets/
└── README.md
```

---

# 🖥️ Requisitos

| Componente | Mínimo |
|------------|---------|
| Processador | 64 bits |
| Memória RAM | 4 GB |
| Armazenamento | 20 GB |
| Internet | Recomendado |

---

# 🚀 Compilando a ISO

```bash
git clone https://github.com/carvalhotarciso70-design/HadeOs.git

cd HadeOs

sudo mkarchiso -v .
>>>>>>> 49806e3 (tentado_corrigir_wifi)
```

---

<<<<<<< HEAD
## Roadmap

### Phase 1: Foundation ✓ In Progress
- [x] Initial project structure
- [x] CachyOS integration
- [ ] Visual identity and branding
- [ ] Custom theme and icon set
- [ ] Official repository setup
- [ ] Graphical installer

### Phase 2: Core Development
- [ ] Linux kernel customization
- [ ] Performance optimizations
- [ ] Custom boot messages
- [ ] Pre-configured security policies

### Phase 3: Tools & Ecosystem
- [ ] Hades Terminal (custom terminal emulator)
- [ ] Cybersecurity tools suite
- [ ] Automated deployment scripts
- [ ] Update center with UI
- [ ] Package repository management

### Phase 4: Community & Stability
- [ ] Official releases and versioning
- [ ] Community contributions framework
- [ ] Documentation and tutorials
- [ ] User forum and support channels

---

## Contributing

We welcome contributions from the community. Whether you're reporting bugs, suggesting features, or submitting code, your input is valuable.

### How to Contribute

1. **Fork** the repository
2. **Create a new branch** for your feature or bugfix
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Commit** your changes with clear messages
   ```bash
   git commit -m "Add: descriptive message about your changes"
   ```
4. **Push** to your fork
   ```bash
   git push origin feature/your-feature-name
   ```
5. **Submit a Pull Request** with a detailed description

### Development Guidelines

- Follow Arch Linux best practices
- Test all changes before submitting
- Maintain shell script quality (use ShellCheck)
- Document significant changes
- Keep commits atomic and well-described

For more details, see [CONTRIBUTING.md](CONTRIBUTING.md).

---

## Code of Conduct

This project adheres to a [Code of Conduct](CODE_OF_CONDUCT.md) to ensure a welcoming and inclusive community. We expect all participants to follow these guidelines.

---

## License

Hades OS is distributed under the **GNU General Public License v3.0**. See the [LICENSE](LICENSE) file for details.

This ensures the project remains free and open source for all users and contributors.

---

## Support & Community

- **Issues & Bug Reports**: [GitHub Issues](https://github.com/Tarcisiocyber/HadeOs/issues)
- **Discussions**: [GitHub Discussions](https://github.com/Tarcisiocyber/HadeOs/discussions)
- **Documentation**: Check the `/docs` directory for detailed guides

---

## Acknowledgments

- [CachyOS](https://cachyos.org/) for the performance-optimized base
- [Arch Linux](https://www.archlinux.org/) community and philosophy
- [KDE Plasma](https://kde.org/) for the powerful desktop environment
- All contributors and early adopters
=======
# 🛣️ Roadmap

## Sistema

- [x] Estrutura inicial
- [x] Base CachyOS
- [ ] Identidade visual
- [ ] Tema próprio
- [ ] Repositório oficial
- [ ] Instalador gráfico

## Kernel

- [ ] Personalização do Kernel Linux
- [ ] Melhorias de desempenho
- [ ] Mensagens personalizadas durante o boot

## Ferramentas

- [ ] Terminal Hades
- [ ] Ferramentas de Cibersegurança
- [ ] Scripts de automação
- [ ] Central de atualizações

---

# 🤝 Contribuindo

Contribuições são sempre bem-vindas.

Caso deseje colaborar:

1. Faça um Fork do projeto.
2. Crie uma nova Branch.
3. Faça suas alterações.
4. Envie um Pull Request.

---

# 📜 Licença

Este projeto é distribuído sob a licença **GPL v3**.
>>>>>>> 49806e3 (tentado_corrigir_wifi)

---

<div align="center">

<<<<<<< HEAD
### "From the depths of the underworld to your computer."

**Developed with dedication, open-source principles, and passion for Linux.**

⭐ If you find this project useful, please consider giving it a star on GitHub!

**[↑ Back to top](#hades-os)**

</div>
=======
# 💀 Hades OS

### "Do submundo para o seu computador."

**Desenvolvido com dedicação, código aberto e paixão pelo Linux.**

⭐ Se gostou do projeto, deixe uma estrela no GitHub!

</div>
````
>>>>>>> 49806e3 (tentado_corrigir_wifi)
