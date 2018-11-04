## GUI Wallet Troubleshooting

This guide will give you somethings to try if you are having trouble with the GUI wallet before asking for help.

### Close Conflicting Programs

Sometimes the client files and gui wallet will interact poorly with each other. Luckily this is easy to fix. First make sure the gui wallet and zedwallet are turned off. Then open task manger (Windows), activity monitor (Mac), or your preferred monitoring software (Linux). Once you have your OS's montoring system open search for a program titled "service" and make sure to quit or force quit it. Finally you exit the monitoring and system and reopen the GUI Wallet. 

### Reimport Wallet File

Sometimes if you are using a new version of the GUI wallet with an old .wallet file the wallet file can go corrupt. This will cause incorrect info to be displayed. All you have to do to fix this is delete the .wallet file and then re-import the seeds or keys in the gui wallet. Once you do this wait for the wallet to sync and you should have the correct balance and info displayed.

### It Says I Can't Connect

This normally means you have set the gui wallet to use a local daemon and the daemon is not running or the node you are connected to is out of sync or down.
