//Exercise 1



 for (let i = 1; 1 <= 100; i++) {
     if(i % 2 == 1) {
         console.log(i);
     } else {
         continue;
     }  
 }

// Exercise 2

 for (let i = 1; i <= 100; i++) {
     if (i % 3 == 0 && i % 5 == 0) {
         console.log("Fizzbux"); 
     } else if (i % 3 == 0) {
         console.log("Fizz");
     } else if (i % 5 == 0) {
         console.log("Buzz");
     } else {
         console.log(i);
     }
 }