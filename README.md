### Project Title: 

#### Brat Pack: Daycare System

### **Live Demo:** 

https://www.alexaperezg.com/BratPack/

This live demo is only to show the features which I worked in, without the login functionality to facilitate navigation for demo purposes only.

### **Project Description:** 

Group project developed to create a tool for parents and staff members that helps them communicate with each other and keep track of every detail of their child’s time at the daycare. Features worked on were "Contact Form" and "Pickup Schedule", in the link above you can see the demo of these features from an Admin and Public point of view.



- ***HomePage:\***
- PHP SESSIONS     implemented for user login functionality and navigation, if user is parent     the navigation will be different than if the user is admin. They have     access to different pages.
- ***Contact Form (Feature 1):\***
- Contact form filled out by parents if they have any questions about the daycare, once the form is submitted an email is automatically sent to their email using the **PHPMailer** confirming their information. Admins are able to see the list of forms submitted where they can **search** by name, **filter** by status, show a specific form, update or delete the forms.
- ***Pickup Scheduler (Feature 2):\***
- Form to be filled out by parents to let the daycare know if someone else is pickup their child up on a specific date. Once they submit the form an email sent to the Pickup email using the **PHPMailer** confirming the information and date. Admin side has access to a list view of all the scheduled pickups where they can **search** by student name, **sort** by date, and a **calendar view** using FullCalendar where they can either view a whole month, week or day. Using **CSS/JS Modal** created a popup , if they click the event they get the name of the child and the person picking them up that day. Admin also can edit, or delete entries in the scheduler.

### Roles:

- Developer
- Designer
- Team Lead

### Languages used: 

- HTML 
- CSS
- PHP
- JavaScript
- Bootstrap
- PHPMailer
- MySQL 
- phpMyAdmin 
- jQuery
