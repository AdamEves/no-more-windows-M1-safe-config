# no-more-windows-M1-safe-config

Okay short and sweet.

Throw away your PC. It's garbage, no anti-detect will save your life. Forget it will ever happen on Windows, it's already as broken as a window pane.

Steps:

• Buy an M1 mac
• Let me get your setup with a Proton Account with VPN. Use that login on whatever you need, then go to Hushed - 2nd Number - Website note phone app version. Buy a phone number for $25.
• But a VPN Router, something like an Asus ROG, set it up at your facility. I'll give you a .ovpn to load into the VPN settings, use your devices under VPN.

Setup your new M1 Mac:

• Create an Apple ID with that Protonmail Premium I give you, Verify the account with the Hushed number, Select your VPN router Wi-Fi. New computer is clean and secure from day 1.
• Open FileVault, encrypt the computer. Not only will this new M1 be unbootable with the new boot EFI system, the drives are encrypted by FileVault. Use Disk Utility to encrypt external drives. Get Parallels and try using Kali Linux on an external for fun too, it runs beautiful on M1.
• Open Settings, go to Wi-Fi, select to change your MAC address. Built in Anti-Detect.
• Install Homebrew, info you can find just by searching.
• In terminal: sudo brew install tor
• Download Tor browser if you really want, doesn't matter.
• Download this script or just copy-paste and name the file tor.sh in text edit:
https://gist.github.com/jakejarvis/544ef4c89f4937879693cf91ad06485c
• to execute it go in Terminal, change directory with:
cd ~/Downloads
sudo chmod +x tor.sh
sudo sh tor.sh
Re-run this at startup, or just keep using your Router VPN without fail, or just use when you need Tor browser at the times you need.

Literally this is flawless, and will never be beat by a Window system, ever.
