# TeacherMate - Teacher Notepad - Student Small Group

## Tests

### Login Workflow

1. Open App - *Expect Splash Screen to load*
* App Loads - *Expect app to be viewed only in landscape mode*
* Click on **Tap to Login** at top of screen - *Expect Splash Page Screen to switch to Login Screen*
* Enter Username into **teacher username** input field: johnteacher
* Enter Password into **teacher password**: 1234
* Click *login* button - *Expect screen to switch to Student Selection Screen*
* Click on a Student username - *Expect the screen to read "Waiting for activity" if Teacher Small Group is not in an activity*

### Whiteboard Workflow

1. *Expect to be working within an activity* 
* Teacher App: Click on the **Whiteboard** button - *Expect the Whiteboard Screen to appear*
* Student App: *Expect the Whiteboard Screen to appear*
* Teacher App: Click anywhere on the Whiteboard Window - *Expect the flashing cursor to appear at the point of click*
* Student App: *Expect the flashing cursor to appear at the point of click*
* Teacher App: Enter in text - *Expect the text to appear on the Whiteboard Window*
* Student App: *Expect the text to appear on the Whiteboard Window*
* Teacher App: Click elsewhere on the Whiteboard - *Expect the flashing cursor to appear at the point of click*
* Student App: *Expect the flashing cursor to appear at the point of click*
* Teacher App: Enter in text - *Expect the text to appear on the Whiteboard Window*
* Student App: *Expect the text to appear on the Whiteboard Window*
* Teacher App: Click on the **Hide Keyboard** button (lower right corner of screen) - *Expect window to shrink*
* Teacher App: Click the **Exit Button** - *Expect the screen to switch back to the pre-whiteboard Screen*
* Student App: *Expect the screen to switch back to the pre-whiteboard Screen*

### Create Note Workflow

1. Click on **Note** button - *Expect Activities Screen to switch to Notes screen*
* Click the **Add Notes** button - *Expect the screen to switch to the Student Note Screen*
* Click the **Add Notes** button - *Expect a new note to appear with the Date field already filled*
* Click into **Observation/Instruction** space - *Expect cursor to move into and blink on Observation/Instruction space*
* Type in test data
* Click into **Next Steps** space - *Expect cursor to move into and blink on Next Steps space*
* Type in test data
* Click the **Exit** button - *Expect the screen to switch back to the Teacher Conference Screen*
* Click **Note** button, again - *Expect the screen to switch to the Student Note Screen and the previous note(s) should be visible*

### Change Student Assignment Levels Workflow

1. Click on **Assignment** button - *Expect displays to show list of options: Reading Stage, Reading Level, Onset/Rime Set, Sight Word Set)*
* Click on **Reading Stage** and change - *Expect Assignment Description on bottom of app to change to chosen values*
* Click on **Reading Level** and change - *Expect Assignment Description on bottom of app to change to chosen values*
* Click on **Onset/Rime Set** and change - *Expect Assignment Description on bottom of app to change to chosen values*
* Click on **Sight Word** and change - *Expect Assignment Description on bottom of app to change to chosen values*
* Click on **information icon** (i) in top right corner of Assignment Window - *Expect information pop-up to appear* 
* Click on the Sync button *Expect notification to appear regarding sync process*
* !!!Check on OMS data!!!

### User Timers Workflow

1. Click on first **00:00** time - *Expect the screen to focus on a timer*
* Click on the **00** for hours - *Expect a cursor to enter the field*
* Click on a number to set minutes - *Expect the chosen number to be inserted into the field*
* Click on the **00** for seconds - *Expect a cursor to enter the field*
* Click on a number to set seconds - *Expect the chosen number to be inserted into the field*
* Click the **OK** button to save - *Expect screen to switch back to the activity screen*
* Click the **Start** button to start the timer - *Expect the Timer to count down*
* Click the **Stop** button to end the timer - *Expect the Timer to stop*
* Repeat the above steps with the with second timer
* *Expect the STOP button to back into START when the timer expires*

### Change Assessment Workflow

1. Click on a letter/word on in the selection window and hold - *Expect the color selector to appear*
* Choose a different color - *Expect the color to change as selected*
* Repeat for all three colors

### Letter Names/Flashcard (Teacher and Student) Workflow

1. Teacher App: Launch Letter Names/Flashcard - *Expect student card to be shown in the Top Section*
* Student App: *Expect student screen to switch to "Letter name/Flashcard" screen*
* Teacher App: Select a Student Card - *Expect student card to turn orange color*
* Teacher App: Select a letter - *Expect the chosen letter to appear in Middle Window*
* Student App: *Expect the chosen letter to appear in the Middle Circle*
* Teacher App: Select the **Yes** button on the Student Card - *Expect the chosen letter to become green*
* Student App: *Expect the Starred Number on the screen to indicate the number of correct answers*
* Student App: *Expect the chosen letter to appear in the Middle Circle*
* Teacher App: Select the **No** button on the Student Card - *Expect the chosen letter to become red*
* Teacher App: Repeat for all letters
* Teacher App: Follow the CHANGE ASSESSMENT WORKFLOW

### Letter Names/Cover Up (Teacher and Student) Workflow

1. Teacher App: Launch Letter Names/Cover Up - *Expect student card to be shown in the Top Section*
* Teacher App: Select six letters - *Expect each chosen letter to fill a circle in the correct order*
* Student App: *Expect the circles to reveal the chosen letters on the same-colored circles*
* Teacher App: Click on the **Cover** button
* Student App: *Expect the letters to disappear from the circles*
* Teacher App: Click on a circled letter - *Expect the circle and letter to increase in size*
* Student App: Click on the corresponding circle - *Expect the letter to briefly appear and disappear*
* Student App: Click on the **same** circled letter, hold, and flick the circle towards the top of the screen - *Expect the circle to float up and letter to disappear again*
* Teacher App: *Expect the letter to appear in the student card and the same letter to turn green in the keyboard window*
* Teacher App: Click on a circled letter - *Expect the circle and letter to increase in size*
* Student App: Click on the corresponding circle - *Expect the letter to briefly appear and disappear*
* Student App: Click on the **wrong** circled letter, hold, and flick the circle towards the top of the screen - *Expect the circle to float up and letter to disappear again*
* Teacher App: *Expect the letter to appear in the student card and the same letter to turn red in the keyboard window*

#### Routine Testing Subflow

1. Teacher App: Follow the CHANGE ASSESSMENT WORKFLOW
* Teacher App: Follow the CHANGE ASSIGNMENT WORKFLOW
* Teacher App: Follow the CREATE NOTE WORKFLOW
* Teacher App: Follow the USE TIMERS WORKFLOW
* Teacher App: Follow the WHITEBOARD WORKFLOW

### Letter Sounds/Flashcard (Teacher and Student) Workflow

1. Teacher App: Launch Letter Sounds/Flashcard - *Expect student card to be shown in the Top Section*
* Student App: *Expect student screen to switch to "Letter Sounds/Flashcard" screen*
* Teacher App: Select a Student Card - *Expect student card to turn orange color*
* Teacher App: Select a letter - *Expect the chosen letter to appear in Middle Window*
* Student App: *Expect the chosen letter to appear in the Middle Stage image*
* Teacher App: Select the **Yes** button on the Student Card - *Expect the chosen letter to become green*
* Student App: *Expect the Starred Number on the screen to indicate the number of correct answers*
* Teacher App: Select a letter - *Expect the chosen letter to appear in Middle Window*
* Student App: *Expect the chosen letter to appear in the Middle Stage image*
* Teacher App: Select the **No** button on the Student Card - *Expect the chosen letter to become red*
* Teacher App: Repeat for all letters
* Teacher App: Follow the CHANGE ASSESSMENT WORKFLOW

### Letter Sounds/Cover Up (Teacher and Student) Workflow

1. Teacher App: Launch Letter Sounds/Cover Up - *Expect student card to be shown in the Top Section*
* Teacher App: Select six letters - *Expect each chosen letter to fill a circle in the correct order*
* Student App: *Expect the circles to reveal the chosen letters on the same-colored circles*
* Teacher App: Click on the **Cover** button
* Student App: *Expect the letters to disappear from the circles*
* Teacher App: Click on a circled letter - *Expect the circle and letter to increase in size*
* Student App: Click on the corresponding circle - *Expect the letter to briefly appear and disappear*
* Student App: Click on the **same** circled letter, hold, and flick the circle towards the top of the screen - *Expect the circle to float up and letter to disappear again*
* Teacher App: *Expect the letter to appear in the student card and the same letter to turn green in the keyboard window*
* Teacher App: Click on a circled letter - *Expect the circle and letter to increase in size*
* Student App: Click on the corresponding circle - *Expect the letter to briefly appear and disappear*
* Student App: Click on the **wrong** circled letter, hold, and flick the circle towards the top of the screen - *Expect the circle to float up and letter to disappear again*
* Teacher App: *Expect the letter to appear in the student card and the same letter to turn red in the keyboard window*

#### Routine Testing Subflow

1. Teacher App: Follow the CHANGE ASSESSMENT WORKFLOW
* Teacher App: Follow the CHANGE ASSIGNMENT WORKFLOW
* Teacher App: Follow the CREATE NOTE WORKFLOW
* Teacher App: Follow the USE TIMERS WORKFLOW
* Teacher App: Follow the WHITEBOARD WORKFLOW

### Onset-Rime/Flashcard (Teacher and Student) Workflow

1. Teacher App: Launch Onset-Rime/Flashcard - *Expect student card to be shown in the Top Section*
* Student App: *Expect student screen to switch to "Onset-Rime/Flashcard" screen*
* Teacher App: Select a Student Card - *Expect student card to turn orange color*

#### Onset Subflow

1. Teacher App: Select an onset - *Expect the chosen onset to appear in Middle Window and related words to appear in the Top Window*
* Teacher App: Select a word from the Top Window - *Expect the chosen word to appear in the Middle Window*
* Student App: *Expect the chosen word to appear in the Middle Top Hat image*
* Teacher App: Select the **Yes** button on the Student Card - *Expect the chosen onset to become green*
* Student App: *Expect the Starred Number on the screen to indicate the number of correct answers*
* Teacher App: Select an onset - *Expect the chosen onset to appear in Middle Window and related words to appear in the Top Window*
* Teacher App: Select a word from the Top Window - *Expect the chosen word to appear in the Middle Window*
* Student App: *Expect the chosen word to appear in the Middle Top Hat image*
* Teacher App: Select the **No** button on the Student Card - *Expect the chosen onset to become red*
* Repeat for all onsets

#### Rime Subflow

1. Teacher App: Select a rime - *Expect the chosen rime to appear in Middle Window and related words to appear in the Top Window*
* Teacher App: Select a word from the Top Window - *Expect the chosen word to appear in the Middle Window*
* Student App: *Expect the chosen word to appear in the Middle Top Hat image*
* Teacher App: Select the **Yes** button on the Student Card - *Expect the chosen onset to become green*
* Student App: *Expect the Starred Number on the screen to indicate the number of correct answers*
* Teacher App: Select an onset - *Expect the chosen time to appear in Middle Window and related words to appear in the Top Window*
* Teacher App: Select a word from the Top Window - *Expect the chosen word to appear in the Middle Window*
* Student App: *Expect the chosen word to appear in the Middle Top Hat image*
* Teacher App: Select the **No** button on the Student Card - *Expect the chosen onset to become red*
* Teacher App: Repeat for all rimes
* Teacher App: Select the **II**, **III**, and **IV** tabs on the right side of the Bottom Window
* Teacher App: Repeat for all onsets and rimes

#### Routine Testing Subflow

1. Teacher App: Follow the CHANGE ASSESSMENT WORKFLOW
* Teacher App: Follow the CHANGE ASSIGNMENT WORKFLOW
* Teacher App: Follow the CREATE NOTE WORKFLOW
* Teacher App: Follow the USE TIMERS WORKFLOW
* Teacher App: Follow the WHITEBOARD WORKFLOW

### Sight Words/Flashcard (Teacher and Student) Workflow

1. Teacher App: Launch Sight Words/Flashcard - *Expect student card to be shown in the Top Section*
* Student App: *Expect student screen to switch to "Sight Words/Flashcard" screen*
* Teacher App: Select a Student Card - *Expect student card to turn orange color*
* Teacher App: Select a word - *Expect the chosen word to appear in Middle Window*
* Student App: *Expect the chosen letter to appear in the Middle Sunrise image*
* Teacher App: Select the **Yes** button on the Student Card - *Expect the chosen letter to become green*
* Student App: *Expect the Starred Number on the screen to indicate the number of correct answers*
* Teacher App: Select a letter - *Expect the chosen letter to appear in Middle Window*
* Student App: *Expect the chosen letter to appear in the Middle Sunrise image*
* Teacher App: Select the **No** button on the Student Card - *Expect the chosen letter to become red*
* Teacher App: Repeat for all letters/words
* Teacher App: Select the **II, III, IV, V, and VI** tabs - *Expect a new set of words to appear in the Bottom Middle Window**
* Teacher App: Repeast for all letter/words
* Teacher App: Follow the CHANGE ASSESSMENT WORKFLOW

### Sight Words/Cover Up (Teacher and Student) Workflow

1. Teacher App: Launch Sight Words/Cover Up - *Expect student card to be shown in the Top Section*
* Teacher App: Select six letters - *Expect each chosen letter to fill a cloud in the correct order*
* Student App: *Expect the circles to reveal the chosen letters on the same-colored clouds*
* Teacher App: Click on the **Cover** button
* Student App: *Expect the letters to disappear from the clouds*
* Teacher App: Click on a clouded letter - *Expect the cloud and letter to increase in size*
* Student App: Click on the corresponding cloud - *Expect the letter to briefly appear and disappear*
* Student App: Click on the **same** clouded letter, hold, and flick the cloud towards the top of the screen - *Expect the cloud to float up and letter to disappear again*
* Teacher App: *Expect the letter to appear in the student card and the same letter to turn green in the keyboard window*
* Teacher App: Click on a clouded letter - *Expect the cloud and letter to increase in size*
* Student App: Click on the corresponding cloud - *Expect the letter to briefly appear and disappear*
* Student App: Click on the **wrong** clouded letter, hold, and flick the cloud towards the top of the screen - *Expect the cloud to float up and letter to disappear again*
* Teacher App: *Expect the letter to appear in the student card and the same letter to turn red in the keyboard window*

#### Routine Testing Subflow

1. Teacher App: Follow the CHANGE ASSESSMENT WORKFLOW
* Teacher App: Follow the CHANGE ASSIGNMENT WORKFLOW
* Teacher App: Follow the CREATE NOTE WORKFLOW
* Teacher App: Follow the USE TIMERS WORKFLOW
* Teacher App: Follow the WHITEBOARD WORKFLOW

### Story Activity Workflow

1. Teacher App: Click on the **Story** button - *Expect Middle Window to reveal Level Menu*
* Teacher App: Select a Reading Level - *Expect the screen to switch to Story Menu Screen*
* Teacher App: Select a Book - *Expect the screen to switch to Story Screen*
* Student App: *Expect the screen to switch to Story Screen*

#### Student Assessment Subflow

1. Teacher App: Select a Student ID at the top - *Expect the student card to turn orange*
* Teacher App: Click on the **Common Core Standards** tab
* Teacher App: Click on an **Assessment** once - *Expect assessment to turn red*
* Teacher App: Click on an **Assessment** twice - *Expect assessment to turn yellow*
* Teacher App: Click on an **Assessment** thrice - *Expect assessment to turn green*
* Teacher App: Click on an **Assessment** fourth - *Expect assessment to be cleared*
* Teacher App: Repeat for the **Comprehension Strategies** 

#### Story Paging Subflow

1. Teacher App: Swipe the story page left - *Expect the page to move left*
* Student App: *Expect the page to move left*
* Teacher App: Swipe the story page right - *Expect the page to move right*
* Student App: *Expect the page to move right* 
* Teacher App: Scroll the text up and down - *If extra lines are hidden, expect the scrolling to reveal all lines*
* Student App: *Expect the text to scroll as appropriate*
* Teacher App: Click on a word - *Expect the word to be highlighted blue*
* Student App: *Expect the same word to be highlighted blue*
* Student App: Click on a word - *Expect the word to be highlighted blue*
* Teacher App: *Expect the same word to be highlighted blue*

#### Student Messaging Subflow

1. Teacher App: Click into the messaging window - *Expect the keyboard to pop up and the cursor to enter the message field*
* Teacher App: Type into the message field - *Expect selected text to appear in the field*
* Teacher App: Click the **Send** button - *Expect the keyboard to be hidden*
* Student App: *Expect the Student Message Field to render the message*

#### Student Messaging Subflow

1. Student App: Click into the messaging window - *Expect the keyboard to pop up and the cursor to enter the message field*
* Student App: Type into the message field - *Expect selected text to appear in the field*
* Student App: Click the **Send** button - *Expect the keyboard to be hidden*
* Teacher App: *Expect the Teacher Message Field to render the message*

#### Routine Testing Subflow

1. Teacher App: Follow the CHANGE ASSESSMENT WORKFLOW
* Teacher App: Follow the CHANGE ASSIGNMENT WORKFLOW
* Teacher App: Follow the CREATE NOTE WORKFLOW
* Teacher App: Follow the USE TIMERS WORKFLOW
* Teacher App: Follow the WHITEBOARD WORKFLOW

### Automatic Skill Orders Workflow

1. New Session
* Click the **Automatic** button - *Expect the Choose a Reading Stage menu to appear*

### Skill Progression Workflow Example

1. Click on the **1** button - *Expect the Letter Names activity to appear*
* Click on the **Flashcard** button - *Expect the Flashcard activity to appear*
* Click on the **Exit** button - *Expect the What Next? menu to appear*
* Click on the **Cover Up** button - *Expect the Cover Up activity to appear*
* Click on the **Exit** button - *Expect the What Next? menu to appear*

#### Story Reading Subflow

* Click on the **New Skill** button - *Expect the Story Menu to appear*
* Click on a story - *Expect a story to appear*
* Click on the **Exit** button - *Expect the What Next? menu to appear*

#### Sight Words Subflow

* Click on the **New Skill** button - *Expect the Sight Words activity to appear*
* Click on the **Flashcard** button - *Expect the Flashcard activity to appear*
* Click on the **Exit** button - *Expect the What Next? menu to appear*
* Click on the **Cover Up** button - *Expect the Cover Up activity to appear*
* Click on the **Exit** button - *Expect the What Next? menu to appear*

#### Letter Names Subflow

* Click on the **New Skill** button - *Expect the Letter Names activity to appear*
* Click on the **Flashcard** button - *Expect the Flashcard activity to appear*
* Click on the **Exit** button - *Expect the What Next? menu to appear*
* Click on the **Cover Up** button - *Expect the Cover Up activity to appear*
* Click on the **Exit** button - *Expect the What Next? menu to appear*

#### Story Reading Subflow

* Click on the **New Skill** button - *Expect the Story Menu to appear*
* Click on a story - *Expect a story to appear*
* Click on the **Exit** button - *Expect the What Next? menu to appear*

#### Letter Sounds Subflow

* Click on the **New Skill** button - *Expect the Letter Sounds activity to appear*
* Click on the **Exit** button - *Expect the What Next? menu to appear*

#### Session Ends Subflow

* Click on the **New Skill** button - *Expect the Reading Stage activity to appear*

### Automatic Sequences to Check - *Use the above SKILL PROGRESSION WORKFLOW EXAMPLE*

#### Reading Stage 1

* Letter Name
* Story Reading
* Sight Words
* Letter Name
* Story Reading 

#### Reading Stage 2 

* Letter Sound
* Story Reading 
* Sight Words 
* Letter Sound
* Letter Sound 

#### Reading Stage 3 

* Onset/Rime 
* Story Reading 
* Sight Words 
* Onset/Rime 
* Onset/Rime 

#### Reading Stage 4 

* Onset/Rime 
* Story Reading 
* Sight Words
* Onset/Rime 
* Story Reading 

#### Reading Stage 5 

* Onset/Rime 
* Story Reading 
* Sight Words 
* Onset/Rime 
* Story Reading 

#### Reading Stage 6 

* Onset/Rime
* Story Reading
* Sight Words 
* Onset/Rime 
* Story Reading 

#### Reading Stage 7 

* Onset/Rime 
* Sight Words 
* Onset/Rime
* Story Reading 

#### Reading Stage 8 

* Sight Words 
* Story Reading 
* Onset/Rime 
* Story Reading 

#### Reading Stage 9 

* Sight Words
* Story Reading 
* Onset/Rime
* Story Reading