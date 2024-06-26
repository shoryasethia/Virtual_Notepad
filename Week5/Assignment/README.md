## What you have to make using opencv and mediapipe is
1. **Brightness Controller + The color of brightness level/bar should change from green (bright) to red (dim).**
> For Brightness you can use `wmi` library
```
import wmi
```
> Initialize WMI for brightness control
```
c = wmi.WMI(namespace='wmi')
```
> Set monitor brightness using WMI
```
brightness = int(length)     //length is distance between fingers
c.WmiMonitorBrightnessMethods()[0].WmiSetBrightness(brightness, 0)  # Set brightness
```
2. **Drag and Drop a saved image.**
>  **Optional : You can try to change the size while drag and drop**
3. **Pause your screen whenever 4 or more fingers are detected.**

### In submission form, this time along with the codes, you have to submit the link of your implementation as well.
### For this assignment ask your doubts in the `Mentee Discussions` on WhatsApp. It would help others as well. And try to solve each other doubts.
