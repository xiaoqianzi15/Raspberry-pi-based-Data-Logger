Raspi based data-logger   //not finished

Hardware schematic:
Power:

Front end:

Software:
The software I'm using is:
Smbus2:
https://pypi.org/project/smbus2/
The function I'm using is :i2c_rdwr
I'm using this function is The ADC I'm using generate 2byte data. so the date go this way 
![image](https://github.com/xiaoqianzi15/Raspberry-pi-based-Data-Logger/blob/master/picture/%E5%9B%BE%E7%89%871.png)
So  i2c_rdwr can get data from ADC and storage it in Raspi. And it is ready to be used for Qt and Matplot

Pyside2:
https://pypi.org/project/PySide2/
Why I'm using this is this is the based on Qt5 so it works so good in Raspi and it get official support from Raspi Group.
It is better than Tkinter. Tkinter is easier but the Example is not working.
All the Pyside2 examples are working good in Raspberry pi4 4G.


Matplotlib:









