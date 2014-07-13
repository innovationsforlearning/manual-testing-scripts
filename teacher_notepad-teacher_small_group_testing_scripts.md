# TeacherMate - Teacher Notepad - Teacher Small Group

## Tests

### Login Workflow

1. Open App - *Expect Splash Screen to load*
* App Loads - *Expect app to be viewed only in landscape mode*
* Click on **Tap to Login** at top of screen - *Expect Splash Page Screen to switch to Login Screen*
* Enter Username into **teacher username** input field: johnteacher
* Enter Password into **teacher password**: 1234
* Click *login* button - *Expect App Menu Screen to load with three options: Teacher Conference, Teacher Small Group, and Partner Station Scoring*
* *Expect syncing screen to pop up.*
* *Expect syncing duration to be 1 - 5 min*

### Teacher Login Conflict Workflow

1. Follow the LOGIN WORKFLOW on one iPad
* Follow the LOGIN WORKFLOW on another iPad - *Expect that if teacher is logged in elsewhere, alert pops up*
* *Expect pop-up to read: "Publish, Teacher(johnteacher) is already login in other device.login with another account"*

### Access Teacher Small Group Workflow

1. Follow the LOGIN WORKFLOW
* Click on **Teacher Small Group** option - *Expect to see a table of groups*
* Sort col by **Group Name** - *Expect the columns to sort by Group Name*

### Adding New Group Workflow

1. Follow LOGIN WORKFLOW
* Follow ACCESS TEACHER SMALL GROUP WORKFLOW
* Click on **Add New Group** - *Expect the screen to switch to Add Group Screen*
* Click into the **Add a new Group name** field - *Expect pop-up field to allow for submitting Group Name*
* Click into the **pop-up field** - *Expect flashing cursor to enter the field*
* Type in a group name - *Expect typed text to appear in pop-up field*
* Click the **OK** button - *Expect pop-up field to go away and new name to be present in Add a new Group name field*
* Click on a few student names from the **Click on one or more Students* column (on right side of screen) - *Expect a checkmark to fill each checkbox next to chosen students' names)*
* Click on the **Create New Group** button - *Expect the new group to appear in the Click on Group Name or add a new Group name below column (on left side of screen*

### Change Students in a Group Workflow

1. Follow LOGIN WORKFLOW
* Follow ACCESS TEACHER SMALL GROUP WORKFLOW
* Click on **Add New Group** - *Expect the screen to switch to Add Group Screen*
* Click on an existing Group (on the left column) - *Expect a checkmark to enter checkbox for selected Group and Student members of Group to be checked in the left column*
* Click on the checkbox of an existing student - *Expect the checkmark to be removed from the Student checkbox*
* Click on the checkbox of a new student - *Expect the checkmark to be added from the Student checkbox*
* Click on the checkbox of a different group - *Expect a checkmark to enter checkbox for selected Group and Student members of Group to be checked in the left column*
* Click back to the original group you chose - *Expect a checkmark to enter checkbox for selected Group and Student members of Group to be checked in the left column*

### Start Small Group Start Session Workflow

1. Follow LOGIN WORKFLOW
* Follow ACCESS TEACHER SMALL GROUP WORKFLOW
* Click on the **Start Session** Button - *Expect to see either the message "Waiting for students to log in" or that a linked student card is at the top of the screen*

### Delete Group Workflow

1. Follow LOGIN WORKFLOW
* Follow ACCESS TEACHER SMALL GROUP WORKFLOW
* Follow the SMALL GROUP START SESSION WORKFLOW
* Click on **Add New Group** - *Expect the screen to switch to Add Group Screen*
* Click on an existing Group (on the left column) - *Expect a checkmark to enter checkbox for selected Group and Student members of Group to be checked in the left column*
* Click on the **Delete** button - *Expect a confirm alert to pop-up that reads "Delete Group: Are you sure you want to delete the Group [Group Name]"*
* Click the **OK** button - *Expect the deleted group to be removed from the left columnn*

### Edit a Group Name Workflow

1. Follow LOGIN WORKFLOW
* Follow ACCESS TEACHER SMALL GROUP WORKFLOW
* Click on **Add New Group** - *Expect the screen to switch to Add Group Screen*
* Click on an existing Group (on the left column) - *Expect a checkmark to enter checkbox for selected Group and Student members of Group to be checked in the left column*
* Click on the **Edit** button - *Expect a pop-up with text box*
* Click on the text box - *Expect the cursor to fill the box and erase current name.*
* Add new text for the Group Name - *Expect new text to fill text box*
* Click the **OK** button - *Expect the group name to be changed in the left column*

### Adding Group Notes Workflow

1. Follow the LOGIN WORKFLOW
* Follow ACCESS TEACHER SMALL GROUP WORKFLOW
* Click on the **Notes** button on a Group record - *Expect screen to switch to the Group Add Notes screen*
* Click the **Add Notes** button - *Expect a new note to appear with the Date field already filled*
* Click into **Observation/Instruction** space - *Expect cursor to move into and blink on Observation/Instruction space*
* Type in test data
* Click into **Next Steps** space - *Expect cursor to move into and blink on Next Steps space*
* Type in test data
* Click the **Exit** button - *Expect the screen to switch back to the Teacher Small Group Conference Screen*
* Click on the **Notes** button on a Group record, again - *Expect the screen to switch to the Group Note Screen and the previous note(s) should be visible*

### Start Session (without Student) Workflow

1. Follow the LOGIN WORKFLOW
* Follow ACCESS TEACHER SMALL GROUP WORKFLOW
* Click on **Start Session** button - *Expect warning to appear with "Student is not selected" in the message*
* Click the **OK** option to exit - *Expect warning to disappear and Teacher Conference Screen to reappear*

### Whiteboard Workflow

1. *Expect to be working within an activity* 
* Click on the **Whiteboard** button - *Expect the Whiteboard Screen to appear*
* Click anywhere on the Whiteboard Window - *Expect the flashing cursor to appear at the point of click*
* Enter in text - *Expect the text to appear on the Whiteboard Window*
* Click elsewhere on the Whiteboard - *Expect the flashing cursor to appear at the point of click*
* Enter in text - *Expect the text to appear on the Whiteboard Window*
* Click on the **Hide Keyboard** button (lower right corner of screen) - *Expect window to shrink*
* Click the **Exit Button** - *Expect the screen to switch back to the pre-whiteboard Screen*

### User Timers Workflow

* Click on first **00:00** time - *Expect the screen to focus on a timer*
* Click on the **00** for hours - *Expect a cursor to enter the field*
* Click on a number to set minutes - *Expect the chosen number to be inserted into the field*
* Click on the **00** for seconds - *Expect a cursor to enter the field*
* Click on a number to set seconds - *Expect the chosen number to be inserted into the field*
* Click the **OK** button to save - *Expect screen to switch back to the activity screen*
* Click the **Start** button to start the timer - *Expect the Timer to count down*
* Click the **Stop** button to end the timer - *Expect the Timer to stop*
* Repeat the above steps with the with second timer
* *Expect the STOP button to back into START when the timer expires*

### Letter Names Activity (without Student) Workflow

1. Follow the LOGIN WORKFLOW
* Follow ACCESS TEACHER SMALL GROUP WORKFLOW
* Follow START SESSION (WITHOUT STUDENT) WORKFLOW
* Click the **Manual** button option - *Expect the Choose a Skill option to appear*
* Click on **Letter Names** button - *Expect the screen to switch to the Letter Names Screen*
* Click on **Flash Card** button - *Expect the Flash Card activity to appear*
* Click on a random character - *Expect the chosen letter to appear in the Middle Window*
* Repeat tests for all characters
* Click the **Exit** button - *Expect the What Next? menu to appear*
* Click the **Cover Up** button - *Expect the Cover Up activity to appear*
* Choose six characters and click on them - *Expect, in order, for each chosen letter to appear within a circle*
* Click on the **Cover** button - *Expect nothing to change*
* Click on a random circle - *Expect the size of the circle and letter to increase*
* Repeat for all circles
* Click on the **Clear** button - *Expect the circles to be cleared*
* Follow the WHITEBOARD WORKFLOW
* Follow the USER TIMERS WORKFLOW

### Letter Sounds Activity (without Student) Workflow

1. Follow the LOGIN WORKFLOW
* Follow ACCESS TEACHER SMALL GROUP WORKFLOW
* Follow START SESSION (WITHOUT STUDENT) WORKFLOW
* Click the **Manual** button option - *Expect the Choose a Skill option to appear*
* Click on **Letter Sounds** button - *Expect the screen to switch to the Letter Sounds Screen*
* Click on **Flash Card** button - *Expect the Flash Card activity to appear*
* Click on a random character - *Expect the chosen letter to appear in the Middle Window*
* Repeat tests for all characters
* Click the **Exit** button - *Expect the What Next? menu to appear*
* Click the **Cover Up** button - *Expect the Cover Up activity to appear*
* Choose six characters and click on them - *Expect, in order, for each chosen letter to appear within a circle*
* Click on the **Cover** button - *Expect nothing to change*
* Click on a random circle - *Expect the size of the circle and letter to increase*
* Repeat for all circles
* Click on the **Clear** button - *Expect the circles to be cleared*
* Follow the WHITEBOARD WORKFLOW
* Follow the USER TIMERS WORKFLOW

### Onset/Rime Activity (without Student) Workflow

1. Follow the LOGIN WORKFLOW
* Follow ACCESS TEACHER SMALL GROUP WORKFLOW
* Follow START SESSION (WITHOUT STUDENT) WORKFLOW
* Click the **Manual** button option - *Expect the Choose a Skill option to appear*
* Click on **Onset/Rime** button - *Expect the screen to switch to the Letter Sounds Screen*
* Click on **Flash Card** button - *Expect the Flash Card activity to appear*
* Click on a random onset - *Expect the related words to appear in the Top Window*
* Click on a random word - *Expect chosen word to appear in the Middle Window*
* Repeat tests for all onsets
* Click on a random rime - *Expect the related words to appear in the Top Window*
* Click on a random word - *Expect chosen word to appear in the Middle Window*
* Click on the **II**, **III**, and **IV** levels - *Expect a new set of onsets and rimes to appear*
* Repeat tests for all rimes
* Click the **Exit** button - *Expect the What Next? menu to appear*
* Click the **Cover Up** button - *Expect the Cover Up activity to appear with six scrolls*
* Choose six onsets and words - *Expect, in order, for each chosen word to appear within a scroll*
* Click on the **Cover** button - *Expect nothing to change*
* Click on a random scroll - *Expect the chosen scroll letters to become red*
* Repeat for all scrolls
* Click on the **Clear** button - *Expect the scrolls to be cleared*
* Follow the WHITEBOARD WORKFLOW
* Follow the USER TIMERS WORKFLOW

### Sight Words Activity (without Student) Workflow

1. Follow the LOGIN WORKFLOW
* Follow ACCESS TEACHER SMALL GROUP WORKFLOW
* Follow START SESSION (WITHOUT STUDENT) WORKFLOW
* Click the **Manual** button option - *Expect the Choose a Skill option to appear*
* Click on **Sight Words** button - *Expect the screen to switch to the Sight Words Screen*
* Click on **Flash Card** button - *Expect the Flash Card activity to appear*
* Click on a random word - *Expect the chosen word to appear in the Middle Window*
* Repeat tests for all words
* Click on the **II** through **VI** tabs - *Expect a new set of words to appear for each*
* Repeat tests for all words
* Click the **Exit** button - *Expect the What Next? menu to appear*
* Click the **Cover Up** button - *Expect the Cover Up activity to appear*
* Choose six words and click on them - *Expect, in order, for each chosen letter to appear within a cloud*
* Click on the **Cover** button - *Expect nothing to change*
* Click on a random cloud - *Expect the size of the cloud and letter to increase*
* Repeat for all circles
* Click on the **Clear** button - *Expect the clouds to be cleared*
* Follow the WHITEBOARD WORKFLOW
* Follow the USER TIMERS WORKFLOW

### Story Activity (without Student) Workflow

1. Click on the **Story** button - *Expect Middle Window to reveal Level Menu*
* Select a Reading Level - *Expect the screen to switch to Story Menu Screen*
* Select a Book - *Expect the screen to switch to Story Screen*
* Click on the **Common Core Standards** tab
* Click on an **Assessment** once - *Expect nothing to happen*
* Click on an **Assessment** twice - *Expect nothing to happen*
* Click on an **Assessment** thrice - *Expect nothing to happen*
* Click on an **Assessment** fourth - *Expect nothing to happen*
* Swipe the story page left - *Expect the page to move left*
* Swipe the story page right - *Expect the page to move right*
* Scroll the text up and down - *If extra lines are hidden, expect the scrolling to reveal all lines*
* Follow the WHITEBOARD WORKFLOW
* Follow the USER TIMERS WORKFLOW