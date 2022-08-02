# farida-ashour


## Test Design

## Bug Reporting


### Bug #1

- Title: When adding a new exchange rate, a future date can be added

- Steps to Reproduce:
  - Open Monefy mobile application
  - Navigate to the side menu
  - Click on "Currencies"
  - Select one from the "others" currencies
  - Click on the add button 
  - Select a future date 
  - Click on the tick icon

- Expected Results:
App should reject future dates
- Actual Results:
App accepts future dates
- Affected Devices:
IOS
- Network:
4G
- Severity:
Low
- Priority:
Low
- Impact:
Low, impact on reliability
- Attachments
<img src="https://user-images.githubusercontent.com/46287387/182482118-64dc684c-88e2-4362-808d-0a04f2a9899a.jpg" height="600" width="300" >


### Bug #2

- Title: When adding a new exchange rate, the decimal places selected does not affect the number

- Steps to Reproduce:
  - Open Monefy mobile application
  - Navigate to the side menu
  - Click on "Currencies"
  - Select one from the "others" currencies
  - Select one of the decimal places
  - Click on the add button 
  - Enter a decimal number in "Exchange Rate" field
  - Click on the tick icon

- Expected Results:
App should approximate the number based on the selected decimal places
- Actual Results:
App does not approximate the value and display the actual result
- Affected Devices:
IOS
- Network:
4G
- Severity:
Medium
- Priority:
Medium
- Impact:
Low, impact on functionality 
- Attachments
<img src="https://user-images.githubusercontent.com/46287387/182485900-244bb028-f188-4a82-b022-76dc0c80fda6.jpg" height="600" width="300" >
<img src="https://user-images.githubusercontent.com/46287387/182485965-938db03d-0d78-4dd8-b51a-f4efad9dad2c.jpg" height="600" width="300" >


### Bug #3

- Title: When using any operational char (+,-,*,/) while adding an expence/income, the operational char selected is not highlighted

- Steps to Reproduce:
  - Open Monefy mobile application
  - Click on '+' or '-' icon 
  - Add a value then click on any operational char

- Expected Results:
App should highlight the selected operational char
- Actual Results:
App does not highlight the selected operational char
- Affected Devices:
IOS
- Network:
4G
- Severity:
Low
- Priority:
Low
- Impact:
Medium, impact on UX
- Attachments
<img src="https://user-images.githubusercontent.com/46287387/182489065-9d13ca57-b3e9-4e58-9c3a-3291e0c0e491.jpg" height="600" width="300" >



### Bug #4

- Title: No search bar is found for the currencies list

- Steps to Reproduce:
  - Open Monefy mobile application
  - Navigate to the side menu
  - Click on "Currencies"

- Expected Results:
App should display a search bar on the currencies list
- Actual Results:
App does not display a search bar on the currencies list
- Affected Devices:
IOS
- Network:
4G
- Severity:
Low
- Priority:
Low
- Impact:
Medium, impact on UX and ease of use 
- Attachments
<img src="https://user-images.githubusercontent.com/46287387/182490144-9a4e4e3d-f8eb-4ae9-b3cb-6740ffe210c1.jpg" height="600" width="300" >

### Bug #5

- Title: When adding a new account, the icons displayed are not descriptive and don’t show what does each icon represent.

- Steps to Reproduce:
  - Open Monefy mobile application
  - Navigate to the side menu
  - Click on "Accounts"
  - Click on the add icon

- Expected Results:
App should display all icons with a description of what each of them represent
- Actual Results:
App displays on the icon without any descriptions
- Affected Devices:
IOS
- Network:
4G
- Severity:
Low
- Priority:
High
- Impact:
Medium, impact on ease of use 
- Attachments
<img src="https://user-images.githubusercontent.com/46287387/182491388-4495cf8b-faae-42ff-93a9-f3744a8deb24.jpg" height="600" width="300" >

### Bug #6

- Title: When adding a category for an expense/income, it always displays "add category" without specifying if it's adding an expense or an income.

- Steps to Reproduce:
  - Open Monefy mobile application
  - Navigate to the side menu
  - Click on "Categories"
  - Click on the add icon 

- Expected Results:
App should display the category that is being created, either expense or income.
- Actual Results:
App displays "New Catgory" as a title without specifying which category.
- Affected Devices:
IOS
- Network:
4G
- Severity:
Low
- Priority:
Low
- Impact:
Low, impact on UX
- Attachments
<img src="https://user-images.githubusercontent.com/46287387/182492816-876f31f8-786f-4968-8bd6-e5e7540603f8.jpg" height="600" width="300" >

### Bug #7

- Title: App is not compitable with landscape view
- Steps to Reproduce:
  - Open Monefy mobile application
  - Change the device's orientation from portrait to landscape

- Expected Results:
App should be compitable with portrait and landscape views
- Actual Results:
App is not compitable with landscape view
- Affected Devices:
IOS
- Network:
4G
- Severity:
Low
- Priority:
Low
- Impact:
Medium, impact on compitability
