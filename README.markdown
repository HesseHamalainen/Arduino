# Modified Arduino Print.cpp

Modified Arduino 1.0.5 Print.cpp with support for 64-bit int print

### Thanks

Thanks to Arduino forums

[http://forum.arduino.cc/index.php/topic,143584.0.html](http://forum.arduino.cc/index.php/topic,143584.0.html)

```
size_t println(int64_t, uint8_t = DEC);
size_t print(int64_t, uint8_t = DEC);
size_t println(uint64_t, uint8_t = DEC);
size_t print(uint64_t, uint8_t = DEC);
```
