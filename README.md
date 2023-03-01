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

### Allure report screenshots:
![334039326_1214379395873219_2230216209726739646_n](https://user-images.githubusercontent.com/68238652/222172978-c2c61217-50fb-46fd-bb16-fed782283af0.png)
![334465098_596534729004092_7765380339442460219_n](https://user-images.githubusercontent.com/68238652/222173567-50beb483-5f49-4234-9d38-1251baa72d2d.png)
![334466237_218052593944262_3308727144411942175_n](https://user-images.githubusercontent.com/68238652/222173712-3d231211-bb65-42a8-bd9d-2bc1d83f1472.png)

### Projects implementation full video:

https://user-images.githubusercontent.com/68238652/222173898-793b835e-073d-4b22-bdf3-6243e4ae0628.mp4


