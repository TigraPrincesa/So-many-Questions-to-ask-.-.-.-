# Coin-Game

// generate a random number between 0 and 1
var number = random(0, 1);
// round the decimal to an integer
var integer = round(number);

// display the text
fill(0, 0, 0);
textSize(100);
text(number, 100, 110);
text(integer, 174, 350);

// set the coin color
if (integer === 0) {
    fill(132, 0, 255);
} 
else {
    fill(255, 255, 0);
}

