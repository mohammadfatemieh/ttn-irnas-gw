# TheThingsNetwork LoraWAN gateway with RAK831 / IMST iC880A and RaspberryPi Zero W for outdoor use. DIY 5.5dB colinear antenna or N connector antenna.

To boost the growth of cost-effective community established outdoor gateways we have designed IRNAS outdoor LoraWAN gateway that includes all components and an antenna element in a weatherproof enclosure. This way communities can easily deploy good quality gateways with minimal costs.

There are two key design options available, subject to selecting the antenna:
* DIY colinear antenna with designed gain of 5.5dB, typically build quality reducsed this to about 3dB (shown left)
* N-connector option for other antennas, default option is RAK wireless omni glass fiber antenna 6dB (design files to be avilable shortly) (shown right)

<img src="/img/irnas-outdoor-lorawan-gateway-4.jpg"  width="425px"> <img src="/img/irnas-outdoor-lorawan-gateway-compact.jpg"  width="425px"> 


IRNAS outdoor LoraWAN gateway joins great solutions into an unified gateway:

* RAK Wireless RAK831 concentrator option:
  * RAK wireless RAK831 gateway module http://www.rakwireless.com/en/WisKeyOSH/RAK831
  * RAK-Raspberry Pi shield by ch2i https://github.com/hallard/RAK831-Zero

* IMST iC880A concentrator option:
  * IMST ic880A concentrator https://wireless-solutions.de/products/radiomodules/ic880a.html
  * iC880A RPi shield/backplane https://www.tindie.com/products/gnz/imst-ic880a-lorawan-backplane-kit/
  * note this backplane requires a minor manual modification to install Murata OKI-78SR-5 regulator, untill an optimized version is designed, check photosfor details

* Components used in both versions
  * Murata OKI-78SR-5 power regulator (multiple versions available)
  * Raspberry Pi Zero W embedded computer + SD card https://www.raspberrypi.org/products/raspberry-pi-zero-w/
  * micro USB-Ethernet USB 2.0 adapter: https://www.aliexpress.com/item/PZ-USB-2-0-to-fast-Ethernet-10-100-RJ45-Network-LAN-Adapter-Card-Micro-usb/32819958748.html
  * Waterproof PoE injector http://szzq.en.alibaba.com/product/60307069118-209893270/IP67_waterproof_RJ45_ethernet_cable_connector.html
  * DIY 5.5dB co-linear antenna designed by Fabien Ferrero from UNICE in France
  * Polyethilene tubing for enclosure 75mm diameter
  * 3D printed part by IRNAS to mount everything together
  * 24V Passive PoE injector/power supply
  * Optional INA219 current measurement board via I2C

The final product is a simple and and cost-effective gateway for about 250 EUR anyone can make and simply install outdoor. With this design we have achieved over 50 km coverage between Pohorje mountain and cities of Graz in Austria and Zagreb in Croatia.


## Assembly instructions
Assembly instructions are coming up shortly, however the posted images are sufficient for replicating the design. The only custom mechanical part that can be 3D printed or milled available in this repository in the folder: mount and on [this link](https://a360.co/2HcsiBF).

<img src="/img/irnas-outdoor-lorawan-gateway-2.jpg"  width="850px">

RAK Wireless RAK831 concentrator option

<img src="/img/irnas-outdoor-lorawan-gateway-7.jpg"  width="425"> <img src="/img/irnas-outdoor-lorawan-gateway-5.jpg"  width="425">

<img src="/img/irnas-outdoor-lorawan-gateway-6.jpg"  width="425"> <img src="/img/irnas-outdoor-lorawan-gateway-3.jpg"  width="425">

IMST iC880A concentrator option

<img src="/img/irnas-outdoor-lorawan-gateway-8.jpg"  width="425"> <img src="/img/irnas-outdoor-lorawan-gateway-9.jpg"  width="425">

<img src="/img/irnas-outdoor-lorawan-gateway-10.jpg"  width="425"> <img src="/img/irnas-outdoor-lorawan-gateway-11.jpg"  width="425">

<img src="/img/irnas-outdoor-lorawan-gateway-4.jpg"  width="850px">


## Co-linear antenna wire
Bending the wire for the co-linear 5.5dB antenna is likely the most challenging part and requires special care. Note that the frequency is tuned with the diameter of the loop and thus it must be made rather precisely. There are two antenna designs available, [one for 868MHZ EU](Collinear868MHzLoRaantenna.PDF) and [the other for 915MHz USA](CollinearLoRaantenna915MHzIRNAS.pdf). Step-by-step instructions on how to make the antenna available in this [video tutorial](https://youtu.be/1_1LxuOngHs).

<img src="/img/Collinear 868 MHz LoRa antenna.jpg"  width="850px">

<img src="/img/irnas-outdoor-lorawan-gateway-1.jpg"  width="850px">
