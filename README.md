


Woodpecker is a custom security distro for remote penetration testing. Some of the original woodpecker's tools are replaced with newer ones (Tor and VPN initializers). This specific variation is based on Ubuntu and easy to maintain. 

## Screenshot
<img src="https://raw.githubusercontent.com/qeeqbox/woodpecker/master/readme/intro.png" style="max-width:768px"/>

## Running
```console 
docker run --privileged -it qeeqbox/woodpecker:1.0
...
...
Successfully built 20055ad080f9
Successfully tagged qeeqbox/woodpecker:1.0

https://github.com/qeeqbox/woodpecker

Custom Woodpecker Security distro for pentesting

[>] Init
[>] Setting root password
[>] Setting xuser password
[>] Setting up vnc 1-4
[>] Setting up vnc 2-4
[>] Setting up vnc 3-4
[>] Setting up vnc 4-4
[>] Localhost exists
[>] Init qnetwork
[>] Setup tor 1-1 None
[>] Setup openvpn.. 1-1 Done

root pass -> lS8OjqpR66
-----------------------
Username  -> xuser
Password  -> RMy3^NX;AZ
VNC pass  -> x#<q!J<thS

http://172.17.0.2:6080/index.html
```

## Changing resolution
- RDP (Change it using the clint app)
- VNC (Change it using `xrandr -s ...`)
- Web browser (Change it using `xrandr -s ...`)

## Installed tools
afflib-tools aircrack-ng apktool arping arp-scan arpwatch autopsy backdoor-factory bbqsql bdfproxy binwalk bluez bluez-hcidump braa btscanner cabextract cadaver cewl cgpt cherrytree chirp chkrootkit chntpw clang cmospwd crunch cryptcat cryptsetup curlftpfs cutycapt darkstat dc3dd dcfldd dhcpig dirb dmitry dns2tcp dnsrecon dnstracer dnswalk doona dos2unix driftnet dsniff edb-debugger ethtool ettercap-common ettercap-dbg ettercap-graphical ewf-tools exiv2 extundelete fcrackzip flasm foremost fping funkload galleta gdb ghex guymager hackrf hashcat hashdeep hashid hping3 httrack hydra hydra-gtk i2c-tools ifenslave ike-scan inetsim iodine john kismet leafpad libfreefare-bin libhivex-bin libnfc-bin lynis macchanger magicrescue maskprocessor masscan mc mdbtools mdk3 medusa memdump minicom miredo missidentify mitmproxy nasm nbtscan ncrack ncurses-hexedit netdiscover netmask netsed netsniff-ng netwag ngrep nikto nmap onesixtyone ophcrack ophcrack-cli p0f pasco patator pdfcrack pev pixiewps polenum proxychains proxytunnel pst-utils ptunnel pyrit python-impacket python-scapy radare2 rake reaver recon-ng recordmydesktop recoverjpeg redsocks reglookup rifiuti rifiuti2 safecopy samdump2 sbd scalpel scrounge-ntfs sendemail siege sipcrack skipfish sleuthkit socat spectools sqlitebrowser sqlmap ssldump sslh sslscan sslscan kismet sslsniff sslsplit sslstrip statsprocessor stunnel4 suckless-tools sucrack swaks t50 tcpdump tcpflow tcpick tcpreplay thc-ipv6 udptunnel vboot-kernel-utils vboot-utils vim-gtk vinetto vlan volatility vpnc wafw00f wapiti wfuzz whatweb wifite wireshark xpdf xprobe xtightvncviewer yersinia zenmap zim zmap

## Roadmap
- Add IP argument

## Official images (Not custom ones)
- [Ubuntu](https://ubuntu.com/)

## Licncess
- https://ubuntu.com/licensing
- https://github.com/torproject/tor/blob/master/LICENSE
- https://www.vpngate.net/en/join.aspx

## Disclaimer\Notes
- Please treat this image as server 
- You may need to setup some security group rules
- Do not use these images in deployment 
