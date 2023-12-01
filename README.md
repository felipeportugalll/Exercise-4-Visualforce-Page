# Exercise 4 Visualforce-Page
Use Case
Express Logistics and Transport customer got to a point where it has a large number of Contacts associated and it’s hard to handle them.

Requirements
1.  Create a custom field on the Contact object: Is Primary Contact(checkbox);

2.  Create the Express Logistics and Transport  Account, install Data Loader, and import 2 000 Contacts for it using Data Loader.

3.  Create a Visualforce page that displays the following:

Account Details: Account Name, Account Number, Type, Active, Phone, Fax. The fields should be displayed as input fields using the Standard Controller. A Save/Cancel Option should be available.
Related Contact list with the following read-only columns: Name, Title, Phone, Is Primary Contact.
Besides the Contact Information, another column should be displayed:

If the Contact is set as a Primary Contact, then an icon should be displayed 
If the Contact is not set as a Primary Contact, then a link should be displayed that will allow the user to set the Contact as a primary contact. When clicking the link, a confirmation pop-up should be displayed to make sure that the user hasn’t accidentally clicked the link. If the user clicks yes, the selected contact will be set as primary and all the other contacts will be secondary (Is Primary Contact should be false).
A Search by Contact Name should also be available for the Contact list;
4.   Create a "Set Primary Contact" custom button that will redirect the user to the Visualforce page and add it to the Account Layout.

![Button redirection on classic](https://github.com/felipeportugalll/Visualforce-Page/assets/108902942/64c481b2-82a4-4eb1-a753-fff140188d8b)
![Button on lightning](https://github.com/felipeportugalll/Visualforce-Page/assets/108902942/f8af91b5-e397-476b-a894-5cb5b2f8e852)
![Set primary contact on lightning page ](https://github.com/felipeportugalll/Visualforce-Page/assets/108902942/3577e21e-ab4f-4f71-ba6c-b683d11edd75)
![Set primary contact on classic](https://github.com/felipeportugalll/Visualforce-Page/assets/108902942/c5c99e88-5ac6-45d4-95b5-6a7013d804a6)

Custom field Is Priary Contact (checkbox) can be seen in exercise 1 apex triggers
