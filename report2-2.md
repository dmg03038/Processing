##report 2-2

void setup() {
  size(150, 200);
}
int h=10;
void draw() {
  background(255);
  fill(255, 0, 0);
  text("안동대 컴공 사랑합니다!", 0, h+=speed);
  if (h>height) h=10;
}
int speed;
void keyPressed() {
  speed=key-'0'; 
}
