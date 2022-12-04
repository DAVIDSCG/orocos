# orocos

## Sources
  1. [orocos_kinematics_dynamics](https://github.com/orocos/orocos_kinematics_dynamics.git)  
  version:1.5.1
  2. [SIP](https://riverbankcomputing.com/software/sip/download)  
  version: 4.19.25  
  3. dependence:  
    Egien:3.3.7  

### Python interpreter  
python3.8.10  
  
### Platform
Ubuntu 20.04

There are three directories:
two sources codes and a "build" in which these are files compilered from my platform  

# Installation  

# SIP


```Shell
  cd sip-4.19.25
  python configure.py  
  make -j8; sudo make install
```

### output:

```Shell
/usr/lib/python3/dist-packages/sipconfig.py  
/usr/lib/python3/dist-packages/sipdistutils.py  
/usr/include/python3.8/sip.h  
/usr/bin/sip  
/usr/lib/python3/dist-packages/sip.pyi  
/usr/lib/python3/dist-packages/sip.so  
```
# orocos_kinematics_dynamics


