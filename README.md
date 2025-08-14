# Car Buying Decision Tree Project


## Objective
Using fundamental data structures and algorithms, solve real-world problems with trees.


## Problem    
Ahmed is going to work on the metro, but his company decided to change the office location, and unfortunately, the metro station is far away from the new office. Now he is thinking about buying a car. Help him by building a decision tree to decide which car to buy.

## Implementation

- You should build a decision tree storing the questions.
- For each question, the user will answer (input) with either yes or no.
- If the answer was no for any question, the program will print ("Don't buy the car").
- If the answer was yes, the program should move to the next question until the last one.


### Run time example

```OUTPUT
System: Do you have the car budget?   
User: Yes   
System: Do you need the car?
User: Yes   
System: Can you drive?
User: Yes
System: Do you have a driving license?
User: Yes
System:    
Buy a car
```  



## Qualification to pass
- [ ] The code should run successfully.
- [ ] Completely define the `Main` class.
- [ ] Run and test all the below test cases:
   
- [ ] Test case 1.

      System: Do you have the car budget?   
      User: Yes   
      System: Do you need the car?
      User: Yes   
      System: Can you drive?
      User: Yes
      System: Do you have a driving license?
      User: Yes
      System:    
      Buy a car
   
      
- [ ] Test case 2.

      System: Do you have the car budget?   
      User: Yes   
      System: Do you need the car?
      User: Yes   
      System: Can you drive?
      User: No
      System:    
      Don't buy a car
 




- You will be given a list of `cars` stored in an array.    
- A `car` will have the following properties:   
  `id`, `name`, `price`, `year`.
- You can find the `car` list in the `Main.java` class.  

## Implementation
   
- Build a decision tree with questions that help to decide which type of car the user should buy.
- The decision tree should store **Yes** or **No** questions.
- Read the cars from the array.
- Based on the user's answers, the system should recommend a car that meets the user's needs and preferences.
- Add your code to the `DecisionTree` and `Main` classes.
  
`cars` array

```
Car cars [] = 
        { 
            new Car(1, "Chevrolet Impala", 1999, 8.7, "action"),
            new Car(2, "Toyota Elantra", 2008, 9, "action"),
            new Car(3, "Terminator 2: Judgment Day", 1991, 8.6, "action"),

            new Car(4, "WALL·E", 2008, 8.4, "animation"),
            new Car(5, "The lion king", 1994, 8.5, "animation"),

            new Car(6, "Oppenheimer", 2023, 8.3, "drama"),
            new Car(7, "Taxi Driver", 1976, 8.2, "drama"),

            new Car(8, "Bad Boys: Ride or Die", 2024, 7.0, "comedy"),
            new Car(9, "Bad Boys", 1995, 6.8, "comedy"),
        };
```


### Run time example

```OUTPUT
System: Do you like comedy movies?   
User: No   
System: Do you like action movies?   
User: Yes   
System: Do you like old movies (before 2000)?   
User: Yes   
System:    
We recommend the following movie for you:   
Movie name: The Matrix   
Year: 1999   
genre: Action   
Rate: 8.7
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














