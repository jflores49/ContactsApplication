# Contacts Application  
My project is a contacts application. It allows you to enter the first name, last name, phone number, and email of a person, which is then saved to a json file when the "Add Contact" button is clicked. The user then has the option to search for a contact by partially inputting their first or last name and clicking the search button. Upon using the search functionality, if any contacts are found, they will be displayed in a list. If the user clicks on a contact from the list, they have the option to delete the contact, or update any of the contact's information.

# Technical Section 
The contacts application follows the MVC structure. The Contacts class is the model, the ContactBook class is the controller, and the Main class is the view. The Main class is the main file to run the program. I implemented inner classes and lambda expressions in the Main class. I used JSON-simple to store the contacts. Something we did not cover in class that I implemented is javafx listview and sortedlist. Both listview and sortedlist are in the Main class. I used listview to display the contacts found when a user searches for a contact. I then used sortedlist to allow a user to sort the listview by last name. I also implemented dialog boxes with custom messages for different scenarios. If a textfield is left blank or has only white spaces, a dialog box will pop up saying the contact cannot be saved due to a blank field. When a contact is updated or deleted, dialog boxes will also pop up saying the contact has either been successfully updated or deleted. There is also a clear button that will clear the entire form when clicked. 
