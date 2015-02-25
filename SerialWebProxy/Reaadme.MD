Serial Web Proxy OpenWrt packages

---------------------------------


The serialwebproxy is a HTML5 WebSocket to Serial Proxy. it proxies all the data that comes from/to the serial port to a websocket on port 
5331 / or user configurable.



sewebproxy - configured for using TTYS0 for serial data proxing

serwebusb - configured for using ttyUSB0 for serial data proxing

serwebacm - configured for using ttyACM0 for serial data proxing



To compile with openwrt copy the folders to openwrt 
packages/utils and then select the packages via make menuconfig.



