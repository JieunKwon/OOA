# Object-Oriented Analysis (OOA)

 <b> Process </b>
  
- Step 1

• Read the requirements

• Find the objects(the nouns)

- Step2

• Read the requirements (again)

• Find relationships(proximity)

- Step 3

• Read the requirements (yet again)

• Find the methods (the verbs)


# Object-Oriented Design (OOD)

<b>   Purpose   </b>

• Grouping (generalizing, classifying) objects into classes

• Establishing relationships/ dependencies between classes (andtherefore objects)

• Defining the functionality that objects of the class must implement


<b> Classes </b>

• Grouping classes into subsystems

• Grouping subsystems into layers / tiers

• Keep raising the level of abstraction to lower the complexity of theproblem


# USES Relationship & Examples

<b> 1. USES Relationship </b>

• Student <u>USES</u> Library

• Student studies in Library

• Library provides Books


<b> 2. Classes </b>

• Student  

• Library

• Book


<b> 3. Use Objects in Code </b>

<image src='image.png' width='400px'>
 

# Relationships

<b> Association</b>

<u> HAS-A relationship </u> is called association as in two classes areassociated with each other

ex)

• Student HAS-A name

• Student HAS-A student number

• Student HAS-A laptop

class Student

{

  private String _name;

  private int_studentNumber; 

  private Laptop _computer; 

}
