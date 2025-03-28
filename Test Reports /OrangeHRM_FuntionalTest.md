Description: Ensure that the website has a proper login process, efficient performance, and is user-friendly.

**OH001- Log in with valid credentials**

Description: User use correct credentials.

Steps

a. Open the URL: https://opensource-demo.orangehrmlive.com/web/index.php/auth/login


b. Place credentials: 
Username : Admin
Password : admin123



Result expected: The user should be logged in successfully.
Actual Result: Website log the user in as expected.

Status: Approved

**OH002- Log in with invalid credentials** 

Description: User use incorrect credentials

Steps

a. Open the URL: https://opensource-demo.orangehrmlive.com/web/index.php/auth/login

b. Place credentials: 
Username : Admin
Password : admin1234


c. Click Log In

Result expected: User cannot log in, because of the error.
Actual Result: User is unable to log in, and the error message "Invalid credentials" is displayed.

Status: Approved


**OH003- Log in with spaces**

Description: User log in only placing spaces in username and password.

Steps

a. Open the URL: https://opensource-demo.orangehrmlive.com/web/index.php/auth/login


b. Place spaces instead of credentials

Result expected: Error message, the user cannot log in.
Actual Result: You cant log in, error in section username and password is displayed stating that is required. 

Status: Approved


**OH004- Password Reset**

Description:Verify if the recovery password is functioning correctly and if the instruction are clear.

Steps

a. Open the URL: https://opensource-demo.orangehrmlive.com/web/index.php/auth/login


b. Click "Forgot your Password?"


c. Website ask for Username or email to send the email to be able to reset the password.

Result expected: Website should prompt for the correct credentials and send the email to reset the password
Actual Result:Instruction were clear in how to reset the password, and i was able to reset it.

Status: Approved

