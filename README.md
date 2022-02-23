## Generative Art with p5.JS

Supplemental material and live examples

### No Loop Example
<iframe src="https://editor.p5js.org/kellbot/full/sCHy3Rm_N"></iframe>
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
