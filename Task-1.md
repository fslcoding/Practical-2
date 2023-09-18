# Practical 2, Task One

## Creating a mobile phone program

You go into a mobile phone shop to buy a phone, what options do you have?
+ _Pay as you go_ or _pay monthly_
+ Type of phone

How is the phone unique to you?
+ You are allocated a phone number

How is the account activated? 
+ The account balance is set to zero

What functions can be carried out from an account perspective?
+ Top up account
+ Make a call
+ Send a text
+ Get balance

**_Step One_**

+ Create a new Visual Studio project
+ Add another class by right clicking on the project
+ Call it Mobile.cs

![image](https://github.com/fslcoding/Practical-2/assets/62078259/1aa10fd0-4043-4581-a20a-c0714aa675b0)


**_Step Two_**

+ Now create three *string* variables, ```accType```, ```device``` and ```number```
+ Also create a *double*, called ```balance```
+ Make sure that your variables are marked as ```private```

![image](https://github.com/fslcoding/Practical-2/assets/62078259/48dffb93-0f86-400e-b0a1-9491de392333)

**_Step Three_**

+ Now you need to make a constructor
+ Add the _strings_ to the parameters of the constructor
+ Also, set the parameters, to the variables in the class:

![image](https://github.com/fslcoding/Practical-2/assets/62078259/4d7d954c-0c71-49c7-af42-28b5325b1db0)

The constructor accepts the account type, ( Pay as you go or monthly ), the name of the chosen device, and a mobile number

**_Step Four_**

+ We want to print out account information, but we may not want to print it out at the same time.
+ To solve this, we can create methods to access the variables 
+ We need a _get_ method for each of the variables
+ Each of the methods should return the variable they are referencing

![image](https://github.com/fslcoding/Practical-2/assets/62078259/449c97d3-c59f-4b34-b781-d8865581e6ca)

**_Step Five_**

+ Go back to the Program class.
+ Create a new _instance_ of the mobile class
+ The instance should be, Monthly, an iPhone 11, with a number of 123456789

![image](https://github.com/fslcoding/Practical-2/assets/62078259/beac0366-ce9d-4f11-993b-48104f4ae9b9)

**_Step Six_**

+ Print the Mobile number's details to the console

![image](https://github.com/fslcoding/Practical-2/assets/62078259/ee249c13-a9cf-4d9f-b7ba-a2046e762856)

This will output:

![image](https://github.com/fslcoding/Practical-2/assets/62078259/faed7388-48d5-41e1-ae1b-ec560fa2c18d)

**_Step Seven_**

+ Create two ```const``` double variables, called CALL_COST and TEXT_COST respectively

![image](https://github.com/fslcoding/Practical-2/assets/62078259/b656f734-e1da-471d-bf2e-08c8d73ed1ee)

**_Step Eight_**

+ Now add some more functions:
+ Top up account with credit
+ Make a call - reduces credit
+ Send a text - reduces credit

Those functions should look like this:

![image](https://github.com/fslcoding/Practical-2/assets/62078259/05a27ffa-cd19-4259-92bc-10fa859df145)

**_Step Nine_**

+ Go back to the Program class
+ Use the ```AddCredit()``` method to add 10 pounds worth of credit
+ Make some calls and texts
+ Print the balance to the console

![image](https://github.com/fslcoding/Practical-2/assets/62078259/dbe60306-16a3-4a08-875c-9156cc9e1ee0)




















