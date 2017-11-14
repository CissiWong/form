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

2. Set the form action to post to `https://httpbin.org/post` and the <form> method set to `post`. This means that httpbin will show you how this response would look like if you sent this to a server. Try sumbitting your form and see if you can see the response on httpbin.

3. Try submitting your form to see how the response from httpbin looks:
  * How does the textfields look like?
  * What response do you get from the password field?
  * Try select one or a few of the radio buttons & submit again. What changes?
  * Select none of the radio buttons & submit.
  * Check the checkboxes & submit.
  * Leave the checkboxes unchecked & submit.

5. Style the rest of the page and the form so that it looks like the one you picked.

Use the `code` folder to build your solution.

To complete this assignment, you need to fork this repository, make changes to your copy, and then submit a pull request on GitHub (from your repository into the technigo one) for review. Don't forget to add a link to your inspiration for your form into the `README.md` file in the starter code.

### :books: Reading List

* [W3Schools – GET vs. POST](https://www.w3schools.com/tags/ref_httpmethods.asp)
* [W3Schools – About HTML Forms](https://www.w3schools.com/html/html_forms.asp)
* [W3Schools – Form Elements](https://www.w3schools.com/html/html_form_elements.asp)
* [MDN – Styling HTML forms](https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms/Styling_HTML_forms)

---

### :sos: How to get help
Learning how to think as a web developer is learning how to be an expert in problem solving. So whenever you get stuck start with step 1 and continue until problem solved.

1. Google! In English, type in the error message if there is one, search within the language you're using (ie CSS, JavaScript etc).
2. Ask your code buddies in your Company.
3. Ask your fellow students in Slack.
4. Ask Damien. Please note: we are part of a sharing community - share the answer with your fellows.

---

### :boom: Success!

After completing this assignment, you should be comfortable building forms in HTML and should understand what happens when the form is submitted with the POST method. You will also know how the data you send looks like on the server side to later be able to use for example to create an account.

---

### :runner: Stretch Goals

Done with the main task? Here's some ideas for things to continue with:

1. Make the page responsive and work well on mobile and tablet.
2. Add a focus effect on the input tags (Using the CSS `:focus` pseudo-selector). Make the border or the background of the field change colour and add a glow effect.
3. Make the fields use appropriate input types and validations.
4. Try to make the submit button look "raised up", and on click, look like its not raised up (like [this](https://codropspz-tympanus.netdna-ssl.com/codrops/wp-content/uploads/2012/01/cssbuttons_021.jpg), but the design is up to you)
