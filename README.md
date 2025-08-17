# Car Buying Decision Tree Project


## Objective
Using fundamental data structures and algorithms, solve real-world problems with trees.


## Problem    
Ahmed is going to work on the metro, but his company decided to change the office location, and unfortunately, the metro station is far away from the new office. Now he is thinking about buying a car. Help him by building a decision tree to decide which car to buy.


- You will be given a list of `cars` stored in an array.    
- A `car` will have the following properties:   
  `id`, `name`, `price`, `type`.
- You can find the `cars` list in the `Main.java` class.  

## Implementation
   
- Build a decision tree with questions that help to decide which car the user should buy.
- The decision tree should store **Yes** or **No** questions.
- Read the cars from the array.
- Based on the user's answers, the system should recommend a car that meets the user's needs and preferences.
- Add your code to the `DecisionTree` and `Main` classes.
  
`cars` array

```java
Car cars [] = 
        { 
            new Car(1, "Toyota Elantra", 60000, "sedan"),
            new Car(2, "Chevrolet Impala", 150000, "sedan"),
            new Car(3, "Mercedes S Class", 1200000, "sedan"),


            new Car(4, "Kia Sportage", 150000, "suv"),
            new Car(5, "Audi Q7", 1200000, "suv"),
            new Car(6, "Toyota Rav4", 60000, "suv"),


            new Car(7, "Lamborghini Urus", 1200000, "sport"),
            new Car(8, "Chevrolet Corvette",  150000, "sport"),
            new Car(9, "Dodge Charger", 60000, "sport"),
        };
```


### Run time example

```OUTPUT
System: Would you like the SEDAN car type?
User: No   
System: Would you like the SUV car type?
User: No   
System: Would you like the SPORTS car type?
User: Yes   
System: Are you willing to spend more than 60000?
User: Yes   
System: Are you willing to spend more than 150000?
User: Yes
System:

We recommend
Car name: Lamborghini Urus
Price: 1,200,000 SAR
This car fits your preferences and needs.

```  

Based on the user's answers, the recommended car should match the following properties,
- Type: Sport
- Price: 1200000.
- Name: Lamborghini Urus.


## Qualification to pass
- [ ] The code should run successfully.
- [ ] Completely define the `DecisionTree` class.
- [ ] Completely define the `Main` class.
- [ ] Run and test all the below test cases:
   
- [ ] Test case 1.

      System: Would you like the SEDAN car type?
      User: No   
      System: Would you like the SUV car type?
      User: No   
      System: Would you like the SPORTS car type?
      User: Yes   
      System: Are you willing to spend more than 60000?
      User: Yes   
      System: Are you willing to spend more than 150000?
      User: Yes
      System:

      We recommend
      Car name: Lamborghini Urus
      Price: 1,200,000 SAR
      This car fits your preferences and needs.
    
- [ ] Test case 2.
      
      System: Would you like the SEDAN car type?
      User: Yes   
      System: Are you willing to spend more than 60000?
      User: No   
      System:

      We recommend
      Car name: Toyota Elantra
      Price: 60,000 SAR
      This car fits your preferences and needs.
      
- [ ] Test case 3.
      
      System: Would you like the SEDAN car type?
      User: No   
      System: Would you like the SUV car type?
      User: No   
      System: Would you like the SPORTS car type?
      User: Yes   
      System: Are you willing to spend more than 60000?
      User: No   
      System:

      We recommend
      Car name: Dodge Charger
      Price: 60,000 SAR
      This car fits your preferences and needs.












