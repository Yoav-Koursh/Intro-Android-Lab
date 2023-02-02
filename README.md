# Intro to Android Studio Lab

## Objective: 
In this lab, you will learn to implement the essentials of Android Studio and working with Java & XML!  

By the end of this lab, you will have a template of a signin page.  

## Instructions:

In this lab, we'll be creating a sign in page using TextView, EditText & Button!  

1. Create and set up a new `Android Studio` project:
    - Go to new -> new project -> Empty Activity.
    - Make sure your code is in **Java**.

2. In your XML file:
    1. Change the layout to `linear layout`.
          - Don't forget the linear layout attributes.
    2. Add:
          - A `TextView` that says SignIn.
          - Two `EditTexts` for email & password, **hint:** Don't forget the difference between hint and text.
          - Two `Buttons` one says signin and the other signup.
              - Organize the buttons to be next to each, **hint: LinearLayout**
          - **Don't forget to add ids**

3. In your Java file:
      1. Connect the views from the `XML file` to the `Java file`.
      2. Set an `onclick listener` for both button:
        - When the signin `Button` is clicked:
            - Set the text of the EditTexts to be the email of the user.
        - When the signup `Button` is clicked:
            - Using Toast, display "Signup is under construction" as a message.


##### Call an Instructor/TA to check your completed tasks
 
###### make sure you commit and push your code.
