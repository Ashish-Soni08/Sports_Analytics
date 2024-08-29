# Sports Analytics

## Setting Up the Development Environment

```bash
# Step 1 -> installs nvm (Node Version Manager)
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.0/install.sh | bash

# Step 2 
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"

# Step 3 -> download and install Node.js (you may need to restart the terminal)
nvm install 20

# Step 4
# verifies the right Node.js version is in the environment
node -v # should print `v20.17.0`

# verifies the right npm version is in the environment
npm -v # should print `10.8.2`

# Reference -> https://nodejs.org/en/download/package-manager
```

````bash
# 
cd ./Application_PhD_Sports_Analytics/

npm run dev
```
