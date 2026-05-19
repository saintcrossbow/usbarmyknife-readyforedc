# USB Army Knife as EDC

My implementation of https://github.com/i-am-shodan/USBArmyKnife

I am obsessed with EDC, and really want a useful, small, InfoSec based EDC device. I've tried this before with mixed success; see https://github.com/saintcrossbow/USB-Swiss-Armory-Knife

However we seem to have a really EDC with the USB Army Knife. The repo above is excellent and has great examples. However, when using the default scripts, you have to change payloads on the SD card or through the AP. I wanted something that I could use without the AP. So this is a remix of some of the examples, with now just two basic scripts, and a little more graphics. 

So friends I give you my real EDC, with real hollywood style and useful tools accessible by a click. You friend - the Saint himself - carries it daily! 

Tested only the LilyGo T-Dongle.

Usage:
* **Insert USB**. *Access point*: Basic file management usage.
* **Click**. *Swiss Army functionality*: Enable full usage of device through the AP. Note you have to click to this point to get full access (Why? The wait for button press stops a lot of functionality).
* **Long press**. *Beacon spam*: Press click to start. Same as original script in repo.
* **Long press**. *WiFi attack*: Press click to start. Same as original script in repo.
* **Long press**. *USB ethernet capture*: On click it perform a setup, reboot, display a graph as it gathers Ethernet pcap, and reboot back into normal mode.
* **Long press**. *USB storage*: Press to activate.

The excellent covert USB example is also available, but requires manual intervention and now has a pretty cool locked feature.
1) Backup autorun.ds
2) Copy coverstorage_autorrun.ds and paste as new autorun.ds
3) Next time you plug in USB, it will show as a storage device once. 
4) After it plugs in again, it shows up - not as a different USB storage device - but a voltage detector! 
To reset it, delete the /firstrun file

USB Army Knife - i-am-shodan did amazing work. All I did is remix it to a fun EDC with some new graphics. I hope you enjoy it.