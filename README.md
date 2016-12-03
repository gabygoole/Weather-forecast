### 示意图
![img](https://github.com/gabygoole/Weather-forecast/blob/master/diagram/pho.png)

### 用到的库
1.[owfont-OpenWeatherMap的icon替代品](http://websygen.github.io/owfont/#usage)<br>
2.JQuery<br>
3.[天气API](https://openweathermap.org/current#geo)

### 注意事项
因为该项目使用了H5原生的`navigator.Geolocation`.而用于确定位置的ip等设备信息是被传到Google，因此，在不挂VPN的情况下，该项目无法正常工作。可将代码中的`geolocation`换成百度地图的API.但此时又有一个问题，国内调用OpenWeatherMap的API，有大概5s的延迟。repo主正working on it.
