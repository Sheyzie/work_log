<!-- Work Log to track my track my task and activities on weekly basis -->

<!-- 
Template:
Week of the Month
    - Task
       -   Purpose of the task
       -   Bugs / Challenges
       -   Solution
       -   Breakthrough / Success
       -   Take away
       -   Note: [Optional] 
       -   Next Task: [Optional] 
 -->

 # Work Log

 ## Month of June
 ### Current Week
- Task: Upgrade lookup.py to go to a file directory and explore
   -  NAME: lookup.py
   -  TYPE: Side project
   -  PURPOSE: A terminal based python script to search and go to a file in a directory.
   -  CHALLENGES: Unable to get the change directory in the terminal outside the script
      -  SOLUTION: Implement menu system in the script to show navigations and allow command input by the user. 
   -  TAKE-AWAY: os.chdir() change the working directory while the script is still executing but return to the directory that run the progrm at the end of the script.
   -  CHALLENGES: cd command did not change the directory.
      -  SOLUTION: used if statement to check if the input by user is cd then run os.chdir() to change the directory
   -  SUCCESS: Project working well. Also successfully wrote the explore code block to run independently without the search.


 ## Month of May
 ### 4<sup>th</sup> Week of May
-  Task: Search For File
   -  NAME: lookup.py
   -  TYPE: Side project
   -  PURPOSE: A terminal based python script to search for files across all directories from the base directory
   -  CHALLENGES: The recursive function ends with directories without sub directories and just files
      -  SOLUTION: 
         -  Loop through the content of the directory check for sub directories and files separately
         -  Saved all directories in a list
         -  Saved all paths in an empty list passed as an argument
         -  Check if the directory is present as path in the paths list
   -  CHALLENGES: The recursive function ends when all directories in a sub directories has been fulfilled without returning to the base directory
      -  SOLUTION:
         -  Created a path history for all path and check if all paths from the last directories path are present in the path history
-  SUCCESS: Successfully searched across all direcories.
-  NEXT TASK: Allow user to go to the directory of the file.

 ## Month of April
-  TASK: Introduction to ALX_BE Program
   -  PURPOSE: Onboarding and understanding how the program is structured
   -  CHALLENGES: The process of onboarding was seamless as ALX provided a well structured LMS (Savanna) which is easy to navigate.
   -  TAKE-AWAY: Connecting to the ALX community platform is a great chance to staying updated with trends, getting resources and sharing ideas with like minds.

-  TASK: Introduction To Web
   -  PURPOSE: Learn and understand how the internet works
   -  TAKE-AWAY: Wrapping my head around the thought of the internet not as bits of data passing through different mediums (cables etc) as oppose to being in the cloud is great discovery for me. 
   -  NOTE: Open you your mind to different possibilities

 
