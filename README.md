
# GitHub_Training_Minutes

*** SW Architecture  
      
      Stories are for consistent updates Requirements are for limited updates.
      
      SRS:
            Outlines architecture elements
            Elicitation of customer requirements
            <subject> shall <capability> format
            Does not include implementation or functional details ("The How" is reserved for the SDD)
            User roles and scenarios
            Test Methods
                  Unit Tests
                  Code Review/Inspection
                  Demo
            Timeline
      
      MVC:
            Model - The backend that holds the structure
            View - Frontend that interfaces with the user and other models and controls
            Control - The "middle-end" the doing of the code. Functionality lives in the control.
      
      
*** Configuration Management
      Overview:
           
           Flow of changes and updates from "Bug Report" to Deployment/Delivery 
           SW artifacts help other devs understand the why things are they way they are
           Shows how stories in Agile Development are carried through. Must define "done" for a story
      
      
*** GitHub/Version Control Training
      
      Version Control:
            ACID
            A-> Atomic
            C-> Consistent
            I-> Isolated
            D-> Durable
            CRUD 
            C-> Create
            R-> Read
            U-> Update
            D-> Delete
      
      
      GitHub:
            Version control tool
            Allows for multiple contributors to work on the same project.
            Provides a way to resolve collisions
            Allows for isolated development of new features
            Allows for controlled continuous improvement of live products
            Grandfather article is a good resource to understand GitHub and its uses
      GitHub Structure:
            Repository is where a project lives can be synced to a local machine. 
            Branch is an isolated branch of the code base. 
            Branches can be merged into the main or live codebase
            Always look for N+1
