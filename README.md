# yolobijes
```
cout <"hello world">
```
```
from djitellopy import tello
from time import sleep

me = tello.Tello()
me.connect()
print(me.get_battery())

me.takeoff()

me.send_rc_control(0 ,50 ,0 ,0 )
sleep(2)
me.send_rc_control(0 ,0 ,0 ,180 )
sleep(2)
me.send_rc_control(0 ,0 ,0 ,0 )
me.land()

```
## 2ND HEADER- this is markdown
continuous integrated codes -git

### 3RD HEADER 
higlight __yolo__
i drink wotah

YElLoW
