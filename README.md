## openvpn-install
OpenVPN [road warrior](http://en.wikipedia.org/wiki/Road_warrior_%28computing%29) installer for Debian, Ubuntu and CentOS.

This script will let you setup your own VPN server in no more than a minute, even if you haven't used OpenVPN before. It has been designed to be as unobtrusive and universal as possible.

###Fork
This project is a fork of Nyr's [openvpn-install](https://github.com/Nyr/openvpn-install).

The following changes have been made :
- choice of the protocol
- choice to disable server logs

###Installation
Run the script and follow the assistant:

`wget https://git.io/vaMxQ --no-check-certificate -O openvpn-install.sh && bash openvpn-install.sh`

Once it ends, you can run it again to add more users, remove some of them or even completely uninstall OpenVPN.