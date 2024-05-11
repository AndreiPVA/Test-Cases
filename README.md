# Test Case Samples

Below are some Test Case samples that I wrote while working on previous projects.

----------------

**Description:**
Check if login works when a person uses correct credentials.

**Steps to reproduce:**
1. Open website.com/login
2. Add correct user/password
3. Click "Login" button

**Expected result:**
User should be able to login and is redirected to his profile page.

**Test data:**
- User: Andrei
- Password: 12345

**Pre-conditions:**
User should have a valid account.

----------------

**Description:**
Check if login works when a person uses correct credentials.

**Steps to reproduce:**
1. Open https://auth.emag.ro/user/login
2. Add correct email adress
3. Click "Continua" button
4. Add correct password
5. Click "Continua" button

**Expected results:**
1. User should be able to open the login page
2. User should be able to add his correct email adress
3. User should be able to go to the next step and add his correct password
4. User should be able to add his correct password
5. User should be able to login and is redirected to his profile page

**Test data:**
- User: Andrei
- Password: 12345

**Pre-conditions:**
User should have a valid account.

----------------

**Description:**
Check if login doesn't work when a person uses invalid credentials.

**Steps to reproduce:**
1. Open https://auth.emag.ro/user/login
2. Add invalid email adress
3. Click "Continua" button

**Expected results:**
1. User should be able to open the login page
2. User should be able to add an invalid email adress
3. User should be redirected to "Create new account" page

----------------

**Description:**
Check if login doesn't work when a person doesn't use credentials.

**Steps to reproduce:**
1. Open https://auth.emag.ro/user/login
2. Click "Continua" button without adding an email adress

**Expected results:**
1. User should be able to open the login page
2. User should get a "Required field" error

----------------

**Description:**
Check if the search feature returns results when the user searches for products.

**Steps to reproduce:**
1. Open https://www.emag.ro/
2. Add a product name on the search bar
3. Click "Magnifying glass icon" button or "Enter" button

**Expected results:**
1. User should be able to open the home page
2. User should be able to add a product name on the search bar
3. User should be redirected to a search results page

----------------

**Description:**
Check if the search feature can fully autocomplete the name of a product when the user enters the first 3 digits from a product name.

**Steps to reproduce:**
1. Open https://www.emag.ro/
2. Add the first 3 digits from a product name on the search bar

**Expected results:**
1. User should be able to open the home page
2. The name of the product should be fully autocompleted

----------------

**Description:**
Check if the search feature doesn't return errors when the user searches for non-existent products.

**Steps to reproduce:**
1. Open https://www.emag.ro/
2. Add a non-existent product name on the search bar
3. Click "Magnifying glass icon" button or "Enter" button

**Expected results:**
1. User should be able to open the home page
2. User should be able to add a non-existent product name on the search bar
3. User should be redirected to a "0 results" page and not get any errors
