# Reading Notes Class 06

- How would you describe an object to a non-technical friend you grew up with?
- What are some advantages to creating object literals? The advantages of using object literals to create objects include convenience, flexibility in declaration, and less code during declaration. You can drop an object literal anywhere in your program with no previous setup and it'll work
- How do objects differ from arrays? Objects represent “things” with characteristics (aka properties), while arrays create and store lists of data in a single variable.
- Evaluate the code below. What does the term this refer to and what is the advantage to using this?
 
 
 
 const dog =  {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
 }
 This code is showing the name, age and color ofa  dog in an Ul. The function is meant to show that the Spot is 14 years old in human years. It is taking the dog's age which is 2 and multiplying it by 7 ( 1 dog year is = to 7 human years). 
