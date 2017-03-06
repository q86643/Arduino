# Arduino
void setup()
{
  for (byte i = 0; i<= 7; i++) {
pinMode(i, OUTPUT);
}
  for (byte i = 0; i<= 7; i++) {
digitalWrite(i,LOW);
}
}
void loop()
{
    for(int i=0;i<8;i++){
    digitalWrite(i,HIGH);
	delay(500);
    digitalWrite(i,LOW);
  }
  
  ///
  
    for(int i=0;i<8;i++){
    digitalWrite(i,HIGH);}
    delay(500);
     for(int i=0;i<8;i++){
    digitalWrite(i,LOW);}
  delay(500);
    for(int i=0;i<8;i++){
    digitalWrite(i,HIGH);}
    delay(500);
     for(int i=0;i<8;i++){
    digitalWrite(i,LOW);}
  delay(500);
  ////
  ////
  for(int i=8;i>=0;--i){
    digitalWrite(i,HIGH);
 	delay(500);
    digitalWrite(i,LOW);
  }
  //
   for(int i=0;i<8;i++){
    digitalWrite(i,HIGH);}
    delay(500);
     for(int i=0;i<8;i++){
    digitalWrite(i,LOW);}
  delay(500);
    for(int i=0;i<8;i++){
    digitalWrite(i,HIGH);}
    delay(500);
     for(int i=0;i<8;i++){
    digitalWrite(i,LOW);}
  delay(500);
  
  
  //
