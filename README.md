##To become a validator node, you need to meet several requirements:

1) You need to register your wallet on the Overgold network. To do this, go to https://overgold.app/auth/user-registration?lang=en and create your own wallet.
2) You need to purchase some OVG coins (even 1 coin will suffice) so that you can make transactions on the Overgold network. The coins must be in your wallet.
3) You need to purchase stOVG. The minimum amount to buy is 10,000 stOVG. You can do this in the "staking cabinet" at https://staking.overgold.app/auth/login.
4) After purchasing the coins, you need to send an email to info@overgold.com indicating your desire to become a node owner and your wallet.
5) After our support department reviews your application, we will ensure that you have the necessary amount of stOVG coins in your wallet, and then we will send you special staking coins and all necessary instructions for activating your node.

Before we send you the commands to activate the node, you need to perform its installation:

# Overgold node installation guide

How to install full overgold node?

## Init
Firstly, you have to choose binary file for your OS.
After downloading you should open folder with binary in terminal and run command:
`./ovgd init ovg-client`

When initiation process will be done, you have to download config files from `configs` folder in our repository.

## Configs 
After initiation, in your computer will appear folder `.ovgchain` in your home directory.
You should copy configs, which you downloaded in previos step, to `.ovgchain/configs` with replacement.
## Run node
Run the command `./ovgd start` in directory with binary file.

