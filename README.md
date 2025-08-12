# Car Decision Tree Project


## Objective
Using fundamental data structures and algorithms, solve real-world problems with trees.


## Problem    
Ahmed is going to work on the metro, but his company decided to change the office location, and unfortunately, the metro station is far away from the new office. Now he is thinking about buying, and a decision tree will help him to decide.


## Implementation

- You will be given a list of questions stored in an array.    
- You should build a decision tree storing these questions.
- For each question, the user will answer (input) by either yes or no.
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









