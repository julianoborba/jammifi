# jammifi

This is a bash based WiFi jammer. It uses your monitor mode interface to continuously send de-authenticate packets to every client on a specified channel.

This program needs the aircrack-ng suit to function and a WiFi card in monitor mode.

Based on esmith2000@gmail.com [ at http://code.google.com/p/wifijammer ] original script.

### Options

Required:
  * -i monitor mode interface
  * -c channel to scan

Optional:
  * -h display help message
  * -v display version

### Example

./wifijammer.sh -i mon0 -c 2
