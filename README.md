# node-nvm-macos-installation
This repository provides a step-by-step guide on installing Node.js and NVM (Node Version Manager) on Mac/macOS. It includes essential terminal commands, version management, and switching between different Node.js versions.


# 🛠️ Node.js and NVM Installation on macOS

This repository provides a step-by-step guide on installing **Node.js** and **NVM (Node Version Manager)** on macOS.  
It includes essential terminal commands, version management, and switching between different Node.js versions.

---

## 📌 Prerequisites

Ensure you have:
✔️ A macOS system  
✔️ Terminal access  

---

## 🚀 Installation Steps  

### 1️⃣ Open Terminal and Verify Your Current Directory  
```sh
pwd      # Print current working directory
ls -al   # List all files (including hidden ones)

2️⃣ Create or Edit the .zshrc File

touch ~/.zshrc  # Create the file if it doesn't exist

3️⃣ Install NVM (Node Version Manager)

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.2/install.sh | bash

4️⃣ Load NVM in the Terminal

source ~/.zshrc  # Apply changes to the current session

5️⃣ Verify NVM Installation

nvm --version  # Check if NVM is installed correctly

6️⃣ List Available Node.js Versions

nvm ls-remote  # Displays all available Node.js versions

7️⃣ Install a Specific Node.js Version

nvm install <node_version>  # Replace <node_version> with the desired version

🔹 Example:

nvm install 18.17.1  # Installs Node.js version 18.17.1

🔹 To install the latest stable version:

nvm install node

8️⃣ Verify Node.js and npm Installation

node --version  # Check Node.js version
npm --version   # Check npm version

9️⃣ List Installed Node.js Versions

nvm ls  # Show installed Node.js versions

🔟 Switch Between Node.js Versions

nvm use <node_version>  # Switch to a specific version

🔹 Example:

nvm use 18.17.1



⸻

📌 Additional Commands

✅ Set a Default Node.js Version

nvm alias default <node_version>  # Make a version default

🔹 Example:

nvm alias default 18.17.1

❌ Uninstall a Node.js Version

nvm uninstall <node_version>  # Remove a specific version



⸻

🤝 Contributing

Feel free to fork this repository and submit pull requests!

⸻

📜 License

This project is licensed under the MIT License.

⸻

🔗 Connect with Me

📧 Email: mhdd24.rafi@gmail.com
💻 GitHub: Mhdd-24

⸻

🚀 Push Updated README to GitHub