Windows

netsh interface show interface
netsh interface set interface "Ethernet" disable


Linux

ip link show
sudo ip link set eth0 down


macOS

ifconfig
sudo ifconfig en0 down
