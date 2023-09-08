<p>
  <h1 align="center">
    <b>
  Check Mate     <!--The title for my project.--> 
    </b>
  </h1>
</p>
In this project, we have executed a Todo webpage named as CheckMate. This webpage can be used to make Todo lists, which are highly beneficial to prioritise and store daily tasks which need to be done. Unlimited 
number of new tasks can be added and removed as per user convenience. Once you complete a task, you can check it off as completed. 
"Checkmate" is a user-friendly and efficient to-do list web application meticulously crafted with JavaScript, HTML, and CSS. Designed with simplicity and productivity in mind, Checkmate empowers users to manage 
their tasks effortlessly.

- My Linkedin profile: <a href="https://www.linkedin.com/in/himesh-mohapatra-386aa8224/">```Linkedin```</a>

- My GitHub profile: <a href="https://github.com/himeshx">```Github!```</a>
<hr>

## HTML Layout

The index.html file gives the basic framework for the webpage. In the head tag, we have linked the style.css file which provides the styling for the page and also imported fonts from fontawesome.

In the body tag, firstly we have used wrapper to center the contents of the webpage. Now, we have created a class named inputField with text type input to "Add Your New Todo List". Beside that, we have added a *"plus"* button to add in more fields.
Now, we add an unordered list tag with class as todoList.

In the footer class, we have added a span element showing the number of pending tasks. At the end, we have added a button *"Delete All"* to clear all the tasks from the list.

Lastly, we have linked the script.js file in the body tag.

<hr>

## CSS Styling

In the style.css file, we have styled the various elements of the webpage according to our will. We have specified the height, width, padding and background colour for the body of the page and also given different colours for user selections.

In the wrapper class, we have styled the header and inputField differently. The input field box has been given a flex display.

Further, we have styled the input in the input field. We have also added the hover feature to the inputField button.

Now, we have styled the various list items present in the unordered list.

<hr>

## JavaScript Interaction

Now, we'll talk about the JavaScript interaction which makes our page functional.

First, we have created variables for inputBox, addBtn, todoList, deleteAllBtn, and input. Then, we have added functioning for taking user input in the input field.

Further, we have created a showTasks function to show all the entered tasks in the list. Then, we have created a variable pendingTasksNumb to store the number of pending tasks for the user.

Following this, we have added an event listener for the input field to enable adding of new tasks through the ENTER key in the text field.

We have also added a functioning delete button beside each stored task to remove it from the list.

At the end, we have added a deleteAllBtn to delete all the stored tasks from the list.
<hr>

<h2 align="left">
  <b>
    ©️ Copyright Disclaimer
  </b>
</h2>

- Under section 107 of the Copyright Act 1976, allowance is made for "fair use" for purposes such as criticism, comment, teaching, education, scholarship and research. Fair use is a use permitted by the copyright statute that might otherwise be infringing. Non-profit, educational or personal use tips the balance in favour of fair use.   
