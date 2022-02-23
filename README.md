## Generative Art with p5.JS

Supplemental material and live examples

### Sample Code

```JavaScript
function setup() {
  createCanvas(400, 400);
  noLoop();
}

function draw() {
  let bg_r = random(0,255);
  let bg_g = random(0,255);
  let bg_b = random(0,255);
  background(bg_r, bg_g, bg_b ); 
}

function mousePressed(){
  redraw();
}
```
