# LED-blink-project-3-leds-
blink the led with Arduino 
int led1=11; //global variable int led2=12; 
int led3=13; 
void setup() { 
pinMode(led1, OUTPUT); //initialize digital pin 13 as an output.
 pinMode(led2, OUTPUT);
 pinMode(led3, OUTPUT);
 }
 void loop() { 
digitalWrite(led1, HIGH); // turn the LED on (HIGH is the voltage level 
digitalWrite(led2, HIGH);
 digitalWrite(led3, HIGH);
 delay(1000); //wait for a second
 digitalWrite(led1, LOW); //turn the LED off by making the voltage LOW
 digitalWrite(led2, LOW); 
digitalWrite(led3, LOW);
 delay(1000);
 //wait for a second
 }
