# Sprint 1: Build a Signup Form

Today's assignment is to build a signup form for a web service and style this according to how you want it to look. In the end you will also post the data from the form into a service called HTTPbin and it should show the data you put in. It is basically a server and will work in the same was as if we posted this data to our own server to for example create a user account. 

## How to complete this assignment

1. Go online and find a page with a form that you like the looks of. Today you choose which page with a form you want to copy. Add the page that you are copying into the Readme file in your Github repo for this assignment.  

1. Build a form that at a minimum contains: 
* 2 x Text fields
* 1 x A password field
* 1 x Set of radio buttons
* 1 x Set of checkboxes
* 1 x Submit button

2. Set the form action to post to `https://httpbin.org/post` and the method set to `post`. This means that httpbin will show you how this response would look like if you sent this to a server. Try sumbitting your form and see if you can se the response on httpbin. 

3. Let's poke around with your form and see what response you get for the following scenarios: 
* How does the textfields look like? 
* What response do you get from the password field? 
* Try select one or a few of the radio buttons.
* Select none of the radio buttons.
* Check the checkboxes. 
* Leave the checkboxes unchecked. 

4. Add an `in-focus` effect for when you click on the fields. Make the border or the background of the field change colour and add a glow effect. 

5. Style the rest of the page and the form so that it looks like the one you picked. 

The `starter-code` folder containers a boilerplate html file and css. 

To complete this assignment, you need to fork this repository, make changes to your copy, and then submit a pull request on GitHub (from your repository into the technigo one) for review. Don't forget to add a link to your inspiration for your form into the `readme-file`. 

### :books: Reading List

* [W3Schools – GET vs. POST](https://www.w3schools.com/tags/ref_httpmethods.asp)
* [W3Schools – About HTML Forms](https://www.w3schools.com/html/html_forms.asp)
* [W3Schools – Form Elements](https://www.w3schools.com/html/html_form_elements.asp)
* [MDN – Styling HTML forms](https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms/Styling_HTML_forms)

---

### :boom: Success!

After completing this assignment, you should be comfortable in building forms in HTML and to send these with the `post`method. You will also know how the data you send looks like on the server side to later be able to use for example to create an account. You should also understand what a `post` method is and how to send information over http. key

---

### :runner: Stretch Goals

Done with the main task? Here's some ideas for things to continue with:

1. Make the page responsive and work good for mobile and tablet. 
