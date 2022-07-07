
# Synopsis:
### TASK 1 :
  Speech to text using html,css,javascript in both Arabic and English ( Example : https://s-m.com.sa/r2/test/ ) 
  using the Web Speech Recognition API, use the SpeechRecognition object to convert the speech into text and then display the text on the screen, also added WebKit Speech Recognition to perform speech recognition in Google chrome 
###  TASK 2 : 
Write Algorithm for running Wasdom ESP32, can be programmed directly from the Arduino IDE, configure ESP32 in Arduino IDE and program it to Blink an LED
# Requirements: 
-	Install Arduino IDE
-	Preparing the ESP32 Board in Arduino IDE 
### Steps:
1. Plug the ESP32 to your PC or laptob by using micro cable.
2. Go to file > preferences , put the package link to the esp32 https://dl.espressif.com/dl/package_esp32_index.json > ok
3. Go to Tools > Board > Boards Manager > from the search bar write "esp32" > click on install.
4. Go to Tools > Board > select the name of your ESP32 board.
5. Go to Tools > Port and select a COM port available.
6. write the following code in arduion editor : 

```C++
// the setup function runs once when you press reset or power the board
void setup() {
  // initialize digital pin LED_BUILTIN as an output.
  pinMode(LED_BUILTIN, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);   // turn the LED on (HIGH is the voltage level)
  delay(1000);                       // wait for a second
  digitalWrite(LED_BUILTIN, LOW);    // turn the LED off by making the voltage LOW
  delay(1000);                       // wait for a second
}
```
7.  Press the upload button.
> NOTE : I USE https://wokwi.com/projects/new/esp32 TO MAKE SURE THE CODE WORK

### Output sample for Task 1:

![output task1 en](https://user-images.githubusercontent.com/73249883/177695659-965657c9-8e46-4ae6-b04b-53f392b746c3.png)

![output task1 ar](https://user-images.githubusercontent.com/73249883/177695538-4e470049-309c-4130-9211-f137020ac9ac.png)

### Output sample for Task 2:
![output task2](https://user-images.githubusercontent.com/73249883/177695811-bb6acd79-ecb5-41bb-ba4d-502cc0c68301.png)


# Learning references
1.	https://www.youtube.com/watch?v=rwB6RqqCmXc&t=3s
2.	https://www.youtube.com/watch?v=_eXEfX1KToo&t=105s
3.	https://www.w3schools.com/css/default.asp
4.	https://www.w3schools.com/js/default.asp
5.	https://www.youtube.com/watch?v=mBaS3YnqDaU&t=10s
6.	https://www.youtube.com/watch?v=h8iHRy48a8I
7.	https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/
 


