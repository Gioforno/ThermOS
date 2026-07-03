# ThermOS
Probably an OS to substitute your old and awkard thermostat, written in C like all serious and consistent programs are made

The idea is to make really smart your manage of temperature: in our first case we implement two ESP32, the master with a GSM 4g module for remote link and the slave with WIFI for local management.
Why this structure? because we already use the gsm and is very easy for the master for remote link, and local user have always a smartphone.

In this repo we provide all need to implement by yourself the (for now) two thermostats, like the hw, the case for hw, how to link to your boiler and the software needed. 

Here there are the link for the [gsm module](https://it.aliexpress.com/item/1005012393503763.html), for the [wifi module](https://it.aliexpress.com/item/1005007004119282.html), for [master's infoscreen](https://it.aliexpress.com/item/1005008779046522.html) and for [temperature sensor](https://it.aliexpress.com/item/1005012179635448.html) (one for each thermostat you implement)



Future development:
- support various implementations (only one thermostats, more than two, more slave, master wifi, ...)
- another very important feature
- the disruptive idea
 
