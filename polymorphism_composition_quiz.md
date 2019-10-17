# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
means many forms

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
means that we can call more than 1 type of object. For example, a wizard can fly using several devices like broomstick, magic carpet or a dragon, each one of these devices belong to a different class. If they implement a interface called IFly, the wizard can fly any kind of device of type IFly.

public void changeRide(IFly newRide){
    this.ride = newRide;
}


3. What can we use to implement polymorphism in Java?
interfaces

4. How many 'forms' can an object take when using polymorphism?
many, there's no limit

5. Give an example of when you could use polymorphism.
same as answear 2:
For example, a wizard can fly using several devices like broomstick, magic carpet or a dragon, each one of these devices belong to a different class. If they implement a interface called IFly, the wizard can fly any kind of device of type IFly.

public void changeRide(IFly newRide){
    this.ride = newRide;
}



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?
composition establishes a relationship of has-a between objects

7. When would you use composition? Provide a simple example in Java.
for example, a Person has a Job. Job is not a property, is another object

8. What is/are the advantage(s) of using composition?
can use Polymorphism,
it's more flexible in a way that you can change something without breaking everything else,
less classes,
multiple implementations,
no conflict between methods and properties

9. When an object is destroyed, what happens to all the objects it is composed of?
the objects that are composed by another object are destroyed when the main object is destroyed.
