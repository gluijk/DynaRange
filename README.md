# DynaRange
A new, modern and easy to use tool to measure camera sensor's dynamic range.
Under the hood, DynaRange's engine (rango) includes high precision features not found in other Dynamic Range calculation tools such as:
 - Accurate RAW black and saturation point calculation with decimal figures (unlike most existint software that just use metadata integer values)
 - Careful selection of valid patches ensuring noise readings are valid for Dynamic range calculation
 - Construction of the sensor's SNR curves which represent the best picture of sensor's performance
 - Derived Dynamic Range calculation for any SNR threshold and for any normalization
 - Easy to explain resolution normalization process based on noise estatistics

The basic usage will be as follows:
1) Prepare the camera on a tripod to photograph a screen's monitor
2) Display a special chart that contains patches from black to white (supplied)
3) Take a photo of the screen at each ISO setting in RAW format
4) Put the lens cup and take a photo at base ISO (dark frame)
5) Display a white screen and take a totally overexposed photo (saturation frame)
6) Load all RAW files into DynaRange
7) Get the measurements

![measuring-photographic-dynamicrange](/SNRcurvesBLACK254.85.png)

![measuring-photographic-dynamicrange](/SNRcurvesBLACK254.85_8Mpx.png)

![measuring-photographic-dynamicrange](/userInterface/Main_Window_v1.2.png)
