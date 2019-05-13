# Better zOO

How to use better OO design for the Zoo homework

# Summary

A guy posted a github repo link to a forum asking what we think about the OO design of his project. It was of course 
terrible, but instead of trolling it I started to think about what we can learn from his implementation and maybe
there is a way showing him how to do it a better way, or even a correct way. 

# The story

As a Zookeeper your task is to collect information about different animals living in your Zoo.

Animals can be birds, fishes, or mammals. 

An animal can have certain number of legs, teeths, and an average weight, and a type:  predator, herbivorous, or unkown.

 * A bird is like an animal, but it has certain wing length. 
 * A fish is like an animal, but it can go down certain deep in the sea it lives. 
 * A mammal is like an animal, but it has a certain hair size.

We have in our Zoo the following type of birds:
  
  * Ostrich
  * Penguin
  
We have in our Zoo the following type of fishes:

  * Barracuda
  * White shark
  
We have in our Zoo the following type of mammals:

  * AfricanBuffalo  
  * Hyppopotamus 
  * Rhinoceros 

# The task
  
As a Zookeeper you need to have an up to date list about your animals in your Zoo, so that you can answer the following questions:

  * How many living beings do I have in my Zoo?
  * How many animals do I have in my Zoo?
  * How many mammals, fishes, and birds do I have in my Zoo?
  * When going through my animals in the Zoo, can I list them by type, and see what kind of attributes they have?

# Requirements

  * Have a nice OO design
  * Use SOLID principles
  * Store the data in a database (in memory database is perfect) and access it through JDBC
  
