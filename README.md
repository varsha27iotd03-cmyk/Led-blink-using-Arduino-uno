# Led-blink-using-Arduino-uno
// LED Blink Example  // Pin number where LED is connected int ledPin = 13;  void setup() {   // Initialize the digital pin as an output   pinMode(ledPin, OUTPUT); }  void loop() {   digitalWrite(ledPin, HIGH);  // Turn the LED on   delay(1000);                  // Wait for 1 second (1000 milliseconds)   digitalWrite(ledPin, LOW) delay (1000);
