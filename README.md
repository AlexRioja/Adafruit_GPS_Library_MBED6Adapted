# Adafruit_GPS_Library_MBED6Adapted
Adaptation of the Adafruit_GPS_Library for the new MbedOs6  

Adapted from -->https://os.mbed.com/users/fconboy/code/MBed_Adafruit-GPS-Library3/  

Changes:  
  -Serial has now moved to be BufferedSerial  
  -getc is now adapted to BufferedSerial.read() (the same with write())  
  -wait() changed to ThisThread::sleep_for()  
  
  
  Found another project trying to do the same:  
  -https://github.com/toyowata/adafruit-gps-v3-test/blob/main/MBed_Adafruit_GPS.cpp
