This is an example of how to turn a raspberry pi3 to a hotspot
using a connection from  mobile - usb - stick.

You have to install : hostaspd and dnsmasq
$sudo apt-get install hostapd
$sudo apt-get install dnsmasq

Then copy hostapd.conf to /etc/hostapd/hostapd.conf

$sudo cp hostapd.conf /etc/hostapd/hostapd.conf

the same for dnsmasq.conf -- > /etc/dnsmasq.conf

$sudo cp dnsmasq.conf /etc/dnsmasq.conf

Then just run
$. ./start_wifi_ap

If you want to go back to the usual wifi

$. ./revert.sh


DISCLAIMER : Use it with your own risk!
