# 10/16/2023 In Class Notes -- Javascript tutorial

- Javascript tags should either be in the head or the end of the document 
    - Either before the html/css is loaded or after
- Javascript looks at your html through a Document Object Model or a DOM
- var, works with all variable types 
- let works with variables that will update overtime 
- const is for a known constant it CANT CHANGE AND IT WONT WORK
- If you make a variable inside of a function it only works inside of the function
- If youre using apostrophes in string vars then you need to use the double quotes rather than singles 
- Beware of youre scope because if you define a global variable then change it within a function, the new variable will be "trapped inside" of the function
    - You must return the value of the variable
- Undefined means doesnt exist and null means empty 
- Once JS throws an error the code stops running there and doesnt conrtinue throughout the code
- == checks for the validity of the statement and === checks for the validity as well as the type 
    - isOn = "true"; 
        - checks for the resemblance of the word
    - isOn == true; 
        - checks that it it either equals true as a boolean or true as a string 
    - isOn === true;
        - checks that it is a boolean And it is true 
- i++ is shorthand for i+1 i-- is shorthand for i-1
- i+= is shorthand for i = i+3 
- beware of infinate loops 
    - your condition must eventually evaluate to false in order to exit and avoid this looping problem
    
