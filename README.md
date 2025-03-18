# node-nvm-macos-installation
This repository provides a step-by-step guide on installing Node.js and NVM (Node Version Manager) on Mac/macOS. It includes essential terminal commands, version management, and switching between different Node.js versions.

Here’s how you can document this properly in a README.md file for your GitHub repository:

Steps:
	1.	Create a GitHub Repository
	•	Go to GitHub and create a new repository.
	•	Give it a relevant name, e.g., node-nvm-install-macos.
	2.	Clone the Repository Locally

git clone https://github.com/your-username/node-nvm-install-macos.git
cd node-nvm-install-macos


	3.	Open the Project in VS Code

code .


	4.	Create a README File
	•	If a README.md file doesn’t exist, create it:

touch README.md


	•	Open it in VS Code and add the following content:

⸻

📌 README.md File Content:

# How to Install Node.js and NVM on macOS

This guide provides step-by-step instructions on installing Node.js and NVM (Node Version Manager) on macOS using the terminal.

## 📌 Prerequisites
- macOS
- Terminal access

## 🚀 Installation Steps

### 1️⃣ Open Terminal and Verify Your Directory
```sh
pwd
ls -al

2️⃣ Create or Edit .zshrc File (if not exists)

touch ~/.zshrc

3️⃣ Install NVM (Node Version Manager)

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.2/install.sh | bash

4️⃣ Load NVM in Your Terminal Session

source ~/.zshrc

5️⃣ Verify NVM Installation

nvm --version

6️⃣ List Available Node.js Versions

nvm ls-remote

7️⃣ Install a Specific Node.js Version

nvm install <node_version>

Replace <node_version> with a specific version, e.g., 18.17.1 or use node to install the latest version.

8️⃣ Verify Node.js Installation

node --version
npm --version

9️⃣ List Installed Node.js Versions

nvm ls

🔟 Switch Between Node.js Versions

nvm use <node_version>

Example:

nvm use 18.17.1

🎯 Notes
	•	Always run source ~/.zshrc after installing NVM.
	•	Use nvm alias default <node_version> to set a default Node.js version.
	•	To uninstall a Node.js version:

nvm uninstall <node_version>



🤝 Contributing

Feel free to fork this repository and submit pull requests!

📜 License

This project is licensed under the MIT License.

---

5. **Commit and Push the Changes to GitHub**
```sh
git add README.md
git commit -m "Added installation guide for Node.js and NVM on macOS"
git push origin main

Now your repository will have a detailed README.md file with clear steps! 🚀