const prompt = require('prompt-sync')();
// taking input from user
const number = prompt('Enter a positive number: ');
// if number == 1
if(number==1){
    console.log(`${number} is neither prime nor composite`);
}
// if number is less than 1
else if(number < 1){
    console.log(`${number} is not a prime number.`);
}
else{
    for(let i=2; i<number; i++){
        if(number%i == 0 ){
            var res = `${number} is not a prime number.`;
            break;
        }
        else{
            var res = `${number} is a prime number.`;
        }
    }
    console.log(res);
}
