# Web3.py in macOS
### Python

#### Dependencies and commands to run Web3.py and TestRPCProvider:

~~~~
brew tap ethereum/ethereum
brew install solidity
brew install pkg-config libffi autoconf automake libtool openssl gcc
export LIBRARY_PATH=$LIBRARY_PATH:/usr/local/opt/openssl/lib/
pip3 install py-solc
pip3 install eth-testrpc
~~~~

###### Note: I do not know if all depencies in `brew install pkg-config libffi autoconf automake libtool openssl gcc` are required. However, those are the modules that I had installed and managed to run Web3 in Python environment
##### 
---
