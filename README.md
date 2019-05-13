# Better zOO

How to use better OO design for the Zoo homework

# Summary

Some universities teach OO design based on the zoo exercise: create an object oriented design of a Zoo which contains various animals (or even plants). Although the task is simple, the implementations often lacks even the very basic OO principles (like encapsulation, single responsiblity, etc.). I think we can do it better. 

# The story

As a Zookeeper your task is to collect information about different animals living in your Zoo.

Animals can be birds, fishes, or mammals. 

An animal can have certain number of legs, teeths, and an average weight, and a type:  predator, herbivorous, or unkown.

 * A bird is like an animal, but it has certain wing length. 
 * A fish is like an animal, but it can go down certain deep in the sea it lives. 
 * A mammal is like an animal, but it has a certain hair size.

We have following kind of birds:
  
  * Ostrich (Struthio camelus, avg_weight = 150, wing_length = 200, legs=2, number_of_teeth=0 )
  * Penguin (Aptenodytes patagonicus, avg_weigth = 20, wing_length=50, legs=2, number_of_teeth=0 )
  
We have following type of fishes:

  * Barracuda (Sphyraena barracuda, avg_weight = 44, number_of_teeth=24, max_depth=100, legs=0)
  * White shark (Carcharodon carcharias, avg_weight = 2000, number_of_teeth=5*48, max_depth=900, legs=0)
  
We have following type of mammals:

  * African Buffalo (Syncerus caffer, avg_weight = 600, number_of_teeth=46, hair_length=5, legs=4)
  * Elephant (Loxodonta africana, avg_weight = 5000, number_of_teeth=26, hair_length=8, legs=4)
  * Hyppopotamus (Hippopotamus amphibius, avg_weight = 1700, number_of_teeth=32, hair_length=0, legs=4)
  * Rhinoceros (Rhinocerotidae, avg_weight = 2500, number_of_teeth=28, hair_length=3, legs=4)
  

# The task
  
As a Zookeeper you need to have an up to date list about your animals in your Zoo, so that you can answer the following questions:

  * How many living beings do I have in my Zoo?
  * How many animals do I have in my Zoo?
  * How many mammals, fishes, and birds do I have in my Zoo?
  * When going through my animals in the Zoo, can I list them by type, and see what kind of attributes they have?

# Requirements

  * Have a nice OO design
  * Use SOLID principles
  * Use immutable classes, if possible
  * Use unit tests to check whether your code is good
  * +1 store data in database (a simple in-memory database is more than sufficient)
  
# How to play

  * Fork the repo and make your own solution
  * If you have any idea how we can improve the game, create a new issue
