## Linux Mining

This guide will explain how to mine Celestial on a Linux device.

### Downloading Files

The first step to get started mining is to download the newest client release versioin here: https://github.com/CelestialCash/Celestial/releases/. Select the Linux.zip file and it should download it. Then just unzip the files.

### Local Node

Locate the Celestial directory in your terminal.

First start the node using the following command ``./Celestiald``. Wait for it to finish syncing.

Next open a new tab and locate the Celestial directory again and this time type:
```
./miner --address CJH7776JGgXfJSD44oNUPuQTAsdLk6nMm2tQc7mFShVxQcJm7oUv8Pv8Q1oNNuN8MBDmdLd1y2dygPTnVCGkRRZbNbyBnfe --log-level 3
```
Replace the address above with your own and press enter. You have now started mining using a local node.

### Remote Node

Locate the Celestial directory in your terminal.

Next type the following command:
```
./miner --address CJH7776JGgXfJSD44oNUPuQTAsdLk6nMm2tQc7mFShVxQcJm7oUv8Pv8Q1oNNuN8MBDmdLd1y2dygPTnVCGkRRZbNbyBnfe --log-level 3 --daemon-host celc.cnknight.club:18236
```
Replace the address above with your own and press enter. You have now started mining using the node ``celc.cnknight.club:18236``. You can always replace that with a different node.

### Mining

Once you have started mining leave that window open for as long as you want to mine. When you close it, it will stop mining. You should get an update in the console with your hashrate every few minutes. When you find a block it will tell you in the mining window

### FAQ

**Q**: I am not finding blocks?
**A**: Celestial is a solo mining coin so it might take a while to find a block but this will happen to everyone so you won't actually be getting less profit then others with a similar hashrate. Also since Celestial is pool resistant people with mining farms won't get that much of an advantage because each of their CPU's are on their own.

**Q**: Can you add mining to the GUI Wallet?
**A**: Not at this time, I would like to keep mining and storage seperate.

**Q**: Is there going to be an easier mining system?
**A**: Yes I will be working on an easier system for mining in the next few weeks.
