# AirBnB_clone
0x00.AirBnB clone - The console

Concept Page

First step: Write a command interpreter to manage your AirBnB objects. This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…

Each task is linked and will help you to:

put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
create the first abstracted storage engine of the project: File storage.
create all unittests to validate all our classes and storage engine
The goal of AirBnB project is to eventually deploy our server a simple copy of the AirBnB Website(HBnB). A command interpreter is created in this segment to manage objects for the AirBnB(HBnB) website.

Environment

This project is interpreted/tested on Ubuntu 20.04 LTS using python3 (version 3.10.12)

Installation

Clone this repository
Access AirBnb directory: cd AirBnB_clone
Run hbnb(interactively): ./console and enter command
Run hbnb(non-interactively): echo "" | ./console.py
Description

This team project is part of alx Software Engineer program. It's the first step towards building a first full web application: an AirBnB clone. This first step consists of a custom command-line interface for data management,and the base classes for the storage of this data.

Tests

All the code is tested with the unittest module. The test for the classes are inthetest_models folder.

Functionalities of this command interpreter:

Create a new object (ex: a new User or a new Place)
Retrieve an object from a file, a database etc...
Do operations on objects (count, compute stats, etc...)
Update attributes of an object
Destroy an object
Author

    Faith nJambi
    Rop Kelvin