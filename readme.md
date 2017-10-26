reate a new web api project and do the following tasks:

 1 - Create a get route that returns your name.

 2 - Create a get route (ex "/concat/troy/amelotte") that takes a first name and a last name and concats them together into one name "troy amelotte" and returns it as json.

 3 - Create a get route (ex "/calculator/3/multiply/4") that takes a number,  a operation (add, subtract, multiply, or divide), and a 2nd number and does the operation specified. For the example above the result would be 12.

 4 - Create a post route that takes the following data and outputs the person's email.
{
    name: "Troy"
    email: "Test@test.test"
}

 5 - Create a post route called getallstudents that takes the data below and returns an array containing all previous and current students.
{
    currentStudents: ["Scott", "Ali", "David"]
    pastStudents: ["Ted", "Chris"]
}

6 - Create a post route that takes the data below and adds up every number and returns the result (as a int).
{
    nums: [ "8", "24", "hello", "14"]
}

7 - Create a post route that takes the data below and construct a new object containing the countryName and population.
{
    name: "Troy Amelotte",
age: 12,
country: "USA",
countryPopulation: 100
}

STRETCH:
Do all of the methods above in a new controller (don't use the premade value controller).
8 - Write a post route that takes the data below and outputs a list containing all strings in the values array.
