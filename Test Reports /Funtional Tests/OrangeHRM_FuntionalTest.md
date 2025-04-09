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


**OH004- Session time out**

Description: Verify that the session expires after inactivity.

Steps

a. Log in with valid credentials


b.  Stay inactive for the defined session timeout period (15 minutes)

c. Try to navigate to another page or perform an action

Result expected: Session will close and redirect the user to the login screen.


Actual result: 20m passed and the session is still opened.

Status: Failed

