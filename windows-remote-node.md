## Create A Windows Remote Node

This guide will explain how to run a remote node on your Windows device.

### Downloading Files

The first step to get your node started is to download the newest client release versioin here: https://github.com/CelestialCash/Celestial/releases/. Select the Windows.zip file and it should download it. Then just unzip the files.

### Starting The Node

To start a remote node first navigate to your command prompt and locate to the Windows folder you just unziped. To do this type ``cd`` then add a space and finally type the path to the folder. For example ``cd C:\Users\MyName\Downloads\UnzippedWindowsFolder``. Next type ``Celestiald.exe --rpc-bind-ip 0.0.0.0``. Wait for it to sync then you can have others connect to it. The ``0.0.0.0`` value should stay ``0.0.0.0`` no matter your IP.

### Having People Connect

People can connect using your public IP and the port 18236. For example people could connect to ``164.13.45.78:18236`` that IP is completely made up but is an example. You could also point a domain to your IP address and have people connect to something like ``domain.com:18236``.

### Setting A Fee

To have people pay a fee for using your node add the following to the Celestiald.exe command ``--fee-address`` and ``--fee-amount``. A full command example could look like:
```
Celestiald.exe --rpc-bind-ip 0.0.0.0 --fee-address CNAVFknVYi8J9nfVCexed9RTUVcGEFxinPPUWchJN6GQGdydAxYdXgBWcwt57ygc6Khr6LKaEdjZ3E8FD8oNz1J457DkkvW --fee-amount 1
```
This command would allow remote connection and have people pay 1 CELC as a fee to the wallet address ``CNAVFknVYi8J9nfVCexed9RTUVcGEFxinPPUWchJN6GQGdydAxYdXgBWcwt57ygc6Khr6LKaEdjZ3E8FD8oNz1J457DkkvW``.