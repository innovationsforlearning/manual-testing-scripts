# Partner Station

## Login and Game Tests

### Initial Login Workflow

1. Open App - *Expect Splash Screen to load*
* App Loads - *Expect app to be viewed only in landscape mode*
* Expect Splash Page Screen to switch to Login Screen*
* Enter Username into **teacher username** input field: johnteacher
* Enter Password into **teacher password**: 1234
* Click *login* button - *Expect Alert indicating successful login and teacher login form to be hidden*

### Wake App Workflow
1. Follow INITIAL LOGIN WORKFLOW
* Tap iPad *Home button* - *Expect to see iPad Home Screen*
* Open App - *Expect to see Login Screen with teacher login form hidden*

### Open App after Successful Login Workflow
1. Follow INITIAL LOGIN WORKFLOW
* Double tap *iPad Home button* - *Expect to see the iOS 7 Multi-tasking view*
* Swipe up on the PartnerStation screenshot - *Expect to see PartnerStation icon removed from the multi-tasking view*
* Tap *iPad Home button* - *Expect to see iPad Home Screen*
* Open PartnerStation - *Expect to see Login Screen with teacher login form populated with username: johnteacher, password: ****
* Click *login* button - *Expect Alert indicating successful login and teacher login form to be hidden*

### Stage I Card Reader Login Workflow

1. Follow the LOGIN WORKFLOW
* Click on **Card Listener** option - *Expect to see a drop down menu of student names (Jill Green-I, Mary Brown-II, etc)*
* Click on *Mary Brown-II* - *Expect to see the student name displayed*
* Click on **Card Reader** option - *Expect to see a drop down menu of student names (Jill Green-I, Mary Brown-II, etc)*
* Click on *Jill Green-I* - *Expect to see the student name displayed*
* Click on *Go button* - *Expect to see the login screen switch to the game screen*
 	- Help button
 	- Jill Green-I - Highlighted - labelled Card Reader
  	- Mary Brown-II - labelled Card Listener
  	- Stimulus
  	- Score
  	- Yes button
  	- No button
  	- Scoring button


### Stage I Card Reader Game Workflow
1. Follow the STAGE I CARD READER LOGIN WORKFLOW
* Expect the stimulus to be any letter upper or lower case
* Click on the *Help button* - expect to hear the NAME of the stimulus
* Click on the *Yes button* - expect to see the Score incremented and see the stimulus replaced.
* Click on the *No button* - expect to hear the NAME of the stimulus and see the stimulus replaced.

### One Card Reader Incorrect Answer Game Workflow
1. Repeat STAGE I CARD READER GAME WORKFLOW Until all stimuli have been presented
* *Expect stimuli followed by clicking No button to be re-presented after initial presentation of all stimuli*

### One Card Reader Stimuli Exhausted Game Workflow
1. Repeat STAGE I CARD READER GAME WORKFLOW
* *Expect all stimuli to be represented in new order after initial presentation of all stimuli*



### Stage II Card Reader Login Workflow

1. Follow the LOGIN WORKFLOW
* Click on **Card Listener** option - *Expect to see a drop down menu of student names (Jill Green-I, Mary Brown-II, etc)*
* Click on *Jill Green-I** - *Expect to see the student name displayed*
* Click on **Card Reader** option - *Expect to see a drop down menu of student names (Jill Green-I, Mary Brown-II, etc)*
* Click on *Mary Brown-II* - *Expect to see the student name displayed*
* Click on *Go button* - *Expect to see the login screen switch to the game screen*
 	- Help button
 	- Mary Brown-II - Highlighted, labelled Card Reader
  	- Jill Green-I - labeled Card Listener
  	- Stimulus
  	- Score
  	- Yes button
  	- No button
  	- Scoring button

### Stage II Card Reader Game Workflow
1. Follow the STAGE II CARD READER LOGIN WORKFLOW
	- Expect the stimulus to be either the first letter or entire word from this list:
	- at, bat, cat, dad, egg, fat, get, hat, in, jet, kid, let, met, net, on, pet, rat, sat, tap, up, vat, wet, yet, zap 
* Click on the *Help button* - expect to hear the SOUND of the stimulus 
* Click on the *Yes button* - expect to see the Score incremented and see the stimulus replaced.
* Click on the *No button* - expect to hear the NAME of the stimulus and see the stimulus replaced.

### Stage III Card Reader Login Workflow

1. Follow the LOGIN WORKFLOW
* Click on **Card Listener** option - *Expect to see a drop down menu of student names (Jill Green-I, Mary Brown-II, etc)*
* Click on Jill Green-I - *Expect to see the student name displayed*
* Click on **Card Reader** option - *Expect to see a drop down menu of student names (Jill Green-I, Mary Brown-II, etc)*
* Click on Joe Gray-III - *Expect to see the student name displayed*
* Click on *Go button* - *Expect to see the login screen switch to the game screen*
 	- Help button
 	- Joe Gray-III - Highlighted, labelled Card Reader
  	- Jill Green-I labelled Card Listener
  	- Stimulus
  	- Score
  	- Yes button
  	- No button
  	- Scoring button

### Stage III Card Reader Game Workflow
1. Follow the STAGE III CARD READER LOGIN WORKFLOW
	- Expect the stimulus to be either a SIGHT WORD word from this list:
		- a, and, ball, be, blue, by, do, for, funny, green, has, he, house, is, like, little, me, no, play, said, school, see, she, the, they, to, toy, we, why
	- OR an ONSET/RIME word from this list:
		- bad, bat, bun, but, cap, cat, cut, did, dip, fin, fit, got, ham, hat, hid, him, hop, hot, hut, jam, kid, kit, lap, lid, lip, lot, mad, man, map, mom, mud, nap, nod, pop, pup, ran, rim, rod, run, sad, sip, sit, son, sun, tan, tin, ton, top, win, won, yam 
* Click on the *Help button* - expect to hear the SOUND of the stimulus 
* Click on the *Yes button* - expect to see the Score incremented and see the stimulus replaced.
* Click on the *No button* when a SIGHT WORD is displayed - expect to hear the SOUND of the word and see the word get larger and then see the stimulus replaced.
* Click on the *No button* when an ONSET/RIME WORD is displayed - expect to 
	- hear the sound of the word and see the word get larger and then smaller
	- see the word split into onset and rime
	- hear the sound of the onset and see it grow larger and then smaller
	- hear the sound of the rime and see it grow larger and then smaller
	- hear the sound of the word and see the word get larger 
	- see the stimulus change


### Two Card Reader Login Workflow

1. Follow the LOGIN WORKFLOW
* Click on **Card Listener** option - *Expect to see a drop down menu of student names (Jill Green-I, Mary Brown-II, etc)*
* Click on Joe Gray-III - *Expect to see the student name displayed*
* Click on first **Card Reader** option - *Expect to see a drop down menu of student names (Jill Green-I, Mary Brown-II, etc)*
* Click on Mary Brown-II - *Expect to see the student name displayed*
* Click on second **Card Reader** option - *Expect to see a drop down menu of student names (Jill Green-I, Mary Brown-II, etc)*
* Click on Jill Green-I - *Expect to see the student name displayed*
* * Click on *Go button* - *Expect to see the login screen switch to the game screen*
 	- Help button
 	- Jill Green-I - Highlighted labelled Card Reader
 	- Mary Brown-II - labelled Card Reader
  	- Joe Gray-III - labelled Card Listener
  	- Stimulus
  	- Score - 0
  	- Yes button
  	- No button
  	- Scoring button

### Two Card Reader Game Workflow
1. Follow the Two Card Reader Login Workflow
* Click on the *Help button* - expect to hear the NAME of the stimulus 
* Click on the *Yes button* - expect to see the see the stimulus replaced with Stage II stimulus and highlight removed from Jill Green-I and highlight added to Mary Brown II
and the score (0) displayed for Mary Brown-II
* Click on the *Yes button* - expect to see the stimulus replaced with Stage I stimulus and highlight removed from Mary Brown-II and highlight added to Jill Green-I
and the score (0) displayed for Jill Green-I
* Click on the *No button* - expect to hear the SOUND of the stimulus and see the see the stimulus replaced with Stage II stimulus and highlight removed from Jill Green-I and highlight added to Mary Brown II
and the score (1) displayed for Mary Brown-II
* Click on the *No button* - expect to hear the NAME of the stimulus and see the stimulus replaced with Stage I stimulus and highlight removed from Mary Brown-II and highlight added to Jill Green-I
and the score (1) displayed for Jill Green-I

### Two Card Reader Incorrect Answer Game Workflow
1. Repeat TWO CARD READER GAME WORKFLOW Until all stimuli have been presented
* *Expect stimuli presented to Mary Brown-II followed by clicking No button to be re-presented to Mary Brown-II after initial presentation of all Stage II stimuli*
* *Expect stimuli presented to Jill Green-I followed by clicking No button to be re-presented to Jill Green-I after initial presentation of all Stage I stimuli*

### Two Card Reader Stimuli Exhausted Game Workflow
1. Repeat TWO CARD READER GAME WORKFLOW
* *Expect all stimuli presented to Mary Brown-II to be represented to Mary Brown-II in new order after initial presentation of all stimuli*
* *Expect all stimuli presented to Jill Green-I to be represented to Jill Green-I in new order after initial presentation of all stimuli*

### One Card Reader Scoring Workflow
1. Repeat STAGE I CARD READER GAME WORKFLOW until *Yes button* has been tapped 10 times.
* Tap *Scoring* button - *Expect to see Game Screen switch to Review Screen*
	- *Card Reader menu* - Labelled Card Reader, displaying Jill Green-I
	- *Report button*
	- *Back to Start a Session button*