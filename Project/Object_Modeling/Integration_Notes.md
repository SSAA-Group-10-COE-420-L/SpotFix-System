User Hierarchy Consolidation: Merged duplicate User definitions into a single abstract superclass, with Coach, Player, LeagueAdmin, and Referee inheriting standard login and profile features via UML generalization.   
Roster & Performance Tracking: Retained the Coach -> Team -> Player management structure and attached a 1-to-1 association between Player and PlayerStats.
Tournament & Match Integration: Connected Team to Tournament via a many-to-many "participates" relationship, feeding teams directly into the Match and Venue scheduling pipeline.
Registration & Payment Processing: Placed Payment between Coach ("Makes") and Team ("Pays_Registration_for") to track registration fee status.
Match Officiating: Linked Referee to Match via an "officiated by" association to govern live stat recording and final score submissions.
Dispute Resolution Workflow: Associated Dispute directly to Match ("is about"), allowing a Coach to submit match protests for a LeagueAdmin to review.
System Announcements: Linked LeagueAdmin to Notification ("Broadcasts") to allow administrators to push announcements across the system.