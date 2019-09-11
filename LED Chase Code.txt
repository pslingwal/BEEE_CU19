void setup() {
pinMode(5,OUTPUT);
pinMode(7,OUTPUT);
pinMode(9,OUTPUT);
pinMode(11,OUTPUT);

}

void loop() {
int i=5;
for(;i<=11;i++)
{
  digitalWrite(i,HIGH);
  delay(1000);
  digitalWrite(i,LOW);
}

}