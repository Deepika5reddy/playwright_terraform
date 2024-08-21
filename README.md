# playwright_terraform
integration of playwright and terraform
Setup:

npm install

# Check node version (Playwright requires Node.js 14 or higher)
$ node --version

# Use higher node version if the version is NOT 14 or higher (ex v18)
$ nvm use 18

# Install Playwright
$  npm install @playwright/test                                              ║
║   npm init playwright@latesty  


sudo apt-get update && sudo apt-get install -y gnupg software-properties-commonsudo apt-get install terraform

sudo apt-get update && sudo apt-get install -y apt-transport-https
curl -fsSL https://apt.releases.hashicorp.com/gpg | sudo apt-key add -
sudo apt-add-repository "deb [arch=amd64] https://apt.releases.hashicorp.com $(lsb_release -cs) main"
sudo apt-get update
sudo apt-get install terraform