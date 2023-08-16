# nus-stu-networkmanager

Place in /etc/NetworkManager/system-connections

nmcli con add type wifi ifname wlan0 con-name CONNECTION_NAME ssid SSID

nmcli con edit id CONNECTION_NAME

nmcli> set ipv4.method auto

nmcli> set 802-1x.eap peap

nmcli> set 802-1x.phase2-auth mschapv2

nmcli> set 802-1x.identity USERNAME

nmcli> save

nmcli> activate
