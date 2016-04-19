# StartWallet Rescue

A tool for retrieving coins from [StartWallet.com](http://startwallet.com). This tool will take your Master Private Key and retrieve coins derived from it, sending them to an address of your choice.

![StartWallet Rescue in use](http://i.giphy.com/xTiQyp9qeXRCbH2tdC.gif)

## Master Private Key

To retrieve your coins you will need your **Master Private Key**. This is a long string beginning with `xprv` that you can find in StartWallet by follwing the instructions below:

1. Navigate to 'Home' and click on the 'Settings' button, to the right of your wallet.

![Navigate to 'Home' and click on the 'Settings' button, to the right of your wallet](http://i.imgur.com/j1evgBT.png)

2. Click 'Show advanced options', at the bottom-left of the page.

![Click 'Show advanced options', at the bottom-left of the page](http://i.imgur.com/Ck8P3pq.png)

3. Click the 'Show' button, below 'Master Private Key'.

![Click the 'Show' button, below 'Master Private Key'](http://i.imgur.com/wHfDVQP.png)

## Retrieving Coins

1. Navigate to [startcoin-developers.github.io/startwallet-rescue/](https://startcoin-developers.github.io/startwallet-rescue/) or [download](https://github.com/startcoin-developers/startwallet-rescue/archive/master.zip) the tool and open `index.html`.

2. Enter your Master Private Key, obtained as-per the instructions above, in the first box.

3. Enter a **StartCOIN address** that you own in the second box.

4. Click the **Rescue Coins** button.

5. Wait for the tool to scan your addresses. You can see how many addresses it has found, alongside the total balance, above the progress bar.

6. When the tool has finished scanning it will transmit your transaction and give you a **TXID**. Your coins will be available after 6 confirmations.

If you want to view the addresses and their balances click the **View Addresses** button. You can also run the tool without specifying a destination address by using the **Scan only** option in the settings.
