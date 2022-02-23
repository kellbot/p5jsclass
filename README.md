## Generative Art with p5.JS

Supplemental material and live examples

#### Draw Loop Example

<iframe src="https://editor.p5js.org/kellbot/full/OBgkvwDgW"></iframe>

```JavaScript
nothing displayed
draw example 0
let yPos = 0;
function setup() {
  // setup() runs once
  frameRate(30);
}
function draw() {
  // draw() loops forever, until stopped
  background(204);
  yPos = yPos - 1;
  if (yPos < 0) {
    yPos = height;
  }
  line(0, yPos, width, yPos);
}
```

#### No Loop Example

<iframe frameborder="0" style="height: 500px; width: 500px; margin: 0 auto; display: block;" src="https://editor.p5js.org/kellbot/full/sCHy3Rm_N"></iframe>

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
