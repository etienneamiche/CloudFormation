# DDD at a glance

DDD: Domain driven design

http://naa4e.codeplex.com

- Domain model

Un modèle de domaine est un système d’abstractions qui décrit certains aspects d'un domaine de connaissance, d'influence ou d'activité 4. Le modèle peut alors être utilisé pour résoudre des problèmes liés au domaine. Le modèle de domaine est une représentation de concepts significatifs du monde réel et qui concernent le domaine à modéliser dans le logiciel. Les concepts incluent les données concernées par l’activité et les règles métier en rapport avec ces données.

Un modèle de domaine utilise généralement le vocabulaire du métier pour que ses représentations puissent être utilisées pour communiquer avec des parties prenantes non techniques.

- Object oriented model

The object-oriented model is based on a collection of objects, like the E-R model.
An object contains values stored in instance variables within the object.
Unlike the record-oriented models, these values are themselves objects.
Thus objects contain objects to an arbitrarily deep level of nesting.
An object also contains bodies of code that operate on the the object.
These bodies of code are called methods.
Objects that contain the same types of values and the same methods are grouped into classes.
A class may be viewed as a type definition for objects.
Analogy: the programming language concept of an abstract data type.
The only way in which one object can access the data of another object is by invoking the method of that other object.
This is called sending a message to the object.
Internal parts of the object, the instance variables and method code, are not visible externally.
Result is two levels of data abstraction.
For example, consider an object representing a bank account.

The object contains instance variables number and balance.
The object contains a method pay-interest which adds interest to the balance.
Under most data models, changing the interest rate entails changing code in application programs.
In the object-oriented model, this only entails a change within the pay-interest method.
Unlike entities in the E-R model, each object has its own unique identity, independent of the values it contains:
Two objects containing the same values are distinct.
Distinction is created and maintained in physical level by assigning distinct object identifiers.


- Functional model

In systems engineering, software engineering, and computer science, a function model or functional model is a structured representation of the functions (activities, actions, processes, operations) within the modeled system or subject area.
A function model, similar with the activity model or process model, is a graphical representation of an enterprise's function within a defined scope. The purposes of the function model are to describe the functions and processes, assist with discovery of information needs, help identify opportunities, and establish a basis for determining product and service costs.

- CQRS

Le pattern CQRS (Command Query Responsibility Segregation) repose sur un principe simple : la séparation, au sein d’une application, des composants de traitement métier de l’information (“command” / écriture) et de restitution de l’information (“query” / lecture). Ce seul principe fournit un cadre d’architecture extrêmement intéressant pour le développement d’applications, en levant un certain nombre de contraintes et en faisant apparaître de nouvelles opportunités.

- 3 tier
- 2 tier



## Ubiquitous Language :

Vocabulary of domain specific terms, shared by all parties involved,used in all forms of spoken and written communication. Used everywhere : user stories, meeting, emails, source code. 

The language is defined in documents available to everyone in the project docs.

No ambiguity, No synonyms.Avoid acronyms

