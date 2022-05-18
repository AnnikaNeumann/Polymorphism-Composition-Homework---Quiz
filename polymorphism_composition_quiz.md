# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
It's the ability of code to take on different forms


2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
It means that a child class could take on any form of the parent class, for example Dancer is the parent class and BalletDancer/ HipHopDancer /BreakDancer is the child class, but the different dancers can have different behaviours.


3. What can we use to implement polymorphism in Java?
We have to override the methods of the subclasses to get different behaviours.


4. How many 'forms' can an object take when using polymorphism?
I think parent class can have unlimited child classes but it's not advisable cause it gets messy.

5. Give an example of when you could use polymorphism.
We have a class called Animal (with property of name) and three different kinds such as dog, cat and bird. It's still an Animal and they all have a name, but they make different sounds (different methods).


# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?
It means that something IS PART OF  - such as windows are part of a house. Something is composed of multiple objects.

7. When would you use composition? Provide a simple example in Java.
We have a class Roof which is part of class House, cause a Roof cannot exist without a House.  

8. Give a difference between composition and aggregation?
Composition means that something IS PART OF (window is part of house) and aggregation means that something HAS A (House has a room)

9. What is/are the advantage(s) of using composition/aggregation?
Objects and classes are not tightly coupled and can be used more loosely and with a Has A relationship we can reuse the code again.

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
When we take away the wall object or fundament, then the whole house is going to fall down, because the it cannot exist without the other objects.

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
The objects can still be used I guess depending on which object is destroyed, but the objects are weakly associated with each other.
