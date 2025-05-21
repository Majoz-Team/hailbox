[![Docker Official](https://img.shields.io/badge/Docker-Official-blue?logo=docker&logoColor=white)](https://www.docker.com)
![Logo](.ignore/logo.png)

###                    **2025** * Hailbox Project
###          * Majoz Team Security Project - Copyright (C) 2025

## Disclaimer
* This project is intentionally vulnerable and designed for educational and testing purposes only. It should only be used in **controlled environments** and with appropriate authorization. The author is **not responsible** for any misuse, damage, or legal consequences resulting from the use of this project.

* **By using this project, you agree to take full responsibility for your actions and acknowledge that ethical hacking principles must be followed. Unauthorized testing or deployment of this project outside of permitted environments may violate local laws and regulations. Use at your own risk.**

##    1. Terms of Use & Redistribution

* This project is officially provided and maintained by **Majoz Team**. By using, modifying, or redistributing this project, you agree to the following terms:

### 1. Authorized Use  
This project is designed **exclusively** for controlled sandbox environments and **must not** be deployed, tested, or executed outside of such environments. Any attempt to apply, modify, or utilize the sandbox in unauthorized contexts **is strictly prohibited** and may violate applicable legal and ethical guidelines.

### 2. Responsible Redistribution  
Redistribution of this project is permitted **only if** the original disclaimers, terms of use, and licensing information remain intact. Any forks or modified versions **must also include these terms in their entirety**, ensuring users are aware of the limitations, ethical guidelines, and legal restrictions associated with the software.

### 3. Prohibition of Unauthorized Replication  
Direct replication, cloning, or derivation of this project **without explicit authorization** from **Majoz Team** is strictly prohibited. Unauthorized copies that do not adhere to these terms **will be considered illegal** and may be subject to removal or legal action. The organization maintains full authority over all derivatives, including forks, modifications, and adaptations.

### 4. Organizational Rights & Oversight  
**Majoz Team** retains **exclusive rights** over this project, its distribution, and all official derivatives. Any forks or adaptations must **comply with these terms** and may be subject to oversight by the organization to ensure ethical and legal compliance. Non-compliant derivatives **may be removed** at the discretion of **Majoz Team**.

### 5. Legal & Ethical Considerations  
Failure to adhere to these terms may result in **access restrictions, removal of unauthorized copies, and where applicable, legal enforcement**. Users and contributors are expected to operate **within ethical hacking principles** and respect all applicable laws governing cybersecurity and software distribution.

By proceeding with the use, modification, or redistribution of this project, you acknowledge and accept these terms in full.

##    2.  Acknowledgments

* We appreciate all contributions and efforts made toward this project. Below are the individuals who have directly contributed to its development.

### Contributors

#### 1. **Mr. Maofox**  
- **Role:** Project creator, main developer, and architect of the sandbox system.  
- **GitHub:** [![GitHub](https://img.shields.io/badge/GitHub-Mr.%20Maofox-blue?logo=github)](https://github.com/mrdtmfx/)  
- **Discord:** [![Discord](https://img.shields.io/badge/Discord-Mr.%20Maofox-blue?logo=discord)]()

---

This project would not be possible without the dedication and expertise of our contributors. If you would like to support or collaborate, feel free to check our **Contributing Guidelines**.

##    3. How to Build

To compile and run this project, follow the steps below.

### Required Dependencies:
Ensure you have the following installed:
- **CMake** – Build system generator.
- **Cargo + Rustc** – Rust package manager and compiler.
- **Docker** – Used for containerized sandbox initialization.
- **GCC / G++** – Standard C/C++ compiler.
- **Clang** – Alternative C/C++ compiler.
- **Git** – Version control system.
- **Visual Studio Code** – Required for compilation and development.

### Installation Guide:

#### **Linux (Debian/Ubuntu)**
```sh
sudo apt update
sudo apt install -y cmake cargo rustc docker.io gcc g++ clang git make
```

#### **Linux (Arch & derived)**
```sh
sudo pacman -Syu cmake cargo rustc docker gcc g++ clang git make
```

#### **Windows (via Chocolatey)**
```powershell
choco install cmake cargo rust docker-cli gcc clang git make vscode
```

### Building the Project
* Once dependencies are installed, clone the repository and build the project using `make`:
```sh
git clone https://github.com/Majoz-Team/hailbox.git
cd hailbox
make
```

### Running the Setup
* After compilation, the Hailbox setuper can be started with:
./build/bin/hailbox