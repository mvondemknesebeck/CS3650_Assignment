# CS3650_Assignment

## Banner Registration Usability Test & SUS
System Tested: Banner Registration Portal

Survey Link: https://docs.google.com/forms/d/e/1FAIpQLSczr0auRnH7vXIX8HOUgWYd3biXW138nMQWrqyWDf-j77UTaw/viewform?usp=publish-editor

Logging Sheet: empirical_usability/usability_logging_sheet.csv

### Step 1: Study Scope & Participant Screener
This study tests how easily students can use the Weber State Banner Registration system to search for classes, build a schedule, and manage enrollment of classes.

Task 1: Find an open class for a computer science course for next semester and enroll in it.


Task 2: Remove a course from the current schedule and verify the credits were reduced.

Participant Screener Survey

Goal: Recruit 3 to 5 students with different registration experience levels.

Question 1: What is your current year in school?
- Freshman
- Sophomore
- Junior/Senior
- Graduate/No Degree (Exclude these people)

Question 2: What is your experience with registration portals?
- First time
- 1 to 3 semesters
- 4 or more semesters
 
Question 3: How do you pick out which classes to take before registering?
- Written answer.

Question 4: Do you use any tools or settings to help you with browsing websites like a screen reader, zoom, etc?
- Yes, then answer which one.
- No
  
Question 5: Are you available for a test session and okay with being observed for research?
- Yes
- No

### Step 2: Moderator Script and Tasks
Welcome Script:

"Hello, and thank you for helping with this usability test today. Before we start I want to go over a few things with you.

First this is completely voluntary and you can take a break or stop at any time without penalty.

Second, we are testing the Weber State Banner registration website and not you or your abilities. If something is confusing or hard to find then the issue is with the website and not you.

Third, with your permission I will record your screen and voice while taking notes. Your name and student number won't be saved anywhere and your data will be kept private with a special code to identify you. Do you have any questions and are you okay to start?"

Think Aloud Instructions:

"As you work through all the tasks, please think aloud when you can. Tell me what you are looking at, what you expect to happen, and what confuses you. Please act like you are doing this by yourself since I can't assist or answer questions. I may speak to you if you get quiet."

Moderator can say these if the subject is quiet for too long:
- What are you thinking?
- What are you expecting to see?

Tasks Examples:

These will ignore certain words seen in the program to avoid interfering in their decisions.

- Task 1: "Enrollment opened for the upcoming term and you need to use the portal to find a 3 credit computer science course that can be taken after 1PM on Tuesdays and Thursdays and has open seats. Then finalize the enrollment."
- Task 2: "You noticed on of your courses overlaps with your work schedule. Find the class, remove it, and check that the credits updated."

### Step 3: Metrics and Data Logging Sheet
All observations are tracked in the empirical_usability/usability_logging_sheet.csv

Quantitative Metrics:
- Participant ID: Anonymous code (P01 to P05)
- Assistance_Used: Any tools used.
- Task ID: Which task is being tested.
- Task_Time_sec: Total seconds from when the participant starts the task until they finish.
- Task_Success_Code: 1.0 = Finished by themselves, 0.5 = finished with help, 0.0 = couldn't finish.
- Error_Count: Number of wrong clicks/mistakes.
- SEQ_Score: After task rating from 1 being hard to 7 being easy.

Qualitative Observations:
- Facial_Expressions: Signs of confusion or frustration.
- Verbal_Noises: Sounds of confusions, sighing, or surprise.
- Physical_Hesitation: Pausing with the mouse for more than 3 seconds or scrolling a bit.
- Posture_Change: Leaning in close to read or leaning back in frustration.

### Step 4: SUS Survey
After finishing both the tasks, the participants will complete the 10 question google form.

1. I think that I would like to use this system frequently.
2. I found the system unnecessarily complex.
3. I thought the system was easy to use.
4. I think that I would need a tutorial to be able to use this system.
5. I found the various functions in this system were well integrated.
6. I thought there was too much inconsistency in this system.
7. I would guess that most people would learn to use this system very quickly.
8. I found the system very difficult to use.
9. I felt very confident using the system.
10. I needed to learn a lot of things before I could start using this system.

How the SUS Score is calculated:
- Odd questions: Take the users score and subtract 1.
- Even questions: Take 5 minus the users score.
- Final score: Add all converted numbers together and multiply by 2.5 to get a score from 0 to 100.

### Step 5
