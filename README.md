# WireGuard
<img src="https://www.wireguard.com/img/wireguard.svg">
WireGuard® is an extremely simple yet fast and modern VPN that utilizes state-of-the-art cryptography. It aims to be faster, simpler, leaner, and more useful than IPsec, while avoiding the massive headache. It intends to be considerably more performant than OpenVPN. WireGuard is designed as a general purpose VPN for running on embedded interfaces and super computers alike, fit for many different circumstances. Initially released for the Linux kernel, it is now cross-platform (Windows, macOS, BSD, iOS, Android) and widely deployable. It is currently under heavy development, but already it might be regarded as the most secure, easiest to use, and simplest VPN solution in the industry.


# Installation

# Wireguard Server
install wireguard server:
<pre>git clone https://github.com/strongpapazola/wireguard-server && cd ./wireguard-server
chmod +x wireguard-install-server.sh
./wireguard-install-server.sh
</pre>

# Wireguard Client
- Linux <= Ubuntu 19.04
<pre>sudo add-apt-repository ppa:wireguard/wireguard
sudo apt-get update
sudo apt-get install wireguard</pre>

Source : https://www.wireguard.com/install/
