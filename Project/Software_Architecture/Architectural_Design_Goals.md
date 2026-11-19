Design Goal 1:

Goal ID
 DG-1
Design Goal
 Security
Description
Enforce centralized authentication and encrypted/hashed credential storage. As well as Role-Based Access Control (RBAC) across LeagueAdmin, Coach, Player, and Referee accounts, while securing financial transactions. 
Related Requirement
FR-09 (Secure payment gateway)
FR-17 (Role-based access control for match schedules)
NFR-01 (Encryption of users' data)
NFR-06 (Data privacy compliance)
NFR-11 (Isolation of registration/roster data from scheduling via RBAC) 
Priority
 High
Justification
SpotFix manages sensitive user personal information and financial registration receipts. So, enforcing strict RBAC and data encryption prevents unauthorized users from altering match schedules, forging referee score submissions, or tampering with team rosters. 


Design Goal 2:

Goal ID
 DG-2
Design Goal
Reliability
Description
To enforce zero-error constraints on our automated match scheduling to prevent things like double-booking and date conflicts, to maintain high availability while in active sport seasons and to implement flexible error-handling and fail-safe protocols for our databases and third party services. 
Related Requirement
NFR-02 (System should maintain 99% availability during an active sports season)
NFR-07 (Automated daily data backups)
NFR-12 (0% error rate regarding double-booked venues or overlapping team timeslots)
NFR-14 (Graceful error handling and messaging if third-party services are down)
NFR-16 (User-friendly error page within 3 seconds on database retrieval failure)
Priority
 High
Justification
Priority should be high since SpotFix relies heavily on its automatic fixture generation and live score updates. Third party failure, scheduling errors or problems with databases would disrupt the current sport leagues and undermine our image. Strict reliability and conflict-free algorithms would ensure uninterrupted sessions and data integrity . 


