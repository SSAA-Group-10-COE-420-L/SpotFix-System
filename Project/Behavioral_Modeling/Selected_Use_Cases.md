Use Case No. UC05

Use Case Name: Updating Match Results

Primary Actor: League Administrator

Purpose: Will use the application to update match stats and results.

Reason for Selection: The backend is designed so that updating match results automatically triggers real-time updates to standings and statistics without manual intervention. The sequence diagram correctly identifies these processes.


Use Case No. UC08

Use Case Name: Registration Payment

Primary Actor: Coaches

Purpose: Will use the payment gateway of the application to pay registration fees for the tournament.

Reason for Selection: Sequence diagrams provide a good model of interaction with external services. In this use case, transactions could be between client and server, tokenized transaction processing, and a receipt confirmation trigger.


Use Case No. UC18

Use Case Name: Generate Fixture Schedule

Primary Actor: League Administrator

Purpose: Automatically generates the match schedule based on registered teams and available venues.

Reason for Selection: Schedule creation works by having multiple objects exchange messages at each step. A sequence diagram helps visualize these interactions and demonstrates important UML features.
