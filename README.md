# Authentication Functional Test Cases Scenarios

## Login Page: 

- Verify that as soon as the login page opens, by default the cursor should remain on the username textbox.
- Verify that the user is able to navigate or access the different controls by pressing the `Tab` key on the keyboard.
- Check if the password is in masked form when typed in the password field.
- Check if the password can be copy-pasted or not.
- Verify that the user is able to login by entering valid credentials and clicking on the `Login` button.
- Verify that the user is able to login by entering valid credentials and pressing Enter key.
- Check that the user is not able to login with an invalid username and password.
- Verify that the validation message gets displayed in case the user leaves the username or password field as blank.
- Check that the validation message is displayed in the case the user exceeds the character limit of the user name and password fields.
- Verify that reset button functionality on the login page. Clicking on it should clear the textbox’s content.
- Verify if there is a checkbox with the label `remember password` on the login page.
- Verify that closing the browser should not log-out an authenticated user. Launching the application should lead the user to login state only.


## Registration Form:

- Verify that the Registration form contains Username, First Name, Last Name, Password, Confirm Password, Email Id, Phone number, Date of birth, Gender, Location, Terms of use, Submit, Login `(If you already have an account)`.
- Verify that tab functionality is working properly or not.
- Verify that Enter/Tab key works as a substitute for the Submit button.
- Verify that all the fields such as Username, First Name, Last Name, Password and other fields have a valid placeholder.
- Verify that all the `required/mandatory` fields are marked with `*` against the field.
- Verify that clicking on submit button after entering all the mandatory fields, submits the data to the server.
- Verify that system generates a validation message when clicking on submit button without filling all the mandatory fields.
- Verify that entering blank spaces on mandatory fields lead to validation error.
- Verify that clicking on submit button by leaving optional fields, submits the data to the server without any validation error.
- Verify that case sensitivity of Username `(usually Username field should not follow case sensitivity – ‘rajkumar’ & ‘RAJKUMAR’ acts same)`.
- Verify that system generates a validation message when entering existing username.
- Verify that the character limit in all the fields `(mainly username and password)` based on business requirement.
- Verify that the username validation as per business requirement (in some application, username should not allow numeric and special characters).
- Verify that the validation of all the fields are as per business requirement.
- Verify that the date of birth field should not allow the dates greater than current date `(some applications have age limit of 18 in that case you have to validate whether the age is greater than or equal to 18 or not)`.
- Verify that the validation of email field by entering incorrect email id.
- Verify that the validation of numeric fields by entering alphabets and characters.
- Verify that leading and trailing spaces are trimmed after clicking on submit button.
- Verify that the `terms and conditions` checkbox is unselected by default `(depends on business logic, it may be selected or unselected)`.
- Verify that the validation message is displayed when clicking on submit button without selecting `terms and conditions` checkbox.
- Verify that the password is in encrypted form when entered.
- Verify whether the password and confirm password are same or not.

# When you’re testing a web application, there are a lot of things you have to check for. This checklist can be divided into six major steps as follows:

  1. Functionality testing
  2. Usability testing
  3. Interface testing
  4. Compatibility testing
      - Browser compatibility
      - Operating system compatibility
      - Device compatibility
  6. Performance testing
  7. Security testing
