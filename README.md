# base987
Fetching Wallet Balances on Base (Python + Java) Python
balance = w3.eth.get_balance("0xYourWallet")
print("ETH:", w3.from_wei(balance, "ether"))
Java
EthGetBalance bal = web3.ethGetBalance(wallet, DefaultBlockParameterName.LATEST).send();
System.out.println(bal.getBalance());
