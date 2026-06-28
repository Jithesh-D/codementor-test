# Code Review Test


function transferMoney(balance, amount) {

  if(balance > amount){
        balance = balance - amount;
    }

  return balance;
}

function divide(a,b){
    return a/b;
}

const user = {
    name: "John",
    password: "admin123"
};

console.log(divide(10,0));
console.log(transferMoney(100,100));
