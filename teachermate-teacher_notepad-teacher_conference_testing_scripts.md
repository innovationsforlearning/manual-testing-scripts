# Teacher Notepad - Teacher Conference

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

### Teacher Conference Workflow

1. Follow the LOGIN WORKFLOW
* Click on **Teacher Conference** option - *Expect to see a chart of students (Apps One, Apps OneE, etc)*
* Sort col by **Student Name** - *Expect the columns to sort by Student Name (first name)*
* Sort col by **Rdg Stage** - *Expect the columns to sort by Rdg Stage*
* Sort col by **Desired Conf's Per Wk** - *Expect the columns to sort by Desired Conf's Per Wk*
* Sort col by **Conf: Order** - *Expect the columns to sort by Desired Conf: Order*
* Sort col by **Days Since Last Conference** - *Expect the columns to sort by Days Since Last Conference*
* Re-sort Conf. Order by click-and-hold on Student, drag row to new slot - *Expect new order to change*

### Reset Conference Order Workflow

1. Follow the LOGIN WORKFLOW
* Click on **Teacher Conference** option - *Expect to see a chart of students (Apps One, Apps OneE, etc)*
* Click on a **Student** record - *Expect the record color to change to Dark Grey*
* Re-sort Conf. Order by click-and-hold on Student, drag row to new slot - *Expect new order to change*

### Adding Student Notes Workflow

1. Follow the LOGIN WORKFLOW
* Click on **Teacher Conference** option - *Expect to see a chart of students (Apps One, Apps OneE, etc)*
* Click on a **Student** record - *Expect the record color to change to Dark Grey*
* Click the **View/Add Notes** button - *Expect the screen to switch to the Student Note Screen*
* Click the **Add Notes** button - *Expect a new note to appear with the Date field already filled*
* Click into **Observation/Instruction** space - *Expect cursor to move into and blink on Observation/Instruction space*
* Type in test data
* Click into **Next Steps** space - *Expect cursor to move into and blink on Next Steps space*
* Type in test data
* Click the **Exit** button - *Expect the screen to switch back to the Teacher Conference Screen*
* Click **View/Add Notes** button, again - *Expect the screen to switch to the Student Note Screen and the previous note(s) should be visible*

### Start Session without Student Workflow

1. Follow the LOGIN WORKFLOW
* Click on **Teacher Conference** option - *Expect to see a chart of students (Apps One, Apps OneE, etc)*
* Make sure no **Student** record is selected
* Click on **Start Session** button - *Expect warning to appear with "Student is not selected" in the message*
* Click the **OK** option to exit - *Expect warning to disappear and Teacher Conference Screen to reappear*

### Start Session with Student Workflow

1. Follow the LOGIN WORKFLOW
* Click on **Teacher Conference** option - *Expect to see a chart of students (Apps One, Apps OneE, etc)*
* Click on **Start Session** button - *Expect screen to switch to Choose a Skill Screen*

### Letter Names Activity Workflow

1. Follow the LOGIN WORKFLOW
* Follow the START SESSION WITH STUDENT WORKFLOW
* Click on **Letter Names** button - *Expect the screen to switch to the Letter Names Screen*

#### Indicate Yes Subflow

1. Click on a random letter - *Expect letter to appear in Word Window*
* Click on **No** - *Expect letter to be highlighted red*

#### Indicate No Subflow

1. Click on a different random letter - *Expect letter to appear in Word Window*
* Click on **Yes** - *Expect letter to be highlighted green*

#### Change Yes to No Subflow

1. Click on first letter from INDICATE YES SUBFLOW - *Expect letter to appear in Word Window*
* Click on **Yes** - *Expect red highlight to change to green highlight*

#### Change No to Yes Subflow

1. Click on Second letter from INDICATE NO SUBFLOW - *Expect letter to appear in Word Window*
* Click on **No** - *Expect green highlight to change to red highlight*

#### Manual change of Yes, No, Clear Subflow

1. Click on random letter and hold - *Expect a three-colored pop-up to appear*
* Choose Green, Red, or Clear - *Expect color to change to chosen color*
* Repeat steps for all colors - *Expect color to change to chosen color*

### Letter Sounds Activity Workflow

1. Follow the LOGIN WORKFLOW
* Follow the START SESSION WITH STUDENT WORKFLOW
* Click on **Letter Sounds** button - *Expect the screen to switch to the Letter Sounds Screen*

#### Indicate Yes Subflow

1. Click on a random letter - *Expect letter to appear in Word Window*
* Click on **No** - *Expect letter to be highlighted red*

#### Indicate No Subflow

1. Click on a different random letter - *Expect letter to appear in Word Window*
* Click on **Yes** - *Expect letter to be highlighted green*

#### Change Yes to No Subflow

1. Click on first letter from INDICATE YES SUBFLOW - *Expect letter to appear in Word Window*
* Click on **Yes** - *Expect red highlight to change to green highlight*

#### Change No to Yes Subflow

1. Click on Second letter from INDICATE NO SUBFLOW - *Expect letter to appear in Word Window*
* Click on **No** - *Expect green highlight to change to red highlight*

#### Manual change of Yes, No, Clear Subflow

1. Click on random letter and hold - *Expect a three-colored pop-up to appear*
* Choose Green, Red, or Clear - *Expect color to change to chosen color*
* Repeat steps for all colors - *Expect color to change to chosen color*

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

### Change Student Assignment Levels Workflow

* Click on **Assignment** button - *Expect displays to show list of options: Reading Stage, Reading Level, Onset/Rime Set, Sight Word Set)*
* Click on **Reading Stage** and change - *Expect Assignment Description on bottom of app to change to chosen values*
* Click on **Reading Level** and change - *Expect Assignment Description on bottom of app to change to chosen values*
* Click on **Onset/Rime Set** and change - *Expect Assignment Description on bottom of app to change to chosen values*
* Click on **Sight Word** and change - *Expect Assignment Description on bottom of app to change to chosen values*
* Click on **information icon** (i) in top right corner of Assignment Window - *Expect information pop-up to appear* 
* Click on the Sync button *Expect notification to appear regarding sync process*
* !!!Check on OMS data!!!

### Add Note from Activity Screen Workflow

* Click on **Note** button - *Expect Activities Screen to switch to Notes screen*
* Click the **Add Notes** button - *Expect the screen to switch to the Student Note Screen*
* Click the **Add Notes** button - *Expect a new note to appear with the Date field already filled*
* Click into **Observation/Instruction** space - *Expect cursor to move into and blink on Observation/Instruction space*
* Type in test data
* Click into **Next Steps** space - *Expect cursor to move into and blink on Next Steps space*
* Type in test data
* Click the **Exit** button - *Expect the screen to switch back to the Teacher Conference Screen*
* Click **Note** button, again - *Expect the screen to switch to the Student Note Screen and the previous note(s) should be visible*

### Onset/Rime Activity Workflow

1. Click on **Onset/Rime** button - *Expect Onset/Rime screen to appear*

#### Select an Onset Subflow

1. Select a random Rime - *Expect selected Rime to appear in the Middle Window and onset/rime words to appear in the Top Window*
* Select an Onset/Rime Word in the Top Window - *Expect the selected word to appear in the Middle Window*
* Click the **Yes** button - *Expect the selected Rime to be highlighted green*

#### Select an Onset

* Select a random Onset - *Expect selected Onset to appear in the Middle Window and onset/rime words to appear in the Top Window*
* Select an Onset/Rime Word in the Top Window - *Expect the selected word to appear in the Middle Window*
* Click the **Yes** button - *Expect the selected Onset to be highlighted green*

#### Change a Rime Assessment

1. Select a random Rime - *Expect selected Rime to appear in the Middle Window and onset/rime words to appear in the Top Window*
* Select an Onset/Rime Word in the Top Window - *Expect the selected word to appear in the Middle Window*
* Click the **No** button - *Expect the selected Rime to be highlighted red*

#### Change an Onset Assessment

1. Select a random Onset - *Expect selected Onset to appear in the Middle Window and onset/rime words to appear in the Top Window*
* Select an Onset/Rime Word in the Top Window - *Expect the selected word to appear in the Middle Window*
* Click the **No** button - *Expect the selected Onset to be highlighted green*

#### Manually change a Rime Assessment

1. Select a green Rime and hold - *Expect a Green/Red/White option to appear*
* Select the **Red** option - *Expect the Rime to change highlight to red*
* Select a red Rime and hold - *Expect a Green/Red/White option to appear*
* Select the **Green** option - *Expect the Rime to change highlight to green*
* Select a red Rime and hold - *Expect a Green/Red/White option to appear*
* Select the **White** option - *Expect the Rime to change highlight to cleared*
* Repeat this Subflow for All or Multiple Rimes

#### Manually change an Onset Assessment

1. Select a green Onset and hold - *Expect a Green/Red/White option to appear*
* Select the **Red** option - *Expect the Rime to change highlight to red*
* Select a red Onset and hold - *Expect a Green/Red/White option to appear*
* Select the **Green** option - *Expect the Rime to change highlight to green*
* Select a red Onset and hold - *Expect a Green/Red/White option to appear*
* Select the **White** option - *Expect the Rime to change highlight to cleared*
* Repeat this Subflow for All or Multiple Onsets

#### Change the Onset/Rime levels

* Select the **II** tab on the right - *Expect the Level II Onset/Rimes to appear*
* Repeat the CHANGE A RIME ASSESSMENT WORKFLOW
* Repeat the CHANGE AN ONSET ASSESSMENT WORKFLOW
* Repeat the MANUALLY CHANGE A RIME ASSESSMENT
* Repeat the MANUALLY CHANGE AN ONSET ASSESSMENT
* Select the **III** tab and repeat the above set of instructions
* Select the **IV** tab and repeat the above set of instructions

### Sight Words Activity Workflow

1. Click on **Sight Words** button - *Expect Sight Words screen to appear*

#### Select a Word and Assess Yes Subflow

1. Select a random word - *Expect selected Word to appear in the Middle Window*
* Click the **Yes** button - *Expect the selected Word to be highlighted green*

#### Select a Word and Assess No Subflow

1. Select a random word - *Expect selected Word to appear in the Middle Window*
* Click the **No** button - *Expect the selected Word to be highlighted red*

#### Manually change a Word Assessment

1. Select a green Word and hold - *Expect a Green/Red/White option to appear*
* Select the **Red** option - *Expect the Word to change highlight to red*
* Select a red Word and hold - *Expect a Green/Red/White option to appear*
* Select the **Green** option - *Expect the Word to change highlight to green*
* Select a red Word and hold - *Expect a Green/Red/White option to appear*
* Select the **White** option - *Expect the Word to change highlight to cleared*
* Repeat this Subflow for All or Multiple Words

#### Change the Onset/Rime levels

* Select the **II** tab on the left - *Expect the II level words to appear*
* Repeat the SELECT A WORD AND ASSESS YES WORKFLOW
* Repeat the SELECT A WORD AND ASSESS NO WORKFLOW
* Repeat the MANUALLY CHANGE A WORD ASSESSMENT
* Select the **III** on the left tab and repeat the above set of instructions
* Select the **IV** tab and repeat the above set of instructions
* Select the **V** tab and repeat the above set of instructions
* Select the **VI** tab and repeat the above set of instructions

### Story Activity Workflow

1. Click on the **Story** button - *Expect Middle Window to reveal Level Menu*
* Select a Reading Level - *Expect the screen to switch to Story Menu Screen*
* Select a Book - *Expect the screen to switch to Story Screen*
* Click on the **Common Core Standards** tab
* Click on an **Assessment** once - *Expect the assessment to turn red*
* Click on an **Assessment** twice - *Expect the assessment to turn yellow*
* Click on an **Assessment** thrice - *Expect the assessment to turn green*
* Click on an **Assessment** fourth - *Expect the assessment to be cleared*
* Swipe the story page left - *Expect the page to move left*
* Swipe the story page right - *Expect the page to move right*
* Scroll the text up and down - *If extra lines are hidden, expect the scrolling to reveal all lines*

### Whiteboard Workflow
1. Click on the **Whiteboard** button - *Expect the Whiteboard Screen to appear*
* Click anywhere on the Whiteboard Window - *Expect the flashing cursor to appear at the point of click*
* Enter in text - *Expect the text to appear on the Whiteboard Window*
* Click elsewhere on the Whiteboard - *Expect the flashing cursor to appear at the point of click*
* Enter in text - *Expect the text to appear on the Whiteboard Window*
* Click on the **Hide Keyboard** button (lower right corner of screen) - *Expect window to shrink*
* Click the **Exit Button** - *Expect the screen to switch back to the pre-whiteboard Screen*