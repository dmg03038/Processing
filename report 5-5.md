## Bouncy

```pde
PGraphics pg;

void setup() {
  size(400, 400);
  pg = createGraphics(300, 300);
}

void draw() {
  pg.beginDraw();
  pg.background(102);
  pg.stroke(0);
  pg.strokeWeight(20);
  if(mousePressed){
  pg.ellipse(pg.width*0.5, pg.height*0.5, mouseX, mouseY);
  }
  pg.endDraw();
  image(pg, 50, 50); 
}
```
