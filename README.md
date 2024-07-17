# regestrasionform
This HTML and JavaScript code creates a registration form with client-side validation. Here’s a detailed explanation of the form’s structure, its functionality, and the validation logic applied to it:
Prevents the default form submission to perform custom validation.
Clears any previous error messages.
Validates the username to ensure it does not exceed 10 characters.
Validates the email to ensure it ends with @gmail.com or @org.com.
Validates the phone number to ensure it starts with 7, 8, or 9 and has exactly 10 digits.
Validates the password to ensure it is at least 5 characters long and includes at least one number.
Validates that the password and confirm password fields match.
If all validations pass, displays a success message and submits the form.

Validation Logic
Username: Ensures the username is 10 characters or fewer.
Email: Uses a regex to check that the email address ends with either @gmail.com or @org.com.
Phone Number: Ensures the phone number starts with 7, 8, or 9 and is exactly 10 digits long.
Password: Validates that the password is at least 5 characters long and contains at least one digit.
Confirm Password: Checks if the confirm password field matches the original password.
