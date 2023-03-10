
![](https://cdn.discordapp.com/attachments/892441244612034611/1060649924934504568/ic_launcher.png)
# LynxVR

![](https://cdn.discordapp.com/attachments/1002633749172850689/1060745085131698196/image.png)

***(Lynx) Big Cats Avatars - Made by Abiboi / [https://Abiboi.com](https://Abiboi.com) / @boi_abi*** 

LynxVR is an application for smartwatches that allows to stream your Vitals into your VR Game! A few games are compatible such as NeosVR and VRChat. 
This application does not require a computer to stream this data and allows Quest Users or Pico Users to use the full advantage of OSC and WebSockets.

# Why LynxVR?
LynxHR is fully open-source, free and growing with support on new and old hardware! We want to make it simple to setup for anyone who's new to Virtual Reality. LynxVR was developed by Furred and its contributers.

# Supported Devices
| Device Name      | Operating System | Standalone Mode | Client Mode | Desktop Mode | Bluetooth / Network |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| Samsung Galaxy Watch 4      | WearOS 3       | ✅ |✅ |✅ | Network |
| Samsung Galaxy Watch 5      | WearOS 3       | ✅ |✅ |✅ | Network |
| Fossil Watch Gen 4      | WearOS 2       | ✅ |✅ |✅ | Network |
| Fossil Watch Gen 5      | WearOS 2       | ✅ |✅ |✅ | Network |
| Fossil Watch Gen 6      | WearOS 3       | ✅ |✅ |✅ | Network |
| Pixel Watch     | WearOS 3       | ✅ |✅ |✅ | Network |
| Samsung Galaxy Watch 1      | Tizen      | ❌ |❌ |✅ | Network |

[See Full Device Support List](https://github.com/Furred/LynxVR/wiki/Device-Compatibility-List)

# API Example Datasets
NeosVR: ``255,0,0,100,false`` => bpm,spo2,stress_lvl,bat,bat_charging<br/>
VRChat: 
```
/avatar/parameters/lynxhr_hr1_i (Integer)
/avatar/parameters/lynxhr_hr2_u (Unsigned Float)
/avatar/parameters/lynxhr_hr3_s (Signed Float)
/avatar/parameters/lynxhr_bat (Float)
/avatar/parameters/lynxhr_bat_charging (Boolean)
/avatar/parameters/lynxhr_slvl (Float)
```


# Contributions
Special Thanks to : <br/>

**Franko the fox** - Implementation of Early Versions of LynxVR (Rust Based) <br/>
**Jack** - NeosVR Parser for WebSocket <br/>

Want to contribute? Share your ideas and create a PR! We're always looking for some help!
