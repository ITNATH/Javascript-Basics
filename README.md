# Javascript-Basics

                         // COMMENT//

// SINGLE LINE COMMENT//   /*MULTIPLE LINE COMMENT*/


/*

              STATEMENT

STATEMENT are each line OR WORD of code WRITTEN.

*/
                   // RULES//
// MOST VARIABLE AND STATEMENT END WITH SEMI-COLUME;, FOR JAVASCRIPT ITS NOT NECCESSARY ALL THE TIME//

// let, class, function, return. are all reserved key words

// first char when naming variable must not be digit//


/*
        Varables in Javascript

These are the syntax used to represent a variable 'var const let'

in most programing language variables are ended with a corma sign ;

variable are likes diff boxes with ID(for specified identication) in an office Rack
Variable is the Main storage for data.



 'let var const'  are used to create variable(storage platform) which would enable us declare our "excutable operation"
 eg 
 
    let firstname ="tola " (inline)

          or 

    let firstname;        declared variable to accept data(multi- line)
     
    firstname= "tola";    stored data assigned

    There are two ways of writing variable
    inline
          and

    multi-line     

*/

 
let FirstMame;
let message;

firstname = "Nath is a developer"
message = "Hello"

// document.write(message)

// we can also declare and assign variables//

//typeof show the type of data//

let surname= "Nath is a developer"
let count= 9
let arr= ["2"]
let nath= true
document.write(typeof nath)

          // data types//
  //String,boolean(if alse),null, symbol, object(),array.float

       // Interactive command//
    
       
alert("Hello World")

prompt()
confirm()


 //operand operation and variables //
/*      

 * +,* OPERATOiN

 2,4 OPRAND

 let a variable

     EXPRESSION
++ incremental variable
-- decrementa variable
= " " proceed a quote/assign value/
== EQUAL TO WITH LESS ACCURACY
=== EQAULT TO WITH DETAILED ACCURACY

 UNINARY VARIABL eg -B
 BINARY VIAIABLE eg A+B
  
*/

let a= 2;
let b= 4;

let x= "a+b"

console.log("x")

/* LOOPS
FOR, WHILE, DO WHILE, FOR..IN, FOR..OF

LOOPS STATEMENT HELP YOU AVOID REAPETION
 
EG

UNSTEAD OF THIS
 WE USE LOOP eg FOR LOOP

  FOR'is a constant' / 
/i means index/
  THEN A BRACKET
(1st INPUT: INITIACIAL EXPRESSION EG i=0;
2nd input: condition i>5
3rd Incremenal statement )
4rd A CODE BLOCK{ }  
5th A STATEMENT INSIDE THE BLOCK console.log() 

*/

console.log("Hello world");
console.log("Hello world");
console.log("Hello world");
console.log("Hello world");

for(i=0;i>5;i++){
    console.log("HELLO WORLD")
}
    
        //  OBJECT can accept and multiple operation, these are the two ways to declear an operation.
  
    let user= {}
    let users = newObjeect{}
    
     //METHOD ARE KEY WORD THAT REFRENCE OTHER VALUE
     
          E.G .LENGHT 
               .THIS
       // THE{.dot AND []}SIGN IS USED TO /ADD READ AND ACCESS/
       
       let users= {}
    users.name= "victor"
    users['age']=28;

    console.log (users);
    
    
      //    function,two ways to declear function/ arrow function and declearation function.
              
                function users () {
                }
              &
              const users = ()=> {}
    
    
    
