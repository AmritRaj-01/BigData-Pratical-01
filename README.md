# BigData-Pratical-01
Practical: Installation of Java on Unix/Linux Machine (Without VirtualBox)

Step 1: Enable WSL
 1. Open PowerShell as Administrator
 2. Run the following command:
 wsl --install
 3. Restart your computer when prompted.
 4. After restart, choose Ubuntu or install it from the Microsoft Store.
 Step 2: Open Ubuntu (WSL)- Search for 'Ubuntu' in Start Menu and open it.- It will initialize and ask for a username and password.
 Step 3: Update the Package List
 Run the following command:
 sudo apt update
 Step 4: Install Java (OpenJDK 8 or 11)- For Java 8:
 sudo apt install openjdk-8-jdk -y- For Java 11:
 sudo apt install openjdk-11-jdk -y
 Step 5: Verify Java Installation
 Run:
 java -version
