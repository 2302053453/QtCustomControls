#CstmBattery

![CstmBattery](../IMAGE/CstmBattery.png)


 <p> use the follow function to set the MAX value of the battery, default is 100.
 <p>  void setMaxValue(const qreal &maxValue);
 <p>
 <p> use the follow function to set the CURRENT value of the battery, default is 60.
 <p>  void setValue(const qreal &value);
 <p>
 <p> use the follow function to set the WARN value of the battery, default is 1/5 of the Max Value.While the CURRENT value is lower then
 <p> the WARN value ,the brush color of the battery will change .
 <p> void setWarnValue(const qreal &warnValue);
 <p>
 <p> Those functions are setting the color of the battery.  you can set the frame color , header color , battery color and warn color.
 <p> By default , the color of the frame and header are Black, the color of the battery is Green , the warn color is Red.
 <p> void setWarnValueColor(const QColor &warnValueColor);
 <p> void setBatteryColor(const QColor &batteryColor);
 <p> void setFrameColor(const QColor &frameColor);
 <p> void setHeaderColor(const QColor &headerColor);
 <p>
 <p> The follow function is to set if the color of the frame and header would change while the CURRENT value was lower than the WARN value.
 <p> Default is True.
 <p>void setFrameWidth(const qint32 &frameWidth);
 