1. The selected architectural style.
Layered Architecture: the presentation layer, application layer, and data layer.
2. Its main characteristics.
Each layer has a specific job it has to perform. This separates the concerns for each layer and lets them operate independently. 
There's hierarchical communication between each layer. 
Encapsulation: changes in one layer don't affect the work of other layers.

3. Why it is appropriate for the project.
It is in line with our previously selected process model. We selected the Incremental model to build a usable version in order to get a strong database and then release features in stages. The layered architecture lets us develop and test the features in the data and application layers independently before letting the user see them in the presentation layer. 

4. How it supports the identified design goals.
It supports DG 1 (Security) since the data layer is isolated from the application and presentation layer. The user will not be able to directly interact with the database, they have to go through the RBAC and other authentication means in the control/application layer. 
It supports DG 2 (Reliability) since all the scheduling and conflict checks are done in the application layer; if the data layer fails or any third party 
fails, the application layer catches it before it reaches the user and can display a meaningful clean message at the presentation layer.  

5. Its main advantages and potential limitations.
Advantages: 
Easy to maintain and test features since each layer can be worked on individually without affecting the other layers. 
The main back-end logic can be reused across different user account types. This allows for high reusability and simpler logic (also helps in maintenance). 
Disadvantages: 
Performance is affected since requests passing through multiple layers can add latency to time sensitive features like live score updates, and can also lead to heavier traffic. 
Any major updates to parts like the core database schematics, like their structures being changed, can require updates in the other 2 layers due to the new format of data. 
