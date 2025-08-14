# Car Buying Decision Tree Project


## Objective
Using fundamental data structures and algorithms, solve real-world problems with trees.


## Problem    
Ahmed is going to work on the metro, but his company decided to change the office location, and unfortunately, the metro station is far away from the new office. Now he is thinking about buying a car. Help him by building a decision tree to decide which car to buy.

## Implementation

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

```
Car cars [] = 
        { 
            new Car(1, "Toyota Elantra", 60000, sedan),
            new Car(2, "Chevrolet Impala", 150000, sedan),
            new Car(3, "Mercedes S Class", 1200000, sedan),


            new Car(4, "Kia Sportage", 150000, suv),
            new Car(5, "Audi Q7", 1200000, suv),
            new Car(6, "Toyota Rav4", 60000, suv),


            new Car(7, "Lamborghini Urus", 1200000, sport),
            new Car(8, "Chevrolet Corvette",  150000, sport),
            new Car(9, "Toyota Elantra", 60000, sport),
        };
```


### Run time example

```OUTPUT
System: Would you like the SEDAN car type?
User: No   
System: Would you like the SUV car type?
User: No   
System: Would you like the SPORT car type?
User: Yes   
System: Are you willing to spend more than 60000?
User: Yes   
System: Are you willing to spend more than 150000?
User: Yes
System:

We recommend
Car name: Lamborghini Urus
Price: 1200000SAR
This car fits your prefrences and needs.





```  

Based on the user's answers, the recommended movie should match the following properties,
- Genre: action movie.
- Year: before 2000.

When searching for a movie with the above properties, The system will pick the most rated movie.   



## Qualification to pass
- [ ] The code should run successfully.
- [ ] Completely define the `DecisionTree` class.
- [ ] Completely define the `Main` class.
- [ ] Run and test all the below test cases:
   
- [ ] Test case 1.
   
      System: Do you like comedy movies?   
      User: No 
      System: Do you like action movies?   
      User: Yes  
      System: Do you like old movies (before 2000)?   
      User: Yes   
      
      System:       
      We recommend the following movie for you:   
      movie name: The Matrix   
      year: 1999   
      genre: Action   
      Rate: 8.7   
   
- [ ] Test case 2.

      System: Do you like comedy movies?   
      User: No 
      System: Do you like action movies?   
      User: No 
      System: Do you like animated movies?   
      User: Yes   
      System: Do you like old movies (before 2000)?   
      User: Yes 
         
      System:       
      We recommend the following movie for you:   
      movie name: The Lion King   
      year: 1994      
      genre: Animated   
      Rate: 8.5  

- [ ] Test case 3.

      System: Do you like comedy movies?   
      User: No 
      System: Do you like action movies?   
      User: No  
      System: Do you like animated movies?    
      User: No   
      System: Do you like drama movies?   
      User: Yes   
      System: Do you like old movies (before 2000)?   
      User: No  
         
      System:       
      We recommend the following movie for you:   
      movie name: Oppenheimer   
      year: 2023      
      genre: Drama   
      Rate: 8.3  














