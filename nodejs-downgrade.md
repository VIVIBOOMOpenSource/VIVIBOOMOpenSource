# Downgrading Node.js to Version 14

## Installation Guide using Node Version Manager (nvm)

### 1. Install nvm

#### For macOS and Linux:
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
```
Close and reopen your terminal for the changes to take effect.

#### For Windows:
- Download the installer: Visit the official nvm-windows GitHub repository and download the latest installer.
- Run the installer and follow the on-screen instructions.
- Install Node.js Version 14: Once nvm is installed, you can install Node.js version 14 using the following command:
```Bash
nvm install 14
```
_Use code with caution._

### 2. Switch to Node.js Version 14
To use the newly installed Node.js version 14, switch to it using:
```Bash
nvm use 14
```

### 3. Verify the Node.js Version
To confirm the version change, run:
```Bash
node -v
```

This should output v14.x.x.
