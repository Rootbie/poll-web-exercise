# Requirements:

1. On your assigned web space, create a folder for this task.
In that folder (or subfolder), you will eventually have two basic files: your HTML’s file (your page) and your 
CSS file (that page’s stylesheet). These two files will be in the same folder because they need to “talk” to each 
other.

Functional Requirement:
- Background color of all button must be green.
- Placeholder text in inputs must be in light gray color. You have to define the placeholder for each input text with same value as above figures.
- Add a new file called styles.css to customize the default CSS style of Bootstrap 4.

![image](https://github.com/Rootbie/poll-web-exercise/assets/95699016/d23dc5b8-da07-443c-bbb5-1b9813a99980)
![image](https://github.com/Rootbie/poll-web-exercise/assets/95699016/3e419ec7-1ceb-43a8-8bf6-fb1545b87051)

2. U must use jQuery (or Javascript) to validate data in the create interview page, the item 
definition as below:

![image](https://github.com/Rootbie/poll-web-exercise/assets/95699016/8a9705d0-c0da-4682-bd59-3743b510ed00)

3. Use Javascript or jQuery to add a new question and add new answer. The design for this feature as the photo 
below:

![image](https://github.com/Rootbie/poll-web-exercise/assets/95699016/2223ee15-b494-47da-859e-0d4fd4c894e8)

4. Use Ajax in the manage question page. If user click to delete button, its will show the confirm box to make sure 
user want to delete this item.

![image](https://github.com/Rootbie/poll-web-exercise/assets/95699016/fe8b5e61-65de-4f92-a52e-6d38b5b400a9)

- After that, if it is confirm ok, you must send data to server to delete this item via Ajax. 
If click into login button at right menu, it will show a popup, it show form to login user.

![image](https://github.com/Rootbie/poll-web-exercise/assets/95699016/562d61ff-0518-4cee-a0a0-caa35f144afc)


Functional Requirement:
- The form must be checked to make sure all the mandatory fields are filled in the input tag. It would
  require just a loop through each field in the form and check for data.
  
- If validation fails, the system should let the users know it by providing a clear and unambiguous
  message (usually one or two sentences) and ways to correct errors. Since users need to notice an
  error message immediately, it is a good practice to position it at the top of a web form, before all the
  other fields. This will also allow screen readers to easily access the message.
  
- Apart from the error message and a list of invalid fields, the system should clearly mark fields that are
  invalid. This can be done in one of the following ways (or any combination of them):
    + By providing red inline messages or markers next to every invalid field
    + By changing the color of field labels

- Rules of thumbs in web form validation design
    + Never omit server-side validation.
    + Don’t provide confusing validation feedback. It should clearly communicate the errors and 
      ways to fix them.
    + Don’t let users think about what information is required, always clearly mark required fields.
    + Never provide validation feedback on a single page or in a popup alert.
    + Don’t use dynamic effects as compensation for a badly designed form. Fancy effects won’t
      hide a poorly designed web form.
    + Don’t forget to inform users when the form was completed successfully. It is as important 
      as a good validation feedback.
      
- Use Ajax to get data from a HTML file
    + It loads the HTML document and sanitizes it
    + It only returns the body content of the HTML - so no styling (other than inline styles) will 
      get through.
