# TeacherMate - Teacher Notepad - Partner Station Scoring

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

### Partner Station Scoring Sorting Workflow
1. Follow LOGIN WORKFLOW
* Tap *Partner Station Scoring* - *Expect App Menu Screen to switch to Partner Station Scoring Screen*
* Expect to see:
	- *Exit button*
	- *Table including columns: Student Name; Partner Station Score*
	- *Student Names: Jill Green-I, Mary Brown-II, Joe Gray-III*
	- *Student Scores: (actual scores)*
* Tap *Student Name header* - *Expect to see table sorted alphabetically by student name ascending*
* Tap *Student Name header* - *Expect to see table sorted alphabetically by student name descending*
* Tap *Partner Station Score header* - *Expect to see table sorted numerically by score ascending*

### Partner Station Scoring Edit Workflow
1. Follow LOGIN WORKFLOW
* Tap *Partner Station Scoring* - *Expect App Menu Screen to switch to Partner Station Scoring Screen*
* Tap *any Score* - *Expect to see Score in a text field, Ok button, Cancel button*
* Tap *text field* - *Expect to see keyboard*
* Type *a number*  - *Expect to see the number in the text field*

### Partner Station Scoring Cancel Edit Workflow
1. Follow PARTNER STATION SCORING EDIT WORKFLOW
* Tap *Cancel button* - *Expect to see Partner Station Scoring screen with score unchanged*

### Partner Station Scoring Accept Edit Workflow
1. Follow PARTNER STATION SCORING EDIT WORKFLOW
* Tap *Ok button* - *Expect to see Partner Station Scoring screen with score updated*

### Partner Station Scoring Exit Workflow
1. Follow LOGIN WORKFLOW
* Tap *Partner Station Scoring* - *Expect App Menu Screen to switch to Partner Station Scoring Screen*
* Tap *Exit button* - *Expect Partner Station Scoring Screen to switch to App Menu Screen*

### Partner Station Scoring Syncing Workflow
1. Follow PARTNER STATION SCORING ACCEPT EDIT WORKFLOW
* Follow PARTNER STATION SCORING EXIT WORKFLOW
* 