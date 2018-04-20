## openvpn-install
OpenVPN [road warrior](http://en.wikipedia.org/wiki/Road_warrior_%28computing%29) installer for Debian, Ubuntu and CentOS.

This script will let you setup your own VPN server on DigitalOcean Droplets in no more than a minute, even if you haven't used OpenVPN before. It has been designed to be as unobtrusive and universal as possible. Thanks to Nyr for the original script (Nyr's Github Repository)[https://github.com/Nyr/openvpn-install]

### Installation
Clone the repository and run the script as shown below.

**NOTE: Before running the script, ensure your DigitalOcean droplet is setup with Private Networking to enable `eth1` interface:**

```
git clone https://github.com/muffycompo/openvpn-install
cd openvpn-install
./openvpn-install.sh
```

Once it ends, you can run it again to add more users, remove some of them or even completely uninstall OpenVPN.
