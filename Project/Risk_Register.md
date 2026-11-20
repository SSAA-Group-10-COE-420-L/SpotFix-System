**Exercise 3: Project Risks and Risk Management**

The potential risks that may affect your software project.

|**Risk ID**|**Risk Description**|**Possible Cause**|**Probability**|**Impact**|**Mitigation/Response Strategy**|
|-|-|-|-|-|-|
|**R1**|Technical difficulties in generating a match scheduling algorithm|Complex logic needed to generate tournament brackets without overlapping booked venues or team schedules.|Low/Medium/High|Low/Medium/High|Starting the 1st increment with a simple scheduling algorithm and introducing complex constraints and edge cases in later increments once the base registration and schedule generation functions are properly tested.|
|**R2**|Schedule delays i.e failing to deliver all the intended features before the semester ends|Underestimating the time required for complex features of the project, or team members having busy schedules.|Low/Medium/High|Low/Medium/High|Ensuring that the core increment i.e account creation and basic fixtures is fully functional early on, and working on secondary features like advanced tracking to later increments so that an MVP is ready for grading.|
|**R3**|Possible occurrence of scope creep as team members try to add features beyond the initial design|Changing requirements when discovering during development that stakeholders need more complex management rules to be implemented than initially discussed.|Low/Medium/High|Low/Medium/High|Sticking to the documented "Out-of-Scope" features. Any new features that creep up during early user feedback can be logged for future updates, so that it protects the current increments.|
|**R4**|Integrating third-party email notifications or SMS exceeds the project's zero-budget constraint and leads to resource limitations|Lack of access to university hosting/email servers or API rate limits|Low/Medium/High|Low/Medium/High|Sticking to simple in-app dashboard notifications for the final deliverable.|
|**R5**|Integration problems with everyone's code merging: features may break when merged during increment rollouts|No standardized database structures agreed among team members, or poor Git coordination|Low/Medium/High|Low/Medium/High|Defining clear API endpoints and strict database schemas and enforcing integration testing before each increment is merged onto the main branch.|



