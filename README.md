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
              
              
              const greet = (name="Everyone") => {
    // console.log('Hello ${name}');

}
greet();

               // VARIABLE

  let a=5;
  let b=10;
  
  num=a+b;

// console.log(num);

              
                //  FUNCTION

function add(num1,num2) {
    //  console.log(num1 + num2);
}
add(10,5)


                    // OBJECT

       let users = {}
        users.name="victor"
        users['age']=28;

        // console.log(users); 
       
                //  CONDITIONAL STATEMENT IF () {

       /* if (5 > 3); {
            console.log(users);
            } 
          else if (users.name === 'victor'); {
            console.log(user.name);
        } else {
             console.log("Run this code regardless");
        } */
         
        // syntaax of Ternary operaton contional statement

        const project = 10 > 2 ? "Javascript" : "Pyton"; 
        // console.log(project);

                //    SWITCH STATEMENT
             
        /*     switch (users) {
                 case "Blessing":
                     console.log("Blessing"); 
                    break;
                 case "Nathaniel":
                     console.log("Nathaniel");
                    break;   
                 default:
                     console.log("No oher name Assigned");
            } 
 */
            //loops, in the for loop the set of condition are know before hand,in while loop, they are not known b4 hand 
                      
         //const numb = [2,4,5,6];
        //for (let i =0; i < numb.lenght; i++);
         {
            // console.log(i);
            
         }

     //
        /*  let nums = 0;

        while (nums < 5) {
            //console.log(num);
            nums++; */
            //or 
           //nums= nums + 1;

        //    DO WHILE LOOP REARLY USED THOUGH

      /*   }

        do{
      //      console.log(name);
        } while()

    */
                // COUNT OPERATION dot.lenght tell us the numbers of item an array holds

                //const numbers = [2,4,5,6,23,21];

              //  let count = 0;

           // for (let i = 0; i < numbers.lenght; i++) {

              //  count++;

        //    }

             // console.log(count);

              // To find a specific num

              //let found = false;
            //  for ( i = 0; i < numbers.lenght; i++) {
        //         if (i === 4 ){

        //             found = true;
        //         }
        // //      }

             // console.log(found);

              //     sum the value in an array


           // let sum = 0;
            //for ( let i = 0; i = sum.lenght; i++) {
              //  sum = sum + 1
          //  }
            //console.log(sum);

            // another way of writting same operation

             // a better method the FOR OFF METHOD

           // let sums = "";

           // for ( let num of numbers) {
              //  sums = sums + num;
         //  }

           // console.log(sums);

            // FINTD THE HIGHERST VALUE

           // let max = null
           // const numbers = (20, 21, 29, 23, 14)

              /*   for ( let num of numbers ) {

                    if (max === null) {

                    max = num;

                }   else if ( num > max ) {

                        max = num;

                }  
            }

           console.log(max); */


           let max = null;
           const numbers = (20, 21, 29, 23, 14);

                for ( let num = 0; num < numbers.lenght; num++) {

                    if (max === null|| numbers num = max); {

                    // OR

                    if (max === null) {

                    max = numbers(num);

                } else if ( numbers(num) > max ) {

                    max = numbers(num);

            }  
        }

       console.log(max);



       // Method

       var /they are function scoped
       var x=hello
       function word(){
           x=hello
       }
       console.log(x)they are alway decleared outside the block.
   
       let /they are blocked scope and can change
   
       var x=hello
       function word(){
           x=hello
           }
           console.log(x)
       
   
       const/ they are blocked scope but dont change.
   */
   
   
                    // HOISTING ACTIVATING A FUNCTION BEFORE IT IS INITIALIZED OR DECLEARED
   
                      /* 
                              // NORMAL
                              FUNTION sayHello() {
                               console.log("sayHello")
                              }    
                                  sayHello()
   
                                  // THIS IS HOISTING THE EXECUTABLE FUNCTION IS DECLARED BEFORE . sayHello ()
   
                                   sayHello()
   
                                  FUNTION sayHello() {
                               console.log("sayHello")
                                  
                                   //Hoisting Deosnt Work for function expression it only works on function declaraton like the above example
   
                                          var is hoisted but set to undfined
                                          let or const is not hoisted
   
                                sayHello()
   
                                /var would work but set to undfined/const sayHello = function() {
   
                                   console.log("sayHello")
                                }
   
                                  */
   
                               // Strings are any statement with a code."" or ""
   
                               let string ("say           Hello") 
                                   console.log( string.trim() ) //trim() remove space
                                      
   
                               const firstname = "lanre4real"
                               const lastname = "nonsosure"
                               
                               const real = "john for real"
                           
   
                               const fulname = firstname.concat(lastname) //concat() methid for join
   
                               console.log(fulname)
                               console.log(firstname.toupper())
                               console.log(lastname.toLowerCase())
                               console.log(real.replace('john','jane'))
                               console.log(real.length())//count the number of words including space.
                               
                               
                                         STATEMENT
                                       const numarea


                                       EXPRESSION
                              let people= "They much"   or
                            const numarea = function (l,b){ area = l*b}

    
    
    
