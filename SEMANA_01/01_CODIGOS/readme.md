void setup() {
  pinMode(13, OUTPUT);    // configura o pino digital 13 como saída
  pinMode(12, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);
  digitalWrite(12, LOW);
  delay(1000);            // espera por um segundo
  digitalWrite(13, LOW); 
  digitalWrite(12, HIGH);
  delay(1000);          
}