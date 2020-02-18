AirBnB clone - The console

*Welcome to the AirBnB clone project! (The Holberton B&B)*

First step: Write a command interpreter to manage your AirBnB objects.

This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration


Each task is linked and will help you to:

*put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances

*create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file

*create all classes used for AirBnB (User, State, City, Place) that inherit from BaseModel

*create the first abstracted storage engine of the project: File storage.

*create all unittests to validate all our classes and storage engine.

Whats a command interpreter?

In our case, we want to be able to manage the objects of our project:

*Create a new object (ex: a new User or a new Place)

*Retrieve an object from a file, a database etc

*Do operations on objects (count, compute stats, etc)

*Update attributes of an object

*Destroy an object

for this project we have to do an unittest for each function, you can found our tests in the github.

AUTHORS:

Iheb Mejri <1057@holbertonschool.com>

Rakia Somai <1069@holbertonschool.com>
