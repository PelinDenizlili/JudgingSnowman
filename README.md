# JudgingSnowman
visual composition using rect and ellipse functions

void setup(){
//size of the background
size(1000,1000);

//color of the background
background(#8AD4F5);


}

void draw(){
  

//the rectangle hat
fill(#FA1E1E);
rectMode(CORNERS);
rect(450,100,550,250,7);


// bottom ellipse
fill(240);
ellipseMode(CENTER);
ellipse(500,625,325,325);


//middle ellipse
ellipseMode(CENTER);
ellipse(500,425,250,250);

//top ellipse
ellipseMode(CENTER);
ellipse(500,275,175,175);


//forming of the glasses

line(412,255,588,255);

ellipseMode(CENTER);
ellipse(470,255,50,50);
ellipse(530,255,50,50);

//forming the eyes
fill(0);
ellipse(470,255,10,5);
ellipse(530,255,10,5);

//forming the arms
//left
line(400,400,250,550);
//right
line(600,400,750,550);

//snowballs formed by mouse motion
fill(255);
ellipse(mouseX,mouseY,10,10);


}
