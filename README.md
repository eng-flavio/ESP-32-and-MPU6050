# Using two MPU6050 with ESP-32 
  Code referring to the use of two MPU-6050 sensors in the ESP-32 microcontroller using a COM port.
  
  ## Prerequisites
  - C++
  - Wire library
  - I2Cdev library
  - MPU6050 library
  ## Install
  - First install all the three libraries required, if you are using  the Arduino interface go to *Sketch* ➡️ *Include Library* ➡️ *Manage Library* and search for the three
  - Make the circuit exactly like the attached schematic and connect to the PC
  <img src="https://github.com/eng-flavio/ESP-32-and-MPU6050/blob/main/esquematico.jpg" alt="texto" width="500"/>
  
  - Make sure if the correct Arduino module is selected
  - Run the program
  - Check the monitor serial, if you are seeing twelve values (per line) varying super fast then it is all ok, if you not, try to change the speed to 115200
  ## Aditional tips
   -  Open the **Device Manager** menu on windows and check the COM port, this will be very important, this communication port may vary by device
   - You can use  this together with Python (I highly recommend), MATLAB, C++ and others.
  
