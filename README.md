# javascript-test-0005-final-13290-aditya
Final Project Assignment - This repository contains the complete final project code 
function printPattern(rows) {
    let count = 1;

    for (let i = 1; i <= rows; i++) {
        let rowOutput = ""; 
        
        for (let j = 1; j <= i; j++) {
            rowOutput += count + " "; 
            count++;
        }
        
        console.log(rowOutput.trim());
    }
}
printPattern(5);
