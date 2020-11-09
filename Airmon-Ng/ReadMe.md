# How to enable Wireless Adapter after running airmon-ng commands
* sudo service NetworkManager restart
* sudo airmon-ng stop <wireless_adapter_name>
* sudo ifconfig <wireless_adapter_name> up