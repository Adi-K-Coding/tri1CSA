---
layout: page
title: CSA Notes
permalink: /notes/
---



# Extra Credit Monday August 29th Write Up

Computer science is not easy. It’s a constant uphill battle, but you have to keep trying. There is always somebody better than you, who knows more syntax than you, who understands thet theory better than you, who has better internships. Therefore, it’s in your best interest to work on your own stuff, and don’t get caught up in what other people are doing. Along the way, you’ll gain really helpful problem solving skills which can be utilized in all different aspects of life. Collaboration, and working as a team are both really important skills that we can gain from this class. Additionally, you can get a lot of cool internships at places such as Northrop Grumman, as Collin and his twin sister have been doing. 

Its really hard at the start, but keeping your motivation throughout the project is the greatest advice you can take to heart. Just keep trying and trying as everybody is gonna make errors, miss a semicolon, miss a capitol S in string, because we’re all students. Sometimes the theory behind computer science is some of the hardest things to learn, but once you get that, you’re set. Google is your best friend when it comes to syntax, as almost all syntax questions can be answered online, or by other people. On that note, working with other people is also a great tool for learning new things and studying. 

I think computer science is gonna be one of the most important industries in the upcoming years. Taking high school computer science classes gives you invaluable experience, and companies all across the globe are looking for people to fill their computer science dependant roles. And it’s not just cs roles that need cs, almost all fields and jobs need some level of cs understanding, or can be significantly improved with a cs background or implementation. Thus, computer science is going to play a massive role on the global scale in the upcoming years, in countless different fields. 



# Key Vocab

* Primitives
  * char
  * int
  * double
  * boolean
  * short
  * long

* Non Primitives
  * String
  * Array
  * ArrayList
  * Queue
  * Stack

### AP Test breakdown
- Primitive Types: 2.5%–5% of test questions
- Using Objects: 5%–7.5% of test questions
- Boolean Expressions and if Statements: 15%–17.5% of test questions
- Iteration: 17.5%–22.5% of test questions
- Writing Classes: 5%–7.5% of test questions
- Array: 10%–15% of test questions
- ArrayList: 2.5%–7.5% of test questions
- 2D Array: 7.5%–10% of test questions
- Inheritance: 5%–10% of test questions
- Recursion: 5%–7.5% of test questions 


### Comments
Long Comment
```java
                    /*
                     *  This is
                     *  a long comment.
                     */
```
                
Short Comment
```java
// This is a short comment.
```

### Randoms: 
```java
Random generator = new Random();
generator.nextInt(n);
```
### Arraylists
[Link to notebook](https://adi-k-coding.github.io/tri1CSA/jupyter/2022/10/06/arraylists.html)

### APIs
[Link to notebook](https://adi-k-coding.github.io/tri1CSA/jupyter/2022/09/22/javaAPI.html)

### Java Naming Conventions:
Java uses camelCase. This is the typical naming convention when naming variables, methods, and other objects. Camel case makes the code easier to follow and read. 

### Operators:
 - public: anything outside of the class
 - private: can only be used within the class
 - protected: not used at this time

### Recursion
-  For loops
```java
for(int i=1;i<=10;i++){  
        System.out.println(i);  
    }  
```
-  While loops
```java
int i=1;  
    while(i<=10){  
        System.out.println(i);  
    i++;  
    }  
```
-  Recursion loops
```java
static int count=0;  
static void p(){  
 count++;  
 if(count<=5){  
  System.out.println(count);  
 p();  
 }  
}  
public static void main(String[] args) {  
 p();  
}  
```

### Inhertitance
![image](https://user-images.githubusercontent.com/34950822/200631617-b652dc9c-624e-4e0c-9c52-f8ad2eae1bad.png)

- The most important use of inheritance in Java is code reusability. The code that is present in the parent class can be directly used by the child class. 
- The idea behind inheritance in Java is that you can create new classes
that are built upon existing classes. When you inherit from an existing class, you can reuse methods and fields of the parent class. Moreover, you can add new methods and fields in your current class also.



