Meeting Notes \- 5/12/2026  
Frontend 

* Finalization Prioritization:   
  We need specs and features at the very least concepts of them out for the prototype.   
  * Core Features  
    1. Implement a Calendar   
       * Suggestion (Owen): [Google Calendar API implementation.](https://developers.google.com/workspace/calendar/api/guides/overview)   
         * (Kaitlyn) I got it, I’ve implemented Google APIs before  
           * Client ID (please don’t share with anyone…): [736502651505-7i3bu30t7b2djm1rq9v62ds6bsmsihrd.apps.googleusercontent.com](http://736502651505-7i3bu30t7b2djm1rq9v62ds6bsmsihrd.apps.googleusercontent.com)  
         * Discussion: Put a limit into it.   
       * Should take in information regarding Project deadlines & User Availability to create best suiting meeting times and Sprint durations for a user to see.   
    2. Backlog  
       * Should record a list of reports and activity across the project duration for a user to read and understand.   
       * Sub-Feature: Some optional filtering that allows a user to set a priority for logs to appear first.   
    3. Issues/Reports List  
       * A recorded list of issues or concerns made by users that can be addressed in the list itself or be turned into new tasks to generate.   
    4. Check-In Feature that factors into availability/events management.   
    5. Creating Daily Reminders that appear for a user.   
    6. AI Log  
       * Should take in general reports & tasks and possible, generate potential prompts to help in specifications in implementation.   
       * Able to track specific AI actions(?)  
    7. Recording Notes alongside specific tasks or blockers.   
       * Useful in communicating ideas or changes for 

Frontend:

* Most information primarily needed/related to the user should be *very* easily accessible.   
  * Click on one or two buttons (in HTML terms).   
* L \- shaped Graphic   
  * Information workflow goes from left to right side of the screen.  
* Blank Canvas Screen(For Now)   
  * Possibly populate Screen with intended Core Features(somehow).  

User Features: 

* New Screen (NS), Current Screen (CS), Always Accessible (AS)  
  * NS → Button leads to this thing  
  * CS → Should actively be displayed on the home page.   
  * AS → Dedicates Sub-bar that is accessible at all times.   
* **Implement a Visual Calendar of the month/current sprint.**   
  * (CS) → Gives the user an immediate reminder on specific due dates/sprints, meeting dates/times, and a mental scale of how much time is left in a week.   
  * Clearly Highlight the Sprint duration and Meeting Date.   
    * For ease of viewing, meeting info can be accessed from the calendar.   
      * Meeting Format (in person, online, hybrid)  
      * Location or Zoom Links  
      * Goal for Meeting  
      * Etc.   
* **AI Sprint Task Suggestion**   
  * (AS \- Admin Exclusive)Managers can describe upcoming project goals or deadlines, and the AI will suggest possible sprint tasks that can be placed onto the sprint calendar.  
* **AI Async Reminder & Summary**  
  * (CS) → Automatically reminds users to submit short daily updates asynchronously. AI summarizes team responses and shares both summaries and original updates with the team to improve visibility without requiring synchronous meetings.  
* Backlog  
  * (NS) → Large List of prior log history, probably too big to be handled in the home page.   
    * New Page allows for plausible filter features.   
* Issues/Reports List  
  * (NS) → Same Reasoning as Backlog.   
* **Creating an Issue/Report**  
  * (AS) → Always accessible for a user to use.   
  * Backend: Should update tasks list and priority list for specific project details.   
* **Availability Chec**k:   
  * (CS) → Pop-up for users to complete (kinda like a survey).   
    * Backend: Updated Availability/Progress Reports should update the calendar’s meeting dates/assigned tasks between users.   
* **Check-In Feature that factors into availability/events management.**   
  * (CS) → Also gives the immediate reminder of current progress for a given day.   
* Creating Daily Reminders that appear for a user.   
  * (CS)   
* AI Log  
  * (NS)  
* Recording Notes alongside specific tasks or blockers. 

User Specs: 

* Refresh System:   
  * Users are notified of when updates are made and have the option to refresh the page to see them. (Event Listener)  
  * Allows applications to constantly update, but also does not force a user to constantly refresh their page to get new information or changes.   
* Someway to handle multiple reports done in the same task.   
  * Creating Sub-Issue Reports/Tasks to handle conflicts.  
    * Either its own Sub-Report or all reports are made as drafts.   
* Notifying Blockers.   
  * Blockers \= dependencies that need to be resolved.   
  * Telling if they exist and preventing work from continuing. 

Next Meeting Date Organization: 

* Tomorrow (5/12/2026) \- Primarily In Person, come in when you are fully available.   
* Goal: Complete/Reach Near Completion of a frontend level prototype.   
  * Meaning:   
    * Have a working HTML application with some implemented features.   
    * Some Backend functionality may be worked on, but is not expected to be perfect. 