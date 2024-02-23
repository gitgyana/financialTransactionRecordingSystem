CRUD Application Design using Additional Features in Flask

Overview
	CRUD, which stands for Create, Read, Update, Delete, are basic functionalities that any application based on a database must possess. The development of these features requires additional knowledge of handling routes and requests. You also require multiple endpoint HTML interfaces to accommodate different requests. 
	For this, you will develop a financial transaction recording system. The system must be capable of Creating a new entry, Reading existing entries, Updating existing entries, and Deleting existing entries.
	
Objectives
	After completing this, you will be able to:
	• Implement "Create" operation to add transaction entry
	• Implement "Read" operation to access the list of transaction entries
	• Implement "Update" operation to update the details of a given transaction entry
	• Implement "Delete" operation to delete a transaction entry.
	
The application has three different web pages. 
	The first one displays all the recorded transactions. This page is called Transaction Records and displays all the transactions entries created in the system. This page also gives an option to Edit and Delete the available entries. The option of adding an entry is also available on this page. 
	The second page is Add Transaction which is used when the user chooses to add the entry on the previous page. The user adds the Date and Amount values for the new entry. 
	The third page is Edit Transaction which is user navigated to upon clicking the edit entry option. On this page also, the date and amount are accepted as entries; however, these entries are then reflected against the ID that was being edited.
