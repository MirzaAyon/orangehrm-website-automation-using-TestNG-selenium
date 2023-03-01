# orangehrm-website-automation-using-TestNG-selenium

### Tasks
Scenario:
1. Login to orange hrm demo site
https://opensource-demo.orangehrmlive.com/

2. Create 2 new employees and save it to a JSON list
3. Now go to PIM dashboard and search by 1st user name. Assert that the user is found.
4. Now click on the user from the search table and update id by random userid
5. Now again search the user by new user id from the PIM dashboard menu and assert that the user is found
6. Now logout from admin and login with the 2nd user from your JSON list
7. Now click on My Info menu
8. Select Gender and Blood Type and save it
9. Click on contact details and input address and email
10. Logout the user

### Testcases: 
- Admin will not be allowed for Login with Invalid username and password
- Admin can Login successfully with valid username and password
- Exployee can not be created without username
- Create first employee.
- create second employee.
- Search existing employee with invalid name.
- Search employee with valid name.
- Update employee Id by random Id.
- Search employee again with newly updated employee id.
- Logout by Admin.
- Login with second user with a valid login information.
- Insert the second user's Gender, Blood, Address and email.
- Logout from second user.

### How to run this project
- Clone this project
- Goto terminal and give the command of  ```gradle clean test```
- Allure reporting  commands: ```allure generate allure-results --clean -o allure-report``` and ```allure serve allure-results```