
1. Discussion in the MATLAB community (USB ANT+  stick solution):

https://www.mathworks.com/matlabcentral/answers/142677-capturing-heart-rate-from-usb-ant-dongle-and-chest-strap

2. Raspberry Pi Ant+ to MQTT-Broker connection (Reto Rölli):

https://www.thisisant.com/forum/viewthread/7360/

3. Discussion about GARMIN watch - ConnectIQ-Watch-IoT - Microsoft Azure Platform (Dave Lusty):

https://www.eevblog.com/forum/cloud-computing/garmin-watch-connectiq-watch-iot-microsoft-azure-platform/msg2828468/

4. Live-stream from Garmin watches via ANT+ stick & virtual box (Darren Hague) and other solutions

https://www.eevblog.com/forum/cloud-computing/live-stream-from-garmin-watches-via-ant-stick-virtual-box-(evtl-coud-iot)/

5. Discussion about sensor accuracy with the The5krunner in his blog:

https://the5krunner.com/2019/04/06/polar-oh1-review-2019/#PRICING_AVAILABILITY_Polar_OH1_Review

6. Python script to Convert Garmin FIT Files to CSV (Max Candocia):

https://www.thisisant.com/forum/viewthread/7358/

7.Linux Pinephone for ANT+ projects (Peter Gamma):

https://www.thisisant.com/forum/viewthread/7372/

8. Android application A TRAINING TRACKER (open source project, Dr. Ing. Rainer Blind) stores data in .csv format

https://www.thisisant.com/forum/viewthread/7363/

9. QBIKE ANT+ Cycling Training on Raspberry Pi (Jeffery Clive):

https://www.thisisant.com/forum/viewthread/7371/

10. Garmin watches and BLEv5.0 support?

- There is an example for BLE devices with Heart Rate Profile for Bluetooth Low Energy Specification v5.0, Dec. 06, 2016 in Matlab:

https://www.mathworks.com/help/comm/examples/modeling-of-ble-devices-with-heart-rate-profile.html

- Garmin HRM Dual™ has ANT+®-Standard (2,4 GHz) and  BLUETOOTH® 5.0 (BLE) support:

https://www.rosebikes.com/garmin-hrm-dualtm-heart-rate-chest-strap-2679363

- It should be possible to pair the Garmin HRM Dual to a PC with Matlab and connect the sensor to the Matlab example code, but this this needs to be confirmed:

https://www.mathworks.com/matlabcentral/answers/533393-are-there-specific-ble-heart-rate-sensor-devices-available-which-are-compatible-to-the-example-model?s_tid=prof_contriblnk

- According to the Polar support, it should also  be possible to pair Bluetooth 4.0 sensors to as Bluetooth 5.0 smartphone, so eventually also Bluetooth 4.0 sensors could work with the Matlab example.

- The Matlab example has only a heart rate profile integrated. But there are more BLE profiles available. Integration for instance of the BLE running speed and cadence profile 

https://www.cypress.com/file/425161/download

would make it possible to use also a BLE footpod. So Matlab could be used to monitor indoor activities with a heart rate sensor and a foot pod sensor.

- Here is the list of (all?) of the current Bluetooth Smart profiles (personal communication DC Rainmaker):

https://www.bluetooth.com/specifications/gatt/

