# Beet-Work

This is not an official Beetlecoin GITHUB or official BEETLECOIN link https://github.com/beetledev/ is the official link. Use this unfinished script at your own discretion. 

THIS IS FOR A LINUX INSTALLATION OF BEETLECOIN WALLET/MASTERNODE SETUP. 
**SIDE NOTE** FOR ALL THOSE WHO ARE WANTING INSTRUCTIONS FOR A WINDOWS MASTERNODE GO TO THE BEETLECOIN WEBSITE https://beetlecoin.io LINK FOUND HERE >> https://beetlecoin.io/wp-content/uploads/2019/06/Hot-Masternode-Setup-Windows.pdf FOR THE MULTIPLE NODE INSTRUCTIONS A TEAM MEMBER HAS COMPILED A YOUTUBE VIDEO FOR THIS. https://www.youtube.com/watch?v=R3ax-KBINbc



This is one of the team member's personal work to help the Beetlecoin Community. Always check with the discord https://discord.gg/gQhdCaJ community before downloading anything for your wallet.

This script is a modified WORK IN PROGRESS script for the official beetlecoin script found at the following wget link:

https://raw.githubusercontent.com/beetledev/Snapshot/master/install_multi_beetlecoin.sh

This script is modified to migrate the beetlecoin wallets from soon to be depreceated Ubuntu 16.04 to the newer release 18.04 Bionic. Ubuntu 16.04 will be depreceated in 2020, the wallets will still work as normal but a lot less support will be available to this verison of Ubuntu. 

This script also uses sepc256k1 (https://github.com/bitcoin-core/secp256k1.git) to quickly compile the wallet. The script offers a command to remove this from your VPS afterwards. While I enjoy sepc256k1 as a nice shortcut, I suggest removing it if you have no idea what it is.

This script mixes the installation script with the multinode script and will ask how many masternodes you wish to install. you may choose 1-64. If you know you will be creating some in the future, go ahead and give yourself a few installs ahead of time, running an empty wallet will not affect anything that much. It will save you time in the future.

This is an install for the hot/cold wallet for VPS found in instructions on the https://beetlecoin.io website at https://beetlecoin.io/wp-content/uploads/2019/08/Hot-and-Cold-Wallet.pdf . Read and familiarize yourself with the installation instructions first. 

DO NOT TRY TO JUMP INTO RUNNING MULTIPLE MASTERNODES IF YOU DO NOT KNOW HOW TO RUN 1 FIRST... We will help you at the beetlecoin discord (see above for link) but it is very very frustrating to teach both lessons at the same time. Don't be greedy, learn to run, manage and update a single wallet first THEN try for multiple nodes.

FINAL NOTES. This is unfinished as of 10/9/2019. If updates are posted, use those. The ./startNodes.sh and ./stopNodes.sh functions have not been finalized. They still call for 16.04 dependencies, so in order to start the wallet(s) you need to reboot the vps after installation.
