
Discussion in the MATLAB community:

https://www.mathworks.com/matlabcentral/answers/142677-capturing-heart-rate-from-usb-ant-dongle-and-chest-strap

Discussion about EventHubApp:

https://forums.garmin.com/developer/connect-iq/f/discussion/209439/eventhubapp


Discussion about GARMIN watch - ConnectIQ-Watch-IoT - Microsoft Azure Platform:

https://www.eevblog.com/forum/cloud-computing/garmin-watch-connectiq-watch-iot-microsoft-azure-platform/msg2828468/

Live-stream from Garmin watches via ANT+ stick & virtual box:

https://www.eevblog.com/forum/cloud-computing/live-stream-from-garmin-watches-via-ant-stick-virtual-box-(evtl-coud-iot)/

Discussion about sensor accuracy:

https://the5krunner.com/2019/04/06/polar-oh1-review-2019/#PRICING_AVAILABILITY_Polar_OH1_Review

..

Integration of the GARMIN watch into the Mind Monitor

https://mind-monitor.com/forums/viewtopic.php?f=15&p=1825#p1825

.
.
Moxymonitor:
https://www.moxymonitor.com/product/ant-to-serial-converter/
makes a device for our Moxy users to get data into Matlab.

This captures the ANT+ signals and converts them to a serial stream on a USB port. You have to program Matlab to read the COM port. There's example code in the manual.

It works for other profiles besides the MO2 profile too. Newer model also has analog outputs for up to 4 of the channels. 
