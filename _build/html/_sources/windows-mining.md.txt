## Windows Mining

This guide will explain how to mine Celestial on a Windows device.

### Downloading Files

The first step to get started mining is to download the newest client release versioin here: https://github.com/CelestialCash/Celestial/releases/. Select the Windows.zip file and it should download it. Then just unzip the files.

### Option #1: Using A .bat File

The first and easiest option is to use the bat file included. If you want to just start mining without syncing the blockchain or starting a node open the files titled miner-start-remote-daemon.bat replace the wallet address with your own then save and exit. Finally double click the miner-start-remote-daemon.bat file. If you are new to mining you can stop here and enjoy mining. If you want to use a node that is not the default replace "celc.pubnodes.com:18236" with the url of the node you want. If you have a local node that runs on your computer open the file titled miner-start.bat in a text editor and replace the wallet address in there with your own then save and exit. If you want to create a local node and do not know how check out [Windows Local Node](./windows-node).

### Option #2: Using Command Prompt

Locate the Celestial directory in the command prompt and make sure you are running as an admin. 

If you do not want to use a local node type something like this:
```
miner.exe --address CJH7776JGgXfJSD44oNUPuQTAsdLk6nMm2tQc7mFShVxQcJm7oUv8Pv8Q1oNNuN8MBDmdLd1y2dygPTnVCGkRRZbNbyBnfe --log-level 3 --daemon-host celc.pubnodes.com:18236
```
You can also replace ``celc.pubnodes.com:18236`` with another url if you want to use someone elses.
If you want to create your own a local node check out [Windows Remote Node](./windows-remote-node).

If you want to use a local node type type something like this:
```
miner.exe --address CJH7776JGgXfJSD44oNUPuQTAsdLk6nMm2tQc7mFShVxQcJm7oUv8Pv8Q1oNNuN8MBDmdLd1y2dygPTnVCGkRRZbNbyBnfe --log-level 3
```
If you do not know how to create a local node check out [Windows Local Node](./windows-local-node).

With either command replace the address with your own and press enter.

### Mining

Once you have started mining leave that window open for as long as you want to mine. When you close it, it will stop mining. You should get an update in the console with your hashrate every few minutes. When you find a block it will tell you in the mining window

### FAQ

**Q**: I am not finding blocks?
**A**: Celestial is a solo mining coin so it might take a while to find a block but this will happen to everyone so you won't actually be getting less profit then others with a similar hashrate. Also since Celestial is pool resistant people with mining farms won't get that much of an advantage because each of their CPU's are on their own.

**Q**: Can you add mining to the GUI Wallet?
**A**: Not at this time, I would like to keep mining and storage seperate.

**Q**: Is there going to be an easier mining system?
**A**: Yes I will be working on an easier system for mining in the next few weeks.
