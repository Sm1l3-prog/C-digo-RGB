function setup() {
  createCanvas(400, 400);
}

function draw() {
  
  let r = map(sin(frameCount * 0.05), -1, 1, 0, 255);
  let g = map(sin(frameCount * 0.03), -1, 1, 0, 255);
  let b = map(sin(frameCount * 0.01), -1, 1, 0, 255);
  background(r, g, b);
  circle (200, 200, 200) 
}
