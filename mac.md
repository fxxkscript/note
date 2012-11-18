Mac Developer
=============

## Write Objective-C Code

1. Protocol

	Protocol methods define behavior that is independent of any particular class. Protocols simply define an interface that other classes are responsible for implementing. When your class implements the methods of a protocol, your class is said to conform to that protocol.

2. Category

	`@interface NSDate (NSDateCreation)`
	
	This line declares a category through the syntactical convention of enclosing the name of the category in parentheses. A category is a feature of the Objective-C language that enables you to extend the interface of a class without having to subclass it. The methods in the category become part of the class type (within the scope of your program) and are inherited by all the class’s subclasses. You can send a message to any instance of the class (or its subclasses) to invoke a method defined in the category.
	
## Acquire Foundational Programming Skills

* strong vs weak

	1. A strong reference indicates ownership; the referring object owns the referenced object.
	2. A weak reference implies that the referring object does not own the referenced object. 
	3. Once there are no strong references to an object, it frees that object and sets any weak references to the object to nil.
	
* Compose a static array of string objects

	`NSString *objs[3] = {@"One", @"Two", @"Three"};`
	
	You can also create arrays using the container literal @[…], where the items between the brackets are comma-separated objects.
	
	`NSArray *myArray = @[ @"Hello World", @67, [NSDate date] ];`

* compiler directive 
	
	编译器指令
	
* conform `|kənˈfɔːm|`

	符合
	
## Streamline Your App with Design Patterns

* encapsulate the aspects of system structure that vary
* program to an interface, not an implementation


