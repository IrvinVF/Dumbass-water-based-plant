int humedad;

void setup() {

for (int i = 8; i<=13; i++) {
  pinMode(i, OUTPUT);
   
}
 Serial.begin(9600);

}

void loop() {
 humedad = analogRead(A0);

 Serial.println(humedad);
 delay(500);
  if (humedad<300) {
    digitalWrite(11, HIGH);
    digitalWrite(10, HIGH);
    digitalWrite(13, LOW);
    digitalWrite(12, LOW);
    noTone(9);
  Serial.println("Ya con eso gracias tqm c:");
}
else {
   digitalWrite(11, LOW);
    digitalWrite(10, LOW);
    digitalWrite(13, HIGH);
    digitalWrite(12, HIGH);
    tone(9, 500);
    delay(200);
    digitalWrite(13,LOW);
    digitalWrite(12,LOW);
    tone(9, 380);
    delay(200);
  Serial.println("DAME AGUA TONTO! >:(");
  analogWrite(7, HIGH);
    }
}
