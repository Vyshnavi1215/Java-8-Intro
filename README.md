## Java-8-Introduction
### Classes:
- Class is the collection of data about a particular entity(object).
- java is very passionate about classes
- For example Car,car will have properties like color, company,name, weight etc, and some of the functionalities like start, drive, break.
- So, the properties would be defined as variables and the functionalities would be the methods. encapsulating these variables and methods together we call as Class.
- Class is the natural home of data and the methods.
- Class is declared by using keyword 'class'.
#### Example : 
```
class className{
type variable 1; //variables, type :type defines the datatype of value(Datatype : defines which type of data that the variable can hold like interger, string)
type variable2;//variables
  method1(){
    //code to written
  }
}
```
- Variables : Variables are the identifiers and they store the data.
- Methods : code to perform the particular task.
- How to create an object for a class :
- First..What is an object??
- An object is an instance of the class, an oblect has physical reality(object occupies space).
### Objects are created in two steps :
1. Declare the variable of the class type.
2. Allocate the memory of that particular class object.
- Considet the class named Car, object of car can be created as follows.
```
1.1 Car car;
2.1 car = new Car();
```
- In the line 1.1 car value would be null, in second line we are actually allocating the reference to the object to refer.
### new keyword :
- new operator allocates the memery dynamically at run time for the object.
### Package :
- What is a package??
- Package is a container, which is used to group together diffent classes that belong to general area.
