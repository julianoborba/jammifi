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


Disclaimer
---------

>It may be illegal to use this script in the US. Due to changes in FCC regulation
>in 2015, it appears intentionally de-authing WiFi clients, even in your own
>home, is now classed as ‘jamming’. Up until recently, jamming was defined as the
>indiscriminate addition of noise to signal - still the global technical
>definition. It’s worth noting here that all wireless routers necessarily ship
>with the ability to de-auth, as part of the 802.11 specification.

>All said, use of this script is at your own risk. Use with caution.

Quote from [here](https://github.com/JulianOliver/dropkick.sh).
