# Python Contacts agenda with time tracking for learning purposes

## Prerequisites
- [X] [Python](https://www.python.org/downloads/)
- [ ] [Visual Studio Code](https://code.visualstudio.com/download) - _optional_

## Specification
A lawyer customer wants to have a small contacts application that will store the following information:

- Names
- Addresses
- Telephones

Moreover, the application needs to be able to do the following:
- Edit the existing contacts
- Find the existing contacts
- Track the time spent working for each contact

## User Instructions for the application

- Clone this repository

```shell
git clone git@github.com:dlavric/python-contacts.git
```

- Open the application with your Python IDE or Visual Studio Code

- Run the application
```
press "F5" from the keyboard
```

- The Menu of the application:

```python
Time Tracker

1. New Contact
2. Find Contact
3. Edit Contact
4. Add Session
5. Exit Program

Enter your command:
```
**NOTE: The contacts agenda is empty, new contacts need to be created to use the application.**

- Select 1 "1. New Contact":

```python
Enter your command: 1
Create new contact
Enter the contact name: Manny 
Enter the contact address: USA    
Enter the contact phone: 1456238975
```

- Select 2 "2. Find Contact":

```python
Enter your command: 2
Find contact
Enter the contact name: manny
Name: Manny
Address: USA
Telephone: 1456238975
Hours on the case: 0
```

- Select 3 "3. Edit Contact":

```
Enter your command: 3
Edit contact
Enter the contact name: manny
Name:  Manny
Enter new name or . to leave unchanged: Manny Jr. 
Enter new address or . to leave unchanged: USA, Colorado, Colorado Springs
Enter new telephone or . to leave unchanged: .
```

- Select 4 "4. Add Sessions":

```python
Enter your command: 4
add session
Enter the contact name: manny
Name:  Manny Jr. 
Previous hours worked : 0
Session length : 4
Updated hours worked : 4.0
```

**NOTE: Time spent on each contact can be added**

```python
Enter your command: 4
add session
Enter the contact name: manny
Name:  Manny Jr. 
Previous hours worked : 4.0
Session length : 1
Updated hours worked : 5.0
```

- Select 5 "5. Exit Program"

```python
Enter your command: 5
save contacts
```

## Technical Details

### This Repository Includes:
- [X] [BTCInput.py](https://github.com/dlavric/python-contacts/blob/main/BTCInput.py)
- [X] [tiny-contacts-time-tracker.py](https://github.com/dlavric/python-contacts/blob/main/tiny-contacts-time-tracker)





