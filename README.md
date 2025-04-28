# 🌐 DNS Enumerator README 🚀

Welcome to DNS Enumerator by Cipher Squid! 🔒
A C-based tool designed to scan hostnames, resolve IP addresses (IPv4/IPv6), and check for common admin directories (e.g., /admin, /login, /dashboard). Results are saved in scan_results.txt. Use responsibly! ⚠️

# 📋 Features

🌍 Resolve Hostnames to IPs
Resolves hostnames to both IPv4 and IPv6 addresses.

🔍 Scan for Common Admin Directories
Checks for standard admin paths like /admin, /login, and /dashboard.

💾 Save Results
Outputs the results to a file named scan_results.txt.

🎨 Colorful CLI
A hacker-style CLI interface for a smooth experience.

🖱️ Simple Input
Enter a hostname to scan or type exit to quit.

# 🛠️ Prerequisites

OS: Linux or macOS (Windows users should use WSL or Cygwin).

Compiler: gcc

Install on Ubuntu/Debian: sudo apt-get install build-essential

Install on macOS: xcode-select --install

Network Access: Required for DNS queries and HTTP checks.

Git: Required to clone the repository

Install Git: sudo apt-get install git or use the equivalent package manager for your OS.

# 📥 Installation & Usage

1. Clone the Repository 🐙

git clone https://github.com/ciphersquid666/DNS-ENUMERATOR.git

2. Navigate to the Directory 📂

cd DNS-ENUMERATOR

3. Compile the Code 🔨

gcc -o dns_enumerator dns_enumerator.c

4. Make the Binary Executable 🔑

chmod +x dns_enumerator

5. Run the Program 🚀

./dns_enumerator


---

# 🎮 How to Use

1. Launch the program:
Run ./dns_enumerator to start the program.


2. Enter a hostname:
You'll be prompted to input a hostname to scan (e.g., example.com). Type the hostname and press Enter.
You can type exit to quit.


3. View Results:
The program will display the IP address details and found admin directories (if any) in the terminal. 📡


4. Check Saved Results:
All scan results will be saved in the file scan_results.txt for later review. 📄




---

# ⚠️ Notes

Ethical Use:
Only scan domains you own or have explicit permission to test. Unauthorized scanning can violate laws or terms of service agreements. 🚨



---

# 🤝 Contributing

Found a bug or want to add new features?

Fork the repo.

Make changes.

Submit a pull request!


Let's make DNS Enumerator even better together! 🌟


---

# Happy Scanning! 🎉

## Created by Cipher Squid 🦑 | Licensed under MIT
