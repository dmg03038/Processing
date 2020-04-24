##Text Banner

```pde
void setup() {
  size(500, 500);
  textSize(50);
}
int i;
void draw() {
  background (0);
  text("Andong", i++, 200);
  if (i==width) {
    i=0;
  }
}
```
