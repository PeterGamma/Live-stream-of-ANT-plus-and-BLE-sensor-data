
1. Discussion in the MATLAB community (USB ANT+  stick solution):

https://www.mathworks.com/matlabcentral/answers/142677-capturing-heart-rate-from-usb-ant-dongle-and-chest-strap

2. Raspberry Pi Ant+ to MQTT-Broker connection (Reto Rölli):

https://www.thisisant.com/forum/viewthread/7360/

3. Discussion about GARMIN watch - ConnectIQ-Watch-IoT - Microsoft Azure Platform (Dave Lusty):

https://www.eevblog.com/forum/cloud-computing/garmin-watch-connectiq-watch-iot-microsoft-azure-platform/msg2828468/

4. Live-stream from Garmin watches via ANT+ stick & virtual box (Darren Hague) and other solutions

https://www.eevblog.com/forum/cloud-computing/live-stream-from-garmin-watches-via-ant-stick-virtual-box-(evtl-coud-iot)/

5. Python script to Convert Garmin FIT Files to CSV (Max Candocia):

https://www.thisisant.com/forum/viewthread/7358/

6. Linux Pinephone for ANT+ projects (Peter Gamma):

https://www.thisisant.com/forum/viewthread/7372/

7. Android application A TRAINING TRACKER (open source project, Dr. Ing. Rainer Blind) stores data in .csv format

https://www.thisisant.com/forum/viewthread/7363/

8. QBIKE ANT+ Cycling Training on Raspberry Pi (Jeffery Clive):

https://www.thisisant.com/forum/viewthread/7371/

9. Discussion about sensor accuracy of the Polar OH1(5krunners blog)

https://the5krunner.com/2019/04/06/polar-oh1-review-2019/

10. Matlab and BLE sensors instead of ANT+ sensors?

https://www.mathworks.com/matlabcentral/answers/533393-are-there-specific-ble-heart-rate-sensor-devices-available-which-are-compatible-to-the-example-model?s_tid=prof_contriblnk

11. Pyloton Open Source Cycling Computer:

https://github.com/PeterGamma/Pyloton-CircuitPython-Cycling-Computer

12. Alternatives to Pyloton

https://github.com/PeterGamma/Alternatives-to-Pyloton-

13. CLUE Step Counter

https://github.com/PeterGamma/CLUE-Step-Counter

14. BeagleBone Blue, Bitalino, Android for step counting:

https://github.com/PeterGamma/Live-stream-for-step-counting-

15. Garmin watches can now Broadcast Garmin Optical HR to Apps Like Zwift // ANT & Bluetooth:

[url=https://www.youtube.com/watch?v=vuOcAP_7uec]https://www.youtube.com/watch?v=vuOcAP_7uec[/url]

Matlab supports BLE, but I could not find an example of someone confirming that BLE streaming to Matlab is working:

[url=https://www.mathworks.com/matlabcentral/answers/518074-is-there-an-example-how-to-connect-the-polar-oh1-bluetooth-low-energy-heart-rate-sensor-with-matlab?s_tid=prof_contriblnk]https://www.mathworks.com/matlabcentral/answers/518074-is-there-an-example-how-to-connect-the-polar-oh1-bluetooth-low-energy-heart-rate-sensor-with-matlab?s_tid=prof_contriblnk[/url]

16. No agreement about a scientifically validated standard for sports watch sensor accuracy with DC Rainmaker and Stephen Thomas:

https://www.dcrainmaker.com/2019/03/polar-oh1-plus-optical-hr-sensor-in-depth-review.html

17. Make yourself free from your depency of Garmin: Open Source Bike computer and Open Source Sports watch

https://www.dcrainmaker.com/2020/01/computers-worldtour-peloton.html

18. Developement of an open source bike computer and sports watch in the Pine64 community:

https://forum.pine64.org/showthread.php?tid=10172&page=2

19. Access your Peloton bike computer using using GNU Octave:

https://github.com/PeterGamma/Access-your-Peloton-bike-computer-using-using-GNU-Octave

20. There is finally a practical example code available in Matlab for BLE heart rate sensor and BLE foot pod:

https://ch.mathworks.com/help/matlab/import_export/collect-data-from-fitness-monitoring-devices.html

Garmin watches can broadcast sensor data over ANt+, newer Garmin watches can also broadcast sensor data over BLE and should also work with the BLE Matlab example:

https://ch.mathworks.com/matlabcentral/answers/533393-are-there-specific-ble-heart-rate-sensor-devices-available-which-are-compatible-to-the-example-model?s_tid=mlc_ans_email_view#comment_990287

No additional toolboxes are necessary for Bluetooth low energy (ble supported in Matlab since 2019b version):

https://ch.mathworks.com/matlabcentral/answers/561773-how-can-i-communicate-with-a-ble-bluetooth-low-energy-device-in-matlab
.
.

21. Ticwatch Pro running Linux for ANT+ and BLE sensors?
.
.

https://forum.xda-developers.com/smartwatch/other-smartwatches/linux-android-wear-ticwatch-pro-2020-t4166623
.
.

22: Creating an ECG Data Stream with Polar device:
.
.

https://towardsdatascience.com/creating-a-data-stream-with-polar-device-a5c93c9ccc59
.
.

This Python project is based on the Polar Android SDK. But does it also run on a Linux phone? 

.
.

23: Polar Sensor Logger with MQTT support for a real-time stream to Matlab, Python, Influx Database, etc.:

.
.

https://play.google.com/store/apps/details?id=com.j_ware.polarsensorlogger&gl=CH

.
.

Jukka Happonen, Senior Specialist at Polar Electro Oy Research Center already made a very helpful contribution with his Polar Sensor Logger app, which can record many parameters from Polar sensors to .txt files, and can stream sensor data over MQTT to Influx Data Base. The Polar Sensor Logger app seems not to be an offical Polar app, but is really an easy and contemporary solution for sensor data streaming. Thank you very much for your great work, Jukka Happonen.

.
.

24. Summary:

.
.

Currently the easiest way to stream ANT+ sensor data from GARMIN watches to MATLAB and Python, is to use Polar sensors with the Polar Sensor Logger app, and then stream the sensor data over MQTT to the Influx Database, where it can be vizualized with Grafana. There is a Influx Database client for Matlab and Python for further data processing. 

.
.

25. MQTT for Garmin watches:

.
.

Is a Rasperri PI ANT+ script which sends sensor data to an MQTT broker, or an EventHubApp which sends sensor data over the Azure Cloud to Microsoft Power PI the only option Garmin has to offer for live-streaming of sensor data?

.
.

https://forums.garmin.com/developer/connect-iq/f/app-ideas/258254/mqtt-support-for-garmin-sensors

.
.

Why is the MQTT, Grafana, InfluxDB, InfluxDB client for Matlab and Python not supported by Garmin?

.
.

26. ANT+ sensor logger app which sends sensor data to an MQTT broker?

.
.


https://www.thisisant.com/forum/viewthread/7502/

.
.


27.MQTT support for the Adafruit Clue Pyloton (Bluetooth low energy)?

.
.

https://forums.adafruit.com/viewtopic.php?f=65&t=177277

.
.

28. Foot pod support for the Adafruit Clue Pyloton (Bluetooth low energy)?

.
.

https://forums.adafruit.com/viewtopic.php?f=65&t=177278


.
.

29. PeloMon: Peloton data capture with Bluetooth (Imran Haque, PhD. Data scientist, computational biologist)

.
.

Imran Haque decoded (most of) the protocol that the Peloton bike uses to communicate with its head unit tablet and built a device, the PeloMon, that takes that data during a ride, without interfering with the Peloton software, to broadcast it over Bluetooth LE to whatever devices you’d like — a watch, Zwift, Wahoo, whatever. 

.
.

https://ihaque.org/posts/2020/10/15/pelomon-part-i-decoding-peloton/

.
.

30. ANT+/BTLE to MQTT:

.
.

https://www.trainerroad.com/forum/t/ant-btle-to-mqtt/42937








