# CODTECH-Task1
const int ledPin = 13;  // Pin for the LED
const int interval = 1000;  // Blink interval in milliseconds (1 second)

void setup() {
  pinMode(ledPin, OUTPUT);  // Set the LED pin as an output
}

void loop() {
  digitalWrite(ledPin, HIGH);  // Turn the LED on
  delay(interval);  // Wait for the specified interval
  digitalWrite(ledPin, LOW);  // Turn the LED off
  delay(interval);  // Wait for the specified interval
}

