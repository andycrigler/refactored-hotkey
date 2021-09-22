# refactored-hotkey
Autohotkey edits for Guayaquil

## notation

| Symbol | Keystroke |
|-------|:-------------|
| #  | The Windows key on the keyboard
| ^  | The Ctrl key
| !  | The Alt key
| +  | The Shift key

## Organization Notes

- You can highlight and Ctrl-f and search by AHK command to easily navigate this giant script -----------
- Organization notes and Guayaquil-specific observations by Andy Crigler 20210921  ----------------------
___________________________________________________________________________________________________________________


|  AHK command | Keystroke Combo              | Description                                                       |
|-------------|-------------------|-------------------------------------------------------------------------------|
| Insert 	 |	Insert			| Readys IVO to scan the next case
| ^#k         |	Ctrl+Windows+k		| CLOK Deletions - first 7 steps
| HOME  	 |	Home			| Navigate to notes, readies "insert" button--can be pressed by hitting space bar
| ScrollLock|	ScrollLock		| Opens the Visa Info tab in the Case/App window
| ^p		 |	Ctrl+p			| Opens the Print-Func Sreen
| ^q          |    	Ctrl+q			| Age Calculator - Difference between two dates
|   ^+q	 |	Ctrl+Shift+q		| Age Calculator - Displays applicant's age through today's date

	
### INTERVIEW FACILITATOR

| AHK command | Keystroke Combo              | Description                                                                   |
|-------------|------------------------------|-------------------------------------------------------------------------------|
| ^+c	 |	Ctrl+Shift+c		| takes notes from IV note taker and pastes them in IVO [GYQ probably won't use]
| [F12]	 |      F12			| Closes notetaker and pastes into IVO
| [F1]        |      F1			| Creates a new notetaker page (GYQ probably won't use)	 
| !e		 |	Alt+e			| DS-260 Opener
| ^k		 |	Ctrl+k			| Renamecheck ALL applicants
| ^g 	 |	Ctrl+g			| facilitator - makes it easier and faster to add and copy 221g hits.
| +s		 |	Shift+s			| Change "Interview Status" to SCHEDULED and save
| ^s		 |	Ctrl+s			| Save
| !q		 |	Alt+q			| Electronic Docs / EDP Opener

#### NEXT APPLICANT


| AHK command | Keystroke Combo              | Description                                                                   |
|-------------|------------------------------|-------------------------------------------------------------------------------|
| ^+r	 | 	Ctrl+Shift+r		| Next CROSS REFERENCED CASE
| ^Right	 | 	Ctrl+Right		| Goes to the next APPLICANT in the case
| ^Left	 | 	Ctrl+Left		| Goes to the previous APPLICANT in the case


 ### UPGRADES BY VERSION

| AHK command | Key Combo      | Works?    | Description                            | Issue                                    |
|-------------|----------------|-----------|----------------------------------------|------------------------------------------|
| ^`	       | Ctrl+`		| Broken    | Opens a letter generator. 	     | GYQ probably won't use
| ^+`	       | Ctrl+Shift+`	| Broken    | Opens a letter generator.              | GYQ probably won't use 
| ^#i	       | Ctrl+Windows+i	| Broken    | Supposed to perform an Ink action.     | doesn't shift focus to Ink
| ^#n	       | Ctrl+Windows+n	| Broken    | NIV lookup 			     | doesn't shift focus to NIV
| ^u	       | Ctrl+u		| Broken    | Unlocks case 			     | fails after 1 January 2021
| ^Insert     | Ctrl+Insert	| Broken    | Opens up adoptions tracking tool       | excel file is post(GZU)-specific
| ^b          | Ctrl+b         | Broken    | Searches for greencard status          | GreenCard table is a post-specific file
| [F5]        | F5             | Broken    | Opens a CCD NIV or PCQS search         | Need to troubleshoot
| !u          | Alt+u          | TBD       | Pastes common CAT-1 comments   

