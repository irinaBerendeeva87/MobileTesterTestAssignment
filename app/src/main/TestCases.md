**Test cases for user registration and login feature:**
---
> User registration
---
### № UR1 Registration with email and password ###
**Preconditions:** 

- The app is installed on a mobile device.
- The user has not registered before.
- The mobile device is connected to the internet.
- The user opens the registration page of the app.

**Steps** 

1. Click on the "Continue with email" button on the login screen.
2. Enter valid email and password.
3. Click on the Sign up button.

**Expected result:** 
User account is created successfully. 

---
№ UR2
#### User receives a confirmation email upon successful registration. ####

**Preconditions:** User has successfully registered with the app.

**Steps** User checks their email inbox for the confirmation email.

**Expected result:**  User should receive a confirmation email with instructions to verify their account and login to the app.

---
№ UR3
#### Registration with invalid email ####
**Preconditions:**

- The app is installed on a mobile device.
- The user has not registered before.
- The mobile device is connected to the internet.
- The user opens the registration page of the app.

**Steps**
1. Enter an invalid email  (such as an email without '@' symbol).
2. Enter a strong password.
3. Click on the Sign up button.

**Expected result:**
The user should not be able to register with an invalid email format.
The app displays an error message indicating that the email format is invalid.

---
№ UR4
#### Registration with invalid password ####

**Preconditions:**

- The app is installed on a mobile device.
- The user has not registered before.
- The mobile device is connected to the internet.
- The user opens the registration page of the app.

**Steps**
1. Enter a valid email.
2. Enter an invalid password(such as a password with spaces).
3. Click on the Sign up button.

**Expected result:**
1. The user should not be able to register with an invalid password.
2. The app displays an error message indicating that the password format is invalid.
---
№ UR5
#### Registration with duplicate email ####

**Preconditions:**

- The app is installed on a mobile device.
- The user has not registered before.
- The mobile device is connected to the internet.
- The user opens the registration page of the app.

**Steps**

1. Enter a duplicate email address.
2. Enter a strong password.
3. Click on the Sign up button.

**Expected result:**

1. The user should not be able to register with email which  already exists.
2. The app displays an error message indicating that the password format is invalid.
---
№ UR6
#### Registration is not possible if the required field is not filled ####

**Preconditions:**

The app is installed on a mobile device.
- The user has not registered before.
- The mobile device is connected to the internet.
- The user opens the registration page of the app.

**Steps**

1. Leave the email field blank.
2. Enter a strong password.
3. Click on the Sign up button.

**Expected result:**

1. The user should not be able to register without email
2. App should mark all required fields and prevent user from proceeding until all fields are filled.
---
№ UR7
#### Registration with Google account ####

**Preconditions:**

- The app is installed on a mobile device.
- The user has not registered before.
- The mobile device is connected to the internet.
- The user opens the registration page of the app.

**Steps**
 
1. Click on the "Continue with Google account" button on the screen.
2. Click on the "Continue" button on the permission 
3. Choose user account.

**Expected result:**

User should be registered successfully and redirected to the app homepage/ Profile.

---
№ UR8
#### Registration with Apple account ####

**Preconditions:**

- The app is installed on a mobile device.
- The user has not registered before.
- The mobile device is connected to the internet.
- The user opens the registration page of the app.

**Steps**

1. Click on the "Continue with Apple account" button on the screen.
2. Click on the "Continue" button on the permission.
3. Click on the "Continue" button on the screen.

**Expected result:**

User should be registered successfully and redirected to the app homepage/ Profile.

---
№ UR9
#### Registration with Facebook account ####

**Preconditions:**

- The app is installed on a mobile device.
- The user has not registered before.
- The mobile device is connected to the internet.
- The user opens the registration page of the app.

**Steps**

1. Click on the "Continue with Facebook account" button on the screen.
2. Click on the "Continue" button on the permission.
3. Choose one of the options with cookies. 
4. LogIn  with credentials of the Facebook account.
5. Click on the "Log In" button.

**Expected result:**

User should be registered successfully and redirected to the app homepage/ Profile.

---
> User log In
---

№ UR10
#### Log in with valid credentials ####
**Preconditions:**

- The app is installed on a mobile device.
- The user has a valid registered account.
- The user has a stable internet connection.
- The user opens the registration page of the app.

**Steps**

1. Clicks on the "Log in" button.
2. Enter valid credentials.
3. The user clicks on the "Log in" button.

**Expected result:**

1. The user is successfully logged into the app and is redirected to the Home page /Profile.
2. App displays user account information correctly after login.

---
№ UR11
#### Can't log in with invalid credentials (email or password). ####

**Preconditions:**

- The app is installed on a mobile device.
- The user has a valid registered account.
- The user has a stable internet connection.
- The user opens the registration page of the app.

**Steps**
1. Clicks on the "Log in" button.
2. Enter an invalid email or password.
3. Click on the "Log in" button.

**Expected result:**

An error message should be displayed indicating that the email or password is invalid.

---
№ UR12
#### Log in with incomplete credentials ####

**Preconditions:**

- The app is installed on a mobile device.
- The user has a valid registered account.
- The user has a stable internet connection.
- The user opens the registration page of the app.

**Steps**

1. Clicks on the "Log in" button.
2. Enter an invalid email or password.
3. Leave one or more required fields blank.

**Expected result:**

App should mark all required fields and prevent user from proceeding until all fields are filled.

---
№ UR13

#### Login with Autofill Feature

**Preconditions:**

- The app is installed on a mobile device.
- The user has a valid registered account.
- Device has a stable internet connection.
- Launch the  app.
- Click on the "Log in" button.

**Steps**

1. Select email and password from the autofill suggestions.
2. Click on the "Log in" button.

**Expected result:**

The user is successfully logged into the app and is redirected to the Home page /Profile.

---
№ UR14

#### Login with Biometric Authentication ####

**Preconditions:**

- The app is installed on a mobile device.
- The user has a valid registered account.
- Device has a stable internet connection.
- Launch the  app.
- Click on the "Log in" button.

**Steps**

1. The app prompts to use biometric authentication (e.g. fingerprint or face ID).
2. Use biometric authentication to log in.

**Expected result:**

The user is successfully logged into the app and is redirected to the Home page /Profile.

---

№ UR15
#### User login with Google/Apple account ####
**Preconditions:**

- The app is installed on a mobile device.
- The user has a valid registered account.
- Device has a stable internet connection.
- Launch the  app.
- Click on the "Log in" button.

**Steps**

1. Click on the "Login with Google" or "Login with Apple" button.
2. Enter the credentials of the Google/Apple account.
3. Click on the Login button.

**Expected result:**

 User should be logged in successfully and redirected to the app homepage/Profile.

---
№ UR16
#### User login with Facebook account ####
**Preconditions:**

- The app is installed on a mobile device.
- The user has a valid registered account.
- Device has a stable internet connection.
- Launch the  app.
- Click on the "Log in" button.

**Steps**

1. Click on the "Login with Facebook" button.
2. Enter the credentials of the Facebook account.
3. Click on the Login button.

**Expected result:**

User should be logged in successfully and redirected to the app homepage/Profile.

