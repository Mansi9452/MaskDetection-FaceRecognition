# Mask-Detection-Face-Recognition-Using-ESP32-Camera

Change SSID and Password according to your own Wifi Connection.

Load the images for face recognition in SD Card named as - "1.jpg", "2.jpg", etc.

Image 1-5 will use ID1, 6-10 will use ID2, and so on.

Update names in ID List Array and Number of Photos in File list Array.

Select Camera model y uncommenting the #define line (Used AI Thinker in this).

Its Recommended to use External Antenna for Best use

Attach I2C LCD for best result -

  (Used 20X4 In Project)
  
  Connect VCC and GND of LCD.
  
  Connect SDA to IO2 and SCL to IO14 (Can Be updated.)
  
Code uses Teachable Machine link for Mask Detection, Update the Model according to your needs.


Project automatically loads and connects to Wifi.
Details are mentioned on LCD regarding the IP Address of Web Server.
LCD screen will provide enough information to user for Mask Detection And Face Recognition.
Web Server will act as Admin Panel which can be updated using HTML code in String.


*To Upload the code connect UOR to Tx & UOX to Tr of TTL/FTDI board and Short GND and IO0 pins to enter programming mode*
