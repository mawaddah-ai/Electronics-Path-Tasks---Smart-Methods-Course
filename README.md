# Electronics-Path-Tasks---Smart-Methods-Course
this repository contains tasks of Electronics path with smart methods

Task 1: Tinkercad Circuit - LED Control , picture contains code +  Circuit
CODE :

void setup() {
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
  pinMode(11, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);
  delay(1000);
  digitalWrite(12, HIGH);
  delay(1000);
  digitalWrite(11, HIGH);
}
