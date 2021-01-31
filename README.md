
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

This Python project is based on the Polar Android SDK. But does it also run unter Linux? 



