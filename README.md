# Blockchain with Python

## Dependencies


-PHP must be installed on your operating system (any version, 5 or 7). Don't worry, you will not need to know any PHP.


-You will need to clone the hd-wallet-derive tool.


-pip install bit Python Bitcoin library.


-web3.py Python Ethereum library,

-Generate a new 12 word mnemonic using hd-wallet-derive.

## Bitcoin Testnet transaction

Fund a BTCTEST address using a testnet faucet.

Process the transactions with the functions like below:

btc_acc = priv_key_account(BTCTEST, priv_key='cPATqqavHDLmsLX2Ej7SR5gvF3u9QJHLAC7taSQEcSuYucC6NGnG')
create_tx(BTCTEST,btc_acc,"mmPmSpyY8JFvr6JPF1xv4Xae5k7GwXvouS", 0.000001)
send_tx(BTCTEST, btc_acc, 'mfkGhz6m2tMwETDU6sgEHY2gp2qcuHaioH', 0.000001)

Use a block explorer to watch transactions on the address.
