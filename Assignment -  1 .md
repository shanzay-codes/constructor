# CS304    -   Assignment No . 01 
##  Showbiz Film production System  -  UML  Class  Diagram


### Classes

** producer**
- Attributes :   - producerID :  int ,  -  budget : double
-  Functions : +  approveScript() , + allocateBudget ()

   **Director**
   - Attributes : - actorID:  int,  -  style :  String
   - Functions : +performRole(), +  rehearseDialogue()

     **Baqi  Classes ( Sirf Naam  - Attributes Optional Hain )**
     - Company
     - ScriptWriter
     - ScreenPlay
     - Scene
     - Dialogue
     - crewMember
     - Editor
     - Role
    

###  Relationships
1. Inheritance : CrewMember Parent Class Hai . Director , Editor , ScriptWriter  Is Se Inherit karte Hain.
2. Aggregation : Company <>--  Producer
3. Composition :  ScreenPlay , Scene , Scene -- Dialogue
4. Association : producer -- ScriptWriter , Director  -- Scene , Actor -- Role
5. Association :ScriptWriter Creates ScreenPlay
    
-  
