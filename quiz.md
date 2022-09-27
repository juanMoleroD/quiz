## Polymorphism & Composition Homework - Quiz
### Polymorphism
What does the word 'polymorphism' mean?
- It means many forms.
What does it mean when we apply polymorphism to OO design? Give a simple Java example.
- it means we are allowing an object to take many different forms. A banana and an apple should be able to behave the same (as a fruit) in a blender. 
What can we use to implement polymorphism in Java?
- Inheritance and interfaces
How many 'forms' can an object take when using polymorphism?
- at the top level 1, but there can be an endless amount of implementations (thousands for fruits, but they are all fruits)
Give an example of when you could use polymorphism.
- when making a blender that takes in fruits to make juice.

### Composition and Aggregation
What do we mean by 'composition' in reference to object-oriented programming?
- it means favouring adding things to and object as opposed to creating the object once you have all the parts. 
When would you use composition? Provide a simple example in Java.
- whenever possible and especially when building complex objects with several dependant objects. 
Give a difference between composition and aggregation?
- composition implies that the child classes cannot exist without their parent, where as aggregation does not.
What is/are the advantage(s) of using composition/aggregation?
- composing objects allow for the Dependency inversion principle to be used.
When using composition, when an object is destroyed, what happens to all the objects it is composed of?
- they are also destroyed
When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
- the objects remain. 