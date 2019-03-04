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

• Establishing relationships/ dependencies between classes (and therefore objects)

• Defining the functionality that objects of the class must implement


<b> Classes </b>

• Grouping classes into subsystems

• Grouping subsystems into layers / tiers

• Keep raising the level of abstraction to lower the complexity of theproblem


# USES Relationship  

<b> 1. USES Relationship - Dependency</b>

• Student <u>USES</u> Library

• Student studies in Library

• Library provides Books


<b> 2. Classes </b>

• Student  

• Library

• Book


<b> 3. Use Objects in Code </b>

<image src='image.png' width='400px'>
 

# HAS-A Relationships - Association

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

# HAS-A Relationships - Aggregation

<b> Whole AGGREGATES Part; Part IS-PART-OF Whole </b>

• Special HAS-A relationship showing the whole and its parts

• Parts can be shared (e.g. A course can be shared by many programs)

• Parts can exist withoutthe whole (e.g. Teams are teams even when theyare not part of a game)

• Parts can exist after the whole does not (e.g. Team continues to existwhen the game has finished)

• Also called “shared aggregation”



# HAS-A Relationships - Composition

<b> Whole IS-COMPOSED-OF the part </b>

• Special type of aggregation showing strong <b> ownership </b>

• Parts CANNOT be shared. An object may be part of only one compositeat a time

-e.g. an Instructor can be part of only one college at a time

• The whole and its parts share the same lifetime: when the whole does not exist neither do its parts

-e.g. A tournament game cannot exist (be played) after the tournament has ended


