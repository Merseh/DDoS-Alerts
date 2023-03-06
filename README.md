# DDoS-Alerts
This script monitors the network traffic on a specified network interface and dumps packets if the number of packets transmitted per second exceeds a certain threshold. The script also sends a message to a Discord webhook to alert the user of the packet dump. The script is designed to be secure by checking for root user permissions and setting file permissions to ensure that the Discord webhook file can only be read by the root user.

# Installation

apt install tcpdump

chmod +x log.sh

sh log.sh
