# arduino-button-ile-led-yakmak

int buton_durumu=0;
void setup() {
  pinMode(7,INPUT);
  pinMode(6,OUTPUT); 

}

void loop() {
 buton_durumu=digitalRead(7);
 if(buton_durumu==0){
digitalWrite(6,1);

 }
else{
  digitalWrite(6,0);
}

}
