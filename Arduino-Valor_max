float pre=0;
float maxx;
float post;
void setup() {
  Serial.begin(9600);

}

void loop() {
  
  
  float tem=random(0,150);
  

  post=tem;
  
if(post>pre)
{
  maxx=post;
  pre=post;
}

Serial.println(maxx);
delay(1000);
}
