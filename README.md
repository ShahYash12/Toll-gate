
Thank you for choosing an automated toll gate system that uses the ESP8266, IR sensor, Ultrasonic sensor, and servo motor. This system is built using the Adafruit platform.

To get started, please follow these instructions carefully:

1. Hardware setup:

   a. Connect the ESP8266 to your computer using a USB cable and open the Arduino IDE.

   b. Install the Adafruit library by going to Sketch -> Include Library -> Manage Libraries and searching for "Adafruit".

   c. Connect the IR sensor to the ESP8266 as follows: VCC to 5V, GND to GND, and OUT to D2.

   d. Connect the Ultrasonic sensor to the ESP8266 as follows: VCC to 5V, GND to GND, TRIG to D3, and ECHO to D4.

   e. Connect the servo motor to the ESP8266 as follows: VCC to 5V, GND to GND, and SIGNAL to D5.

2. Software setup:

   a. Download the code from the following link: [INSERT LINK HERE]

   b. Open the downloaded code in the Arduino IDE.

   c. In the code, edit the following variables according to your requirements:

      i.  TOLL_AMOUNT: The toll amount to be charged.
      ii. OPEN_ANGLE: The angle at which the servo motor should open the gate.
      iii. CLOSE_ANGLE: The angle at which the servo motor should close the gate.
      iv.  MAX_DISTANCE: The maximum distance at which the ultrasonic sensor can detect an object.
      v.   SSID: The name of your Wi-Fi network.
      vi.  PASSWORD: The password for your Wi-Fi network.

   d. Upload the code to the ESP8266.

3. Testing:

   a. Power up the ESP8266 and wait for it to connect to your Wi-Fi network.

   b. Place an object in front of the Ultrasonic sensor and verify that the gate opens.

   c. Remove the object and verify that the gate closes.

   d. Pass another object in front of the IR sensor and verify that the toll amount is deducted from the user's account.

   e. If everything works as expected, your automated toll gate system is now ready to use!

We have two users created in dashboard in ada.fruit.io :
  1. Toll admin
  2. Driver
  
 1. Toll admin : Here the Distance between the car and toll is visible as well as a option to open the gate manually .
 
 2. Driver : The driver has to enter the password to open the gate .

We hope you find this guide helpful. If you have any questions or concerns, please feel free to reach out to us.

Best regards,

Yash Shah
![WhatsApp Image 2023-04-23 at 23 12 51](https://user-images.githubusercontent.com/121884963/234546491-577f9e03-1db8-4858-b30d-941f993eee08.jpeg)
![WhatsApp Image 2023-04-23 at 23 12 33](https://user-images.githubusercontent.com/121884963/234546506-78f9abb2-1d94-423b-8e6e-38f0bef48cd7.jpeg)
![WhatsApp Image 2023-04-23 at 23 12 21](https://user-images.githubusercontent.com/121884963/234546512-491aea6a-a17f-4447-86fb-a73ff437b226.jpeg)
![WhatsApp Image 2023-04-23 at 23 12 11](https://user-images.githubusercontent.com/121884963/234546518-f4cb6c06-badd-4ee7-b23f-899dc4d5dae3.jpeg)
