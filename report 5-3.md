##5-3
#learning
```pde
int num = 60;
float mx[] = new float[num];
float my[] = new float[num];

void setup() {
  size(640, 360);
  noStroke();
  fill(255, 153, 50); //RGB
}

void draw() {
  background(0); 
 
  int which = frameCount % num; //프레임카운트를 60 으로 나눈 나머지를 저장
  mx[which] = mouseX; 
  my[which] = mouseY; 
  
  for (int i = 0; i < num; i++) { 
    // which+1 is the smallest (the oldest in the array)
    int index = (which +5 + i) % num;
    ellipse(mx[index], my[index], i, i);
  }
}
```
