int LEDRed = 6;
int LEDYellow = 5;
int LEDGreen = 4;


int LEDRed1 = 9;
int LEDYellow1 = 10;
int LEDGreen1 = 11;

void setup() {
    pinMode(LEDRed, OUTPUT);
    pinMode(LEDYellow, OUTPUT);
    pinMode(LEDGreen, OUTPUT);

    pinMode(LEDRed1, OUTPUT);
    pinMode(LEDYellow1, OUTPUT);
    pinMode(LEDGreen1, OUTPUT);

  Serial.begin(9600);

}

void loop() {
digitalWrite( LEDRed, LOW);
digitalWrite( LEDGreen, HIGH);
delay (1000);

digitalWrite( LEDGreen, LOW);
digitalWrite( LEDYellow, HIGH);
delay (3600);

digitalWrite( LEDYellow, LOW);
digitalWrite( LEDRed, HIGH);
delay (2000);

int lightlevel = analogRead(A0);
  Serial.println(lightlevel);
if (lightlevel < 30) {

  
digitalWrite( LEDRed1, LOW);
digitalWrite( LEDGreen1, HIGH);
delay (1000);

digitalWrite( LEDGreen1, LOW);
digitalWrite( LEDYellow1, HIGH);
delay (3600);

digitalWrite( LEDYellow1, LOW);
digitalWrite( LEDRed1, HIGH);
delay (2000);

}




}
