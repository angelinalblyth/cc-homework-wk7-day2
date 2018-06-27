# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

So there is a team with players and a coach. The methods written in the team class you should be able to put the players or the coach into those methods and they will work. The players and the coach can have separate methods each to their own class. So for example a walk onto pitch method in the team class will work for both coach and players but a kick the ball method might only be available to the players class.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

3. What can we use to implement polymorphism in Java?

We can use interfaces to implement polymorphism.

4. How many 'forms' can an object take when using polymorphism?

as many as you give it?


5. Give an example of when you could use polymorphism.

When you have an animal but subclasses of cat, dog, rabbit.

# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

It is one object made up of smaller objects. Composition is a 'has-a' relationship.

7. When would you use composition? Provide a simple example in Java.

You could have it for a person, a person has a job for example.

8. What is/are the advantage(s) of using composition?

Benefit of using composition in java is that we can control the visibility of other object to client classes and reuse only what we need.

9. What happens to the behaviours when the object composed of them is destroyed?

When an object is deleted all objects that it owns is also deleted, so if you delete a person then their job is also deleted. 
