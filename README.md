# Ticketmaster-Take-Home-Challenge

- The challenge set as part of the Founders and coders Ticketmaster Take home challenge apprenticeship application process. 


 ## user stories
  
- A fan can be notified via email or SMS, so the form should allow submission of email address and/or mobile phone number

- A fan must be signed in to Ticketmaster in order to add themselves to the waiting list. If they're not signed in, we'll prompt them to sign in when they click the "join the waiting list" button.

- Once a fan is signed in, we'll have their email address, so we will pre-fill the email address field with it

- A fan can optionally add their phone number to the form

- If a fan adds a phone number, they should be given the option to disallow contact via email
- A fan should not be allowed to submit an empty form

- Successful submission of the form should send a POST request to the waiting list API which will return a success or error response

- The waiting list API should be called when the form loads, to prevent adding the fan to the waiting list multiple times. If the fan is already on the waiting list the fan should see a message informing them of that

## The Challenge

- Break these requirements into separate user stories. Bear in mind the requirements may not be a complete list, feel free to add more stories as you see fit
- Focus on the front end side of things - assume that the APIs already exist and work correctly for waiting list checks/submission/user sign in
- On a new GitHub repo, create an issue for every user story
- Decide which user story you are going to focus on for the take-home challenge
- Attempt to complete the selected user story. Do not attempt to complete the whole feature!
- If you fancy it, we welcome any critique or alternative suggestions for the design if you feel like it could be improved

## The User story chosen

- I decided to work on the user story in which user would click on the join waiting list button and is taked to a page where the form is ready.

## Design and styling 

- For the design I went with a simple fully responsive page mimicing the actual Ticketmaster form.
- Used the CSS box model to add the different div sections with class names added for styling. 
- media query added for responsiveness when used in varying screen sizes.
-

## Stretch goal

- I intend to make the form fully functional using javascript.
- 


