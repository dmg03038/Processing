## dropping Circle
```pde
void setup() {
  size(200, 300);
}
int i;
void draw() {

  background(0);
  ellipse(50, i++, 80, 80);
  if (i>width)i=0;
}
```
