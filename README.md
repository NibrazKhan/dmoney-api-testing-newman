## dmoney-api-testing-newman
 Automated dmoney API using Postman where test cases are added for Login,Creating users,Searching users and performed testing for CRUD operations.
 Steps to run this project:
 - Clone this project or export using this collection [link](mainNode.next=oldHead).
 - Give the following commands by opening terminal in the project folder to create newman Report:
 ```
 npm i newman
 ```
 ```
 npx newman run .\collection\Dmoney_Users_collection.json -e -n 1
```
```
npm i newman-reporter-htmlextra
```
```
node .\report.js
```
 - Read the project [Documentation](https://documenter.getpostman.com/view/21520037/UzBmN7Uv).

#### Screenshot of the report generated using newman.

![report_using_newman](https://user-images.githubusercontent.com/55280106/175131634-4e09b597-677c-4232-8965-d4788a17fa48.png)
