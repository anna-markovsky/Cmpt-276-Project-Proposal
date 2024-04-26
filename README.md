
**The employee code for sign up is childhelp2020
**

https://group-project-l2iu.onrender.com/homepage

Cmpt 276 Group Project ideas

Summary of customer requirements: 
home page with like an about section for why is the toy and clothing drive important
an about us like abt the brand page
an our partners page
Which is like we need to like write down the company that they partner with, add the logo and link to their websites
an employee login to access the database
Inventory (clothing and toys) sorting: 
toy inventory where the toys are sorted by age range and genre or like books/sports stuff
for the clothes it should be sorted by age range and gender


Questions to ask him: 
What website features does he need? 


Are there any restrictions on how he wants the toys to be sorted? 
What type of information about the toys would he like to be recorded in the database? 
Is there a certain website layout he would like? 


Sort by:
Puzzles, action figure, sports 
Age and gender

Layout:
Reflect brand

Inventory display:
Table for employ view, data entry
For 


Marking scheme from Canvas:
Marking:
Login/Logout/Signup functionality with landing page for different types of users
Extra features - that are most important to your app (according to your client)
A good distribution of work
Report 
Client contact / info present?
Are there a good amount of stories described in the report?
Are the stories presented out in a consistent manner?
Is there a mention of persona, action, and result?
Do they have test cases, both success and failure cases?
Are the stories clear and well explained?
UI mockup present to support any stories that may be unclear?
Story 4: Change of User Name in Profile
*Description: As a registered user of ChildHelp, I want to be able to change the name associated with my username on the website, ensuring that my profile accurately reflects my current legal name or preferred name.

*Actors: A registered user of ChildHelp (e.g., Volunteer, Inventory Clerk, Administrator).

*Trigger/Precondition: The user navigates to the ChildHelp webpage and selects the login option. They are then directed to a login form, where they input their correct login details. Upon successful authentication, the system grants them access to their profile settings.

*Actions/Post Conditions:
1. Once logged in, the user navigates to the "Profile Settings" or "Account Settings" section of the website.
2. In the profile settings, the user finds an editable field for their "Name."
3. The user enters their new name or modifies the existing one and selects the option to "Save Changes" or "Update Profile."
4. Upon successful validation, the system updates the user's name associated with their username in the ChildHelp database.


*Acceptance Tests:
1. A user logs into their account with their credentials (e.g., username: VolunteerMike, password: nameChange789).
2. VolunteerMike navigates to "Profile Settings" and changes the name field from "Michael" to "Mike."
3. Upon saving the changes, the system checks for input validity and updates the name in the database.
This user story is focused on enhancing user satisfaction by allowing personalization of profile information, ensuring that the system is inclusive and respects users' preferences for identification.

Story 5: Change of password associated with Profile
User Story: Change Password

*Title: Update User Password

*Description: As a registered user of ChildHelp, I want to change my old password to a new one to enhance my account's security and ensure that my access remains protected.

*Actors: A registered user of ChildHelp (e.g., Volunteer, Inventory Clerk, Administrator).

*Trigger/Precondition: The user navigates to the ChildHelp webpage, selects the login option, and logs in with their current credentials. After successful login, they access their account settings.

*Actions/Post Conditions:
1. Once logged in, the user navigates to the "Account Settings" or "Security Settings" section of the website.
2. The user selects the option to "Change Password."
3. The user is prompted to enter their current password for verification purposes, followed by the new password and a confirmation of the new password in separate fields.
4. The system checks the current password against the user's existing password in the database for verification.
5. The system validates the new password based on predefined security criteria (e.g., minimum length, must include letters, numbers, and special characters).
6. Upon successful verification and validation, the system updates the user's password in the  database.

*Acceptance Tests:
1. A user (e.g., username: AdminBeth) logs into their account with their current credentials.
2. AdminBeth navigates to "Account Settings" and chooses to "Change Password."
3. She inputs her current password for verification,if the password is correct then only the password is changed . 
4. If the current password is correctly verified and the new password meets all requirements, the system updates her password.
This user story focuses on ensuring user security and account integrity by facilitating a secure and user-friendly process for password updates on the ChildHelp website.

database:  psql -h dpg-cnjoa921hbls73dqtrt0-a.oregon-postgres.render.com -U group_project_db_user -d group_project_db

password: DmtRqJ1aUB2ImyJAM3Umnn6KnNwBaQ1q


