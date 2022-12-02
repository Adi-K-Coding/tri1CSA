---
layout: page
title: Class Homeworks
permalink: /classhmwrk/
---


# Scores

Unit Number | My Score 
-- | -- 
Unit 1 | 0.9/1
Unit 2 | 1
Unit 3 | 0.9/1 
Unit 4 | 1 
Unit 5 | 0.85 
Total | 4.75/5

# Unit 1 - Primitives
Primitives are predefined, lowercase, "Primitives", which cannot call methods, are a value, and can be different sizes based on what primitive it is. Non primitives are defined by the coder, are uppercase, "Reference types", which can call methods, can be null, and are all the same size

### Homework
2A. 
```java
public double purchasePrice() {
  return getListPrice()*(1+taxRate);
}
```
3A.
```java
public int compareCustomer(Customer other) {
  int comparedCustomer = getName().compareTo(other.getName());
  if(comparedCustomer == 0{
    return getID() - other.getID();
  }else{
  return comparedCustomer
  }
}
```

# Unit 2 - OOP
OOP or object oriented programming is a type of programming language. Classes are a template or blueprint from which objects are created. Objects are instances of a class. Methods are a set of code that perform a specific task. Classes in java can hace data members, methods, constructors, nested classes, and interfaces. 

[Link to Homework](https://adi-k-coding.github.io/tri1CSA/jupyter/2022/11/07/OOP.html)


# Unit 3 - Boolean Expressions and If Statements
If/else statements allow you to create a code segment that has checks. If/ElseIf/Else statments can be used to decide different program outputs depending on what the user inputted. Switch statements are also an alternative method to if statements. 

### Homework
2009 3A. 
```java
private int getChargingCost(int startHour, int chargeTime)
{
 int cost = 0;
 for (int x = 0; x < chargeTime; x++){
  cost += this.rateTable[(startHour + x) % 24];
 }
 return cost;
} 
```

2017 1B.
```java
public boolean isStrictlyIncreasing(){
for (int i = 0; i < digitList.size()-1; i++){
  if (digitList.get(i).intValue() >= digitList.get(i+1).intValue()){
    return false;
   }
}
return true;
}

2019 3B.
public boolean isBalanced(ArrayList<String> delimiters){
 int openCount = 0;
 int closeCount = 0;
 for (String str : delimiters){
  if (str.equals(openDel)){
    openCount++;
  } else{
    closeCount++;
  }
  if (closeCount > openCount){
    return false;
  }
 }
 if (openCount == closeCount){
  return true;
 }
 else{
 return false;
 }
}
```
# Unit 4 - Iteration
Iteration is worth 25% of the test so its pretty important. While loops, for loops, and recursion loops are types of loops. Another example is nested iteration, which can put a loop inside another loop. 

### Homework
Part 1:
```Java
import javax.swing.JOptionPane;
import java.util.Random;

public class NumGuesser {
    Random rand = new Random();
        boolean numCorrect = false;
        String uGuess = "";
        int numGuesses=0;
    
    void run(){
        
        int randNum = rand.nextInt(1000);
        while(numCorrect==false){
            uGuess = JOptionPane.showInputDialog("Guess the number between 1-1000");
            int uGuessNum = Integer.parseInt(uGuess);
            if(uGuessNum>randNum){
                JOptionPane.showMessageDialog(null, "Guess too high, try again. Previous guess: "+uGuessNum);
                numGuesses+=1;
            }else if(uGuessNum<randNum){
                JOptionPane.showMessageDialog(null, "Guess too low, try again. Previous guess: "+uGuessNum);
                numGuesses+=1;
            }else if(uGuessNum==randNum){
                JOptionPane.showMessageDialog(null, "Correct! It took you "+numGuesses+" guesses to get it correct");
                numCorrect=true;
            }
        }
    }
    public static void main(String[] args) {
        NumGuesser ng = new NumGuesser();
        ng.run();
    }
}
```

Part Two:
![Screen Shot 2022-11-07 at 10 59 32 PM](https://user-images.githubusercontent.com/34950822/200496120-0a2aa3a8-0651-4826-b569-fb1a172ac83e.png)

# Unit 5 - Writing Classes
Classes are a blueprint for instantiating objects. An object is an istance of a class, a class defines an abstract type, methods are the behaviors you get objects to perform. Constructors create the object, are a special method for object instantiation, default constructor has no arguements. Accessor methods are getters and setters, which allow you to get values of variables and return a copy, or edit a variable. 

### Homework
2021 1A. 
```java
public int scoreGuess (String guess){
  int count = 0;
  for (int i = 0; i <= secret.length() - guess.length(); i++){
    if (secret.substring(i, i + guess.length()).equals (guess)){
        count++;
    }
}
return count * guess.length() * guess.length();
}
```

2021 3A.
```java
public void addMembers(String[] names, int gradYear ){
    
  for( String n : names ){
    memberList.add(new MemberInfo( n, gradYear, true) );
  }
}

```
# Unit 6 - Array
Notes: Common errors when making arrays include bound errors, unfilled and uninitialized arrays, when you allocate, or assign a single array variable, but not the whole array. You can use for loops to iterate through an array, by using array.length. 

### Homework
[Link to Homework](https://adi-k-coding.github.io/tri1CSA/jupyter/2022/11/07/array.html)


