1.nextjs-ethers-metamask-connect-24
This is a minimalistic project to show us how we can connect to metamask using ethersjs in nextjs / react.

2.Requirements
git
Nodejs & npm
Yarn
Metamask
vscode

Install git:
```bash 
sudo apt install git-all
```

Install nodejs & npm: 
```bash 
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
nvm install node
```

Install yarn:
```bash
 npm install --global yarn
```

Install vscode:
download and install the .deb package from the official Microsoft website, then run:
```bash 
sudo apt install ./<file>.deb
```

3.Creat next.js app
```bash
 yarn create next-app nextjs-ethers-metamask-connect-24
```

4.Run next.js app 
```bash 
yarn dev
```
ctrl + c stop server.

5.Install ethers.js 
```bash 
yarn add ethers@^5.7.2
```
or uninstall
```bash
yarn remove ethers
```

6.edit pages to realize project
I have deployed and approved SimpleStorage contract on sepolia for testing.



