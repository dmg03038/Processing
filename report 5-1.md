## Report 5-1 
### Pen
```pde
void setup(){
  size(500,500);
  stroke(0,0,255); // RGB
  strokeWeight(10);
}
void draw(){
if(mousePressed){
  line(mouseX,mouseY,pmouseX,pmouseY);
  }
}
```
