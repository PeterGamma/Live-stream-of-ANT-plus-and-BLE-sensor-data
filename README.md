
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


14. BeagleBone Blue, Bitalino, Android for step counting:

https://github.com/PeterGamma/Live-stream-for-step-counting-

15. Garmin watches can now Broadcast Garmin Optical HR to Apps Like Zwift // ANT & Bluetooth:

[url=https://www.youtube.com/watch?v=vuOcAP_7uec]https://www.youtube.com/watch?v=vuOcAP_7uec[/url]

Matlab supports BLE, but I could not find an example of someone confirming that BLE streaming to Matlab is working:

[url=https://www.mathworks.com/matlabcentral/answers/518074-is-there-an-example-how-to-connect-the-polar-oh1-bluetooth-low-energy-heart-rate-sensor-with-matlab?s_tid=prof_contriblnk]https://www.mathworks.com/matlabcentral/answers/518074-is-there-an-example-how-to-connect-the-polar-oh1-bluetooth-low-energy-heart-rate-sensor-with-matlab?s_tid=prof_contriblnk[/url]

16. No agreement about a scientifically validated standard for sports watch sensor accuracy with DC Rainmaker and Stephen Thomas:

https://www.dcrainmaker.com/2019/03/polar-oh1-plus-optical-hr-sensor-in-depth-review.html


20. There is finally a practical example code available in Matlab for BLE heart rate sensor and BLE foot pod:

https://ch.mathworks.com/help/matlab/import_export/collect-data-from-fitness-monitoring-devices.html

Garmin watches can broadcast sensor data over ANT+, newer Garmin watches can also broadcast sensor data over BLE and should also work with the BLE Matlab example:

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

This Python project is based on the Polar Android SDK.  

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

24. Garmin watch and sensor streaming?:

.
.

Currently the easiest way to stream ANT+ sensor data from GARMIN watches to MATLAB and Python, is to use Polar sensors with the Polar Sensor Logger app, and then stream the sensor data over MQTT to the Influx Database, where it can be vizualized with Grafana. There is a Influx Database client for Matlab and Python for further data processing. 

.
.

25. MQTT for Garmin watches ?

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


30. Discussion in the TRAINERROAD forum: ANT+/BTLE to MQTT ?  

.
.

https://www.trainerroad.com/forum/t/ant-btle-to-mqtt/42937

.
.

31. Does Matlab consultant Adam Danz or Matlab undelete my Matlab questions, which where deleted for reasons I cannot follow?

.
.

https://ch.mathworks.com/matlabcentral/answers/758469-does-matlab-consultant-adam-danz-or-matlab-undelete-my-matlab-questions-which-where-deleted-for-rea?s_tid=prof_contriblnk

.
.

After postings at XDA developers about Poco F1, where I mentioned Matlab, my last question in the Matlab community about post deletion was deleted. I worked almost a week on this question. Is the Matlab community the right community for enlightened scientists? I invite everybody  to send me an e-mail to discuss about this.Since I have observed that many of my posts where deleted in different communities after I published a list of my deleted posts in the Matlab community on my blog, I removed this list from my blog. I am convinced that I would win the case of post deletion in the Matlab community if I took legal action. I will do without it for the time being. 

.
.

https://petergamma.org/arbitrary-post-deletion-in-the-matlab-community/

.
.

32. How to Run MATLAB Code in Octave:

.
.

https://itstillworks.com/12562105/how-to-run-matlab-code-in-octave

.
.


33. How to convert MATLAB code to python:

.
.

https://www.youtube.com/watch?v=AxeJayy5oLA

.
.

34. Bluetooth Low-Energy Heart Rate Monitor data logging in Python:

.
.

https://github.com/fg1/BLEHeartRateLogger

.
.

35. Porting the Adafruit Pyloton open source bike computer to a platform with more features:

.
.

https://petergamma.org/read-out-sensor-data-from-the-adafruit-clue-pyloton/


.
.

36. Sensor streaming over IpBike and Livetracking.io

.
.

https://petergamma.org/sensor-streaming-over-ipbike-and-livetracking-io/


.
.

37. Linux AsteroidOS sports watch

.
.

https://petergamma.org/linux-asteroidos-sports-watch/











