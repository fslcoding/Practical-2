# Practical Two, Task Three

**_Walkthrough_**

## Create a Square class

**_Step One_**

+ Create a new project
+ In the project, create a new class called ```Square```

![image](https://github.com/fslcoding/Practical-2/assets/62078259/8ba7db17-d5f9-45fd-ac78-6faeb4c77fef)

**_Step Two_**

Add the following variables:
+ sideLength
+ area

Make sure they are private!

![image](https://github.com/fslcoding/Practical-2/assets/62078259/3675db1c-f0c1-491d-9008-cc2c01bb8bed)

**_Step Three_**

+ Add a constructor with a parameter: ```int initialSidelength```
+ Set ```sideLength``` equal to ```initialSidelength```
+ Set area equal to ```sideLength``` squared

![image](https://github.com/fslcoding/Practical-2/assets/62078259/39a53d04-e867-4f32-a273-45bf1721d137)

**_Step Four_**

+ Add a ```getArea()``` method
+ Add a ```Grow()``` method
+ In the ```Grow()``` method, set ```sideLength``` equal to double of itself.

![image](https://github.com/fslcoding/Practical-2/assets/62078259/1309297c-fce0-4e71-ab23-e8c4a8448835)

**_Step Five_**

+ Go to the Program class
+ Create a new ```Square```, with a ```sideLength``` of 4
+ Print the area of the square
+ Grow the square
+ Print the area of the square

![image](https://github.com/fslcoding/Practical-2/assets/62078259/7d40d7e5-7698-4c2b-a6ad-54e715c5d733)


**_Step Six_**

+ Run the program, and examine the results
+ Why does the program not work as you would expect?

Expected Output:
```
Square: 16
Square: 64
```




