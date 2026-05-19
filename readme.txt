USB Army Knife as EDC

My implementation of https://github.com/i-am-shodan/USBArmyKnife

I am obsessed with EDC, and really want a useful, small, InfoSec basd EDC.

I've tried this before with the somewhat ill-advised USB Armory; see https://github.com/saintcrossbow/USB-Swiss-Armory-Knife

However we seem to have a really EDC with the USB Army Knife. The repo above is excellent and has great examples. However, to be really multifunctional, you have to change payloads on the SD card or through the AP. I wanted something that I could use without the AP. So this is a remix of some of the examples, with now just two basic scripts, and a little more graphics.

So friends I give you my real EDC, with real hollywood style and useful tools accessible by a click. You friend - the Saint himself - carries it himself!

Usage:
Insert USB. (Bang) An access point is enable for basic file management usage.
Click. Moves to Swiss Army style - enable full usage of device through the AP. Note you have to click to this point to get full access (it ends the script).
Long press. Get ready to beacon spam - press click to start. Same as original script in repo.
Long press. Get ready to WiFi attack - press click to start. Same as original script in repo.
Long press. Get ready to act as USB ethernet capture. On click it will get set up in right mode, display a graph as it gathers Ethernet deatils, and reboot back into normal mode.
Long press. Press once to become a USB device.

Want the promised covert USB method? It requires manual intervention, but has a pretty cool method.
1) Backup autorun.ds
2) Copy coverstorage_autorrun.ds and paste as new autorun.ds
3) Next time you plug in USB, it will show as a storage device once. 
4) After it plugs in again, it shows up not as a different USB storage device - but a voltage detector! 
To reset it, delete the /firstrun file

USB Army Knife - i-am-shodan did amazing work. All I did is move it to fun EDC. I hope you enjoy it.