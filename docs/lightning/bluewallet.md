# Blue Wallet (LND Hub)

The first step to using Blue Wallet with your myNode is enalbling LND Hub. The can be done by clicking the "Enable" button underneath the LND Hub icon on the main page.

<center>
  <figure>
    <img src="/images/lightning/bluewallet-1.png" style="width: 500px">
  </figure>
</center>

Next, you can click on the "LND Hub" button and view the LND Hub web interface. This is not required.

<center>
  <figure>
    <img src="/images/lightning/bluewallet-2.png" style="width: 500px">
  </figure>
</center>

Now that LND Hub is running, install Blue Wallet on your mobile device and connect it to your myNode!

From the mobile wallet, click on the settings icon and then click on Lightning Settings. On this screen, enter the URL to your myNode device on port 3000 and click Save. Alternatively, you can scan a QR code according to the [pairing instructions](/lightning/pairing-wallets).

<center>
  <figure>
    <img src="/images/lightning/bluewallet-3.png" class="app_screenshot">
  </figure>
</center>

Any new wallets added to Blue Wallet will be tied to your myNode device!

Important notes regarding BlueWallet lightning wallets connected to youre myNode device:
1. They will not see your lightning sats in your channels.
2. If you receive sats into your wallet, those sats will be added into your overall lightning sats balance on your node in your channels, but your BlueWallet will only be able to control what it has received.
