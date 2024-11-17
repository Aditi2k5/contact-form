This project is a contact form made mainly using JS frameworks. 
The front-end has been worked on using mainly React along with MaterialUI components as well for some basic styling options. 
The functionality of updating, deleting and adding contacts by the useer has been implemented mainly using localStorage which is used as a web storage. for that session of the user on their browser.

A major change done would be not deciding to use any database or backend as I am not familiar with these frameworks and technologies needed to implement it effectively. I looked up an alternative that could be used to implement the same/similar working as asked and I decided to go ahead with localStorage. It was mentioned to not take assistance of AI coding tools however I did enlist of perplexity AI as this was still quite new to me and for creating an effective table like view in MUI. 

The main file of the app is the contact.js file which holds the functioning if the contact form. useState is used to handle each functioning such as opening the form, closing, editing contact, adding and deleting along with error handling. All of this comes under const ContactForm.

The only requirement to effectively run this in web is to install react, lucide-react(used for deleting and edit buttons), mui packages.
To start the app on localserver: Go to vscode terminal, enter cd contact-form, and npm start.
The app should be running on port 3000 by default.

