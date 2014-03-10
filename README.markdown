# Modified Arduino Print.cpp

Modification to Arduino Print.cpp to provide Serial.print and
Serial.println with uint64_t and int64_t.

### Origin

All code by Arduino Forums and all respect and thank to appropriate people.

[http://forum.arduino.cc/index.php/topic,143584.0.html](http://forum.arduino.cc/index.php/topic,143584.0.html)

```
size_t println(int64_t, uint8_t = DEC);
size_t print(int64_t, uint8_t = DEC);
size_t println(uint64_t, uint8_t = DEC);
size_t print(uint64_t, uint8_t = DEC);
```
