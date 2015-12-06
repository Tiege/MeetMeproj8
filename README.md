# Meet Me Scheduler - Project 8 - cs399se
Our final project built off of project6/7. The program allows a user to propose a meeting to participants via email using the availability from their google calendars. The recipients of the email can use the link in the email to respond with their availability and the app will generate time slots where all parties are free. The meeting proposer can then select a time to set a meeting or delete their original proposal.

#Test flow:
A good flow to test all aspects of the web application by yourself:
	- Set up two seperate google calendars on a google account with event blocks created as desired
	- Go to the app and enter a date range that includes dates with event scheduled
	- Select one of the calendars to use for the proposal
	- send en email to yourself 
	- open the email and follow the link to another page where you can select the participating calendar
	- send the selection and then manual go back to the index page
	- click 'Check Responses' and observe free time intervals displayed
	- delete proposal to end application process

#Notes:
 - For sending the email, if you use chrome you need to manage your mailto handlers, it should work on fire fox fine and IE seems to be stranger than chrome
 - If you trouble occurs during the email section, you can continue the testing process by simply going to http://ix.cs.uoregon.edu:5808/emailRouted
 - After the proposal is deleted a new session must be initialized to repeat the application
 - An interface was added for the proposer to select a meeting time but that's the extent of the interface
