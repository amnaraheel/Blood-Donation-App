# Blood-Donation-App
Blood is the vital connection to having a healthy body. For that purpose, we have developed an app to provide compassionate care to the people in need of blood. Or network of generous donors, volunteers and employees share a mission of preventing and relieving suffering, here at home and around the world.

# Methodology
We applied the knowledge we gained in Data Structure and Algorithm course and did some self-study in the compilation of our code. The main two modules of our application are:

- Donor 
- Receiver

These both modules are buttons. The user presses either and then another tab opens. 

Donor:

If the donor button is pressed, then the user is asked for following information to 
donate blood:
- Name
- Phone Number
- Blood Type
- City

Receiver:
 
If the receiver button is pressed, then the user is allotted with a serial number and is provided with a listed of donors and each donor is allotted with a serial number. The user is then asked to enter the serial number and is moved to the next tab and are asked if they have received the blood or not? Upon clicking the “yes” button the donor is moved to the inactive list and is deleted from the active list. All this includes file handling too. We maintain two files for each active list and inactive list which are updated according to the functions performed. And if the “no” is pressed then the user is moved back to the receiver tab where they can apply to receive blood again. 

# Specifications
The specifications of our project are as follows:
- We used Double Linked List as our data structure to minimize the time complexity.
- We used global variables and objects for easy access and to avoid the difficulty of defining the same variable again and again.
- We used Kivy as an external library for GUI.
- We used file handling to handle the data of the donors.
