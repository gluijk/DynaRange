# DynaRange
A new, modern and easy to use tool to measure camera sensor's Dynamic Range.

Under the hood, DynaRange's engine (rango) includes high precision features not found in other Dynamic Range (DR) calculation tools such as:
- Black and saturation points calculation with decimal precision (unlike most existing software that just use metadata integer values)
- Careful selection of valid patches ensuring noise readings are valid for DR calculation
- Construction of the sensor's SNR curves which represent the best picture of sensor's performance
- Derived DR calculation for any SNR threshold and for any normalization
- Easy to explain resolution normalization process based on standard noise estatistics


The basic usage will be as follows:
1) Prepare the camera on a tripod to photograph your screen's monitor
2) Display a special chart (supplied) that contains patches from black to white
3) Take a photo of the screen at every ISO setting in RAW format
4) Put the lens cup and take a photo at base ISO (dark frame)
5) Display a white screen and take a totally overexposed photo (saturation frame)
6) Load all RAW files into DynaRange
7) Get all the measurements: black and saturation points, SNR curves and DR calculation at every ISO

![measuring-photographic-dynamicrange](/SNRcurvesBLACK254.85.png)

![measuring-photographic-dynamicrange](/SNRcurvesBLACK254.85_8Mpx.png)

![measuring-photographic-dynamicrange](/userInterface/Main_Window_v1.2.png)
