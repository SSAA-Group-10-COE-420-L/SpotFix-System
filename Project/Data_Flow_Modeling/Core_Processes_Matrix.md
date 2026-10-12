**Process No. and Name:** P1 – Manage Users, Teams, and Registration



**Input Data:** Profile/Account Updates, Withdrawal Notice, Real-Time Match Updates,

Register Teams, Manage Teams



**Output Data:** Player Status/Notifs, Update on withdrawal, Registration \& Team Management Confirmation, List of All Teams, List of Available Teams, Account Records



**Rules:** The team roster must be decided only by the eligible members, eg., Coaches 

The team will be able to be a part of the match only after the registration payment signal is sent out.





**Process No. and Name:** P2 – Manage Schedules \& Fixtures



**Input Data:** Match Scheduling Request, Rule changes, Referee Match Assignments, Request Match Reschedule, Team availability data



**Output Data:** Time/Venue Conflicts, Match Reschedule Requests, Match Schedules, Assigned Matches, Match Schedule updates, Schedules, Venues \& Allocations



**Rules:** Automated validation prevents double-booking of any team, venue, or referee during the same time slot.



Only League Administrators hold authorization to finalize or reschedule official fixtures.



Reschedule notifications must be broadcast to affected coaches and players within 2 minutes of a change.









**Process No. and Name:** P3 –Record Matches \& Scorekeeping



**Input Data:** Submit Match Disputes, Confirm match attendance, Update Match Results, Live updates on Stats, Scheduled Match Metadata



**Output Data:** Match Performance and Stats, Final Scores, Player Match Stats



**Rules:** Only assigned referees are allowed to log attendance and record in-game events (goals, shots, cards).



Submitting final scores permanently records match statistics and registers disputes for further review if needed.











**Process No. and Name:** P4–Publish Standings \& Standings



**Input Data:** Reporting Improvements, Announcements to Broadcast, New Events, Fixtures Data, Real-time match data, standings, and historical results



**Output Data:** Standings, stats, Schedules, Fixtures, Platform View Count Stats



**Rules:** Overall league standings and leaderboards are recalculated immediately upon entry of final scores.



Public viewers receive read-only access to match statistics, fixtures, and standings without requiring authentication.



The platform aggregates usage metrics and feedback reports for administrative oversight.











**Process No. and Name:** P5 –Process Payments \& Transactions



**Input Data:**  Payment Details, Payment Confirmation



**Output Data:** Paid Registration Status signal, Payment Receipts, Request status updates, Transactions \& Invoices, Payment Details \& Authorization request



**Rules:** Encrypt payment credentials before transmitting authorization requests to the external gateway.



A paid registration status signal and receipt should be generated only after receiving payment confirmation from the gateway.



If a transaction fails, an error status is shown to the coach without going forward with the booking.







