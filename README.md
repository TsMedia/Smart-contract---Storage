��#   S m a r t - c o n t r a c t - - - S t o r a g e  
 
This code is from Block Chain fundamentals > Plural insights

Resources:
Metamask;
Node.js;
Chocolatey - Windows Package manager;
testrpc;
Truffle;

### Environment:

Set-ExecutionPolicy -ExecutionPolicy RemoteSigned

choco install git -params "GitAndUnixToolsOnPath"

git config --system http.sslverify false

npm install --global --production windows-build-tools

npm install -g ethereumjs-testrpc

npm install -g truffle
