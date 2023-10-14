# js-assignment1
//Question 1 
let totalvalue = 2000;
let discountpersentage  = 20;


function percentage(num, per)
{
  return  num - (num/100)*per;
}
         
console.log( " the total price after the discount is Rs:", (percentage (2000,20)));

//question 2
let username = "admin";
let password = "12345";
if  (username , password = "admin" ,"12345" )


 {
console.log("login successful" )
}
 else {
    console.log("invalid credentials")
}

//Question 3
var inr = 850
var usd = 82
{
   
   var result = (inr /  usd );
}
console.log( inr,("INR is") ,result , ( "USD"));

//question 4
//booking application for a cinema!
let numberOfChilds = 2;
let numberOfAdults = 1;
let numberOfSeniors = 1;
{
    sum = (numberOfChilds*100 + numberOfAdults*150 + numberOfSeniors*120 )
       
}
console.log(("The total ticket price is"), sum);


//quesion 5
let package = "express";
switch (package) {
 case "standard":
 console.log("delivery might take 3-5 days");
 break;
 case "express":
 console.log("The delivery might take 1-2 days");
 break;
 default:
 console.log("The delivery will be today overnight");
}


//question 6
let name = "shahid";
let email = "shahdi@gmail.com";
let age = "20";


function validateUserInformation(name, email, age) {
   
    if (typeof name !== "string") {
      console.log("Name should be a string.");
    }
    if (typeof email !== "string") {
      console.log("Email should be a string.");
    }
    if (typeof age !== "number" || isNaN(age)) {
      console.log("Age should be a number.");
    }
 
  
