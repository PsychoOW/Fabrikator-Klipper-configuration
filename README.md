# Turnigy-Fabrikator-Klipper-configuration
Turnigy Fabrikator 3D Printer Klipper Configuration (Ramps 1.4)

I post here 2 Versions of the config, one called Stock which can be used with every unmodified Turnigy Fabrikator 3D Printer. This is not going to be maintained by me, but as of today this configuration will work perfectly fine. This Version is basically here for preservation purposes and ready to use solution for those who are not familiar with configurating printer from scratch. It should have most functions configured that are able with that machine in stock condition. Except the more complex ones like input shaping. 

The other one will be the one i use and will keep it up to date here when necessary, that one is basically stock condition too, but use pei plate (with stock heatbed) and i added a inductive bed leveling probe as z_min_endstop and if i find cheap upgrades then i will add them accordingly.

Please Note: Z , Y and X MAX Endstop sensors are not going to be used, so you can remove these sensors and use these pins for whatever you want. In Klipper there is no need for these things and i didnt checked if they can be added. However, Klipper doesnt let you out of Boundaries so its never going to crash, unless you have configured the bed bigger then it is.

Have fun printing! :)

https://youtu.be/mO7GEQNTWvU?si=GxqugT6uQqMfbmE0
