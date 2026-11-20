**ID:** T1



**Task Name:** Requirement consolidation and increment planning



**Description:** Merge the FR’s, NFR’s, and UC’s and then assign them to increment 1, 2, or 3



**Predecessor(s):** –



**Duration (Days):** 3





**ID:** T2



**Task Name:** Database design and object modeling



**Description:** Design schema for D-1, D-2, D-3, D-4. Work out the main things the system keeps track of (teams, players, matches, and payments)



**Predecessor(s):** T1



**Duration (Days):** 3





**ID:** T3

**Task Name:** Architectural and UI design 



**Description:** Plan how the system will be split into parts (architectural design). Design the screens that each type of user will see 



**Predecessor(s):** T1



**Duration (Days):** 3



**ID:** T4

**Task Name:** User Login and Access Control 



**Description:** Build the login, so each type of user only sees what they are allowed to see. 



**Predecessor(s):** T2, T3



**Duration (Days):** 3





**ID:** T5

**Task Name:** Team and Player Registration System



**Description:** Build team registration, adding and removing players, and account updates. 



**Predecessor(s):** T4

**Duration (Days):** 4





**ID:** T6

**Task Name:** Payments and Transactions System



**Description:** Build the payment step for team registration, connected to the payment gateway. Create a receipt after payment is confirmed. 



**Predecessor(s):** T5

**Duration (Days):** 4





**ID:** T7

**Task Name:** Scheduling and Fixtures System



**Description:** Build match scheduling, with checks so a team or venue is never booked twice at the same time. 



**Predecessor(s):** T5

**Duration (Days):** 5





**ID:** T8

**Task Name:** Notifications System



**Description:** Tell coaches and players when a match is rescheduled. Let the admin send announcements. 



**Predecessor(s):** T7

**Duration (Days):** 3





**ID:** T9

**Task Name:** Match Recording and Standings System



**Description:** Let referees record scores and match events. Update the league standings and player statistics right after the final score is entered. 



**Predecessor(s):** T7

**Duration (Days): 5**





**ID:** T10

**Task Name:** Public Views and Reporting system



**Description:** Show fixtures, results and standings to viewers. Let users search for games, download schedules, submit disputes, and report improvements. 



**Predecessor(s):** T9

**Duration (Days):** 4





**ID:** T11

**Task Name:** Integration \& Testing 



**Description:** Connect all the systems and test the whole system. Find bugs and check that every requirement is met. 



**Predecessor(s):** T4,T5,T6,T7,T8 T9, T10



**Duration (Days):** 4





**ID:** T12

**Task Name:** Documentation \& Deployment Preparation 



**Description:** Write the instructions for using the system and the test results. Get the system ready to go live. 



**Predecessor(s):** T11

**Duration (Days):** 3

