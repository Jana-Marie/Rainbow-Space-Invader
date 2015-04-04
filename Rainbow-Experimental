height = 1.5; //height of the level to be colored
bottom_height = 0.5; //height of the last level

difference(){
union(){

import("invader.stl", convexity=3); //A Space Invader for example, Replace "invader.stl" with your file/path

}
union(){

//The Object is being sliced here
translate([0,0,height])
cube([30,30,5]);
translate([0,0,0])
cube([30,30,bottom_height]);

}
}

//markers to aling the 3D-Print in the middle, dont move them, the G-Code-Interpreter will need them!
translate([37.5,30,0])
cube([2,2,1]);
translate([-12,-12,0])
cube([2,2,1]);
translate([37.5,-12,0])
cube([2,2,1]);
translate([-12,30,0])
cube([2,2,1]);
