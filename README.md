# Pisca-led
void setup() {
  pinMode (5, OUTPUT);
  //pino D5, saída
  //coloque o cabo no pino D5 do ESP ligado a perna maior do led (+)
  //coloque o outro cabo no pino GND do ESP ligado a barra negativa da protoboard (-)
  //coloque uma desistência ligada da barra (-) da protoboard a perna menor do led (-)
}

void loop() {
  digitalWrite(5, HIGH);
  //led ligado
  delay(500);
  //tempo do led ligado
  
  digitalWrite(5, LOW);
  //led desligado
  delay(500);
  //tempo do led desligado
}
