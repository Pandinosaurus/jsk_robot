## :set-master-volume `volume` (naoqi_driver [`kochigami-develop`])

### What is this?

Sets the overall output volume of the system.  

### Parameters

`volume`: volume (int 0-100)

### Location

`launch/naoqi_driver.launch`  

### NAOqi API

[ALAudioDeviceProxy::setOutputVolume](http://doc.aldebaran.com/2-5/naoqi/audio/alaudiodevice-api.html#alaudiodevice-api)  

Related PR is [here](https://github.com/ros-naoqi/naoqi_driver/pull/110) and [here](https://github.com/jsk-ros-pkg/jsk_robot/pull/814).  
Related commit is [here](https://github.com/kochigami/naoqi_driver/commit/9839964110eb25ba316213b65908715863e8ca94#diff-fd6c3751bab04f0ce69992cda4034458R974).

### Sample

```
send *ri* :set-master-volume 30 ; set master volume as 30 (0~100)
```
