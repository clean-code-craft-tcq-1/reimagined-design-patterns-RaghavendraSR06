# reimagined-design-patterns

**Mediator Design Patterns

	1. Mediator Design patterns reduces the communication complexity between multiple objects and classes.
	2. It restricts the direct communication between the objects. All the communication will be taken care by mediator object which is created from mediator class.

Advantages:
	1. Single Responsibility Principle(SRP) can be achieved.
	2. No need to change the actual components by introducing new mediators.
	3. Reusability of the components can be achieved since they function independently. 

Disadvantages:
	1. Mediator object will be performing more operations which turns It into God Object.

Example for mediator design patterns:
Consider a real time example of buying and selling goods. If the seller want to sell goods to the buyer then the seller can communicate through a broker or a mediator who in turn searches the buyers for buying the goods.



**Builder Design pattern

	1. Builder design pattern creates a complex object by combining simple objects step by step.
	2. This is creational design pattern, which creates a final object after combining all the simple objects.
	
Advantages:
	1. Construction of objects can be reused for various products.
	2. SRP can be achieved by using this pattern.

Disadvantages:
	1. Complexity of the code increases due to creation of multiple classes.

Example for builder design pattern:
Consider a real time example of building a house. Builder builds the basement , then builds interior , then the structure of the house will be built and a complete house will be completed. Here basement, interior, structure are simple objects and a house is a complex object which is built finally.



**Decorator Design Pattern

	1. In this pattern we can add new functionality to the existing object without changing the structure. 
	2. This is an structural design pattern.
	3. It contains a decorator class which wraps original class and provides additional functionality keeping the class signature as it is.

Advantages:
	1. Functionality of object can be added without changing the class structure.
	2. SRP can be achieved using this design pattern.
	3. We can add or remove the responsibilities of object during run time

Disadvantages:
	1. Implementation of decorator is difficult in such a way as behavior does not depend on order of decorators stack. 

Example of decorator design pattern:
Consider a real time example of building a car. The car structure remains the same for all the variants. But the features of the car increases based on the variants. Here feature is the decorator which increases the functionality of car.


**Memento Design Pattern

	1. This design pattern is used to restore the state of object to the previous state.
	2. It is behavioral design pattern.
	3. Helps us to save and restore the previous state of object without implementation details.

Advantages:
	1. Helps us to maintain different object state.
	2. Helps to restore the previous object state.

Disadvantages:
	1. Increases the RAM memory when multiple memento state objects are created.
	2. Need to identify and delete the previous object state which is not required.

Example for Memento Design Pattern
	1. When you do some spelling mistake in a word file, if ctrl + z is pressed it returns to the previous state of the object, which helps the user to correct the mistakes.
	2. In an SQL if any wrong commit happens it provides a roll back functionality for restoring it into previous version.

