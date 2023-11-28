## Build and Customize a Survey
Create a product feedback survey using Salesforce Surveys.

If you haven’t already enabled Surveys in your Trailhead Playground, do it now or else this challenge won’t pass.
Create a new survey:
Survey name: Solar Panel Feedback Survey
Disable the Welcome page
Enable Auto-Progress
Add a page that rates the installation process:
Page name: Solar Panel Installation (if you don't see the page name field, scroll up)
Question 1
Type: Rating
Question: Rate your experience with the solar panel installation.
Question 2
Type: Picklist
Question: Tell us what didn’t go well with the installation.
Choices
Late installation
Faulty installation
Installation executive behavior
Not yet installed
Add a page that scores the solar panel:
Page name: Score Solar Panel (if you don't see the page name field, scroll up)
Question 1:
Type: Score
Question: Score our solar panels
Add a page that provides details on low scores:
Page name: Low Score Details (if you don't see the page name field, scroll up)
Question 1:
Type: Long Text
Question: Tell us why you rated our solar panels
Insert the response for the Score our solar panels question into the Tell us why you rated our solar panels question.
Add a thank-you message (we won’t check this)
Add an image at the end of the thank-you message
Select Default Settings (we won’t check this):
Email Settings
Content: Question: Rate your experience with the solar panel installation. (Rating)
Email Templates: None
Email Sender Address: None
Language Settings
Language: English
Save the survey
