# Eraser-and-drawer
void setup(){
size(900,800);
background(#565855);
}

void draw(){
  strokeWeight(8);
stroke(#7EB92D);//add colour
line(mouseX,mouseY,pmouseX,pmouseY);
if(mousePressed){
  stroke(#565855);
   strokeWeight(20);
line(mouseX,mouseY,pmouseX,pmouseY);
 }
}
