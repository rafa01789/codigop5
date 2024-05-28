# codigop5


var count = 0;
var cor = '#78008A';
  
function draw () {
    
    stroke(cor);
    var x1 = random(300) - 75;
    var y1 = random(300) - 75;
    var x2 = random(300) - 75;
    var y2 = random(300) - 75;

    line(x1,y1,x2,y2);
    count++
    
    if (count > 1000) {
        count = 0;
        if (cor == '#78008A') { 
            cor = "#FFFFFF";
        } else {
            cor = '#78008A';
        }
    }
    
}
