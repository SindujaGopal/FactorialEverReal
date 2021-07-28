
Defect summary report contains issues identified in the site (Defect Summary Report.xls)
It contains defect description, actual value present and suggested new ways.

# Instruction to run cypress project

Requirement: Cypress (Either direct download or with commands)

Import everreal folder in cypress
Click on 'everreal.js' in 'EverReal ExecutionFile' folder
Chrome would start with execution status displayed in it
After the execution screenshots will be saved in everreal\cypress\screenshots

#Execution status

Below steps would run in Cypress execution:
1. Open factorial page:
	Opens factorial page in browser and checks for page header, textbox name, calculator icon and calculate button name.
	Test status : Pass

2. Check page title:
	Checks factorial page title.
	Test status: Fail ; Expected: Factorial

3. Enter valid number and click calculate:
	Enter a valid integer and clicks on Calculate button
	Test status: Pass

4. Check result displayed for valid entry:
	Checks the result for above entry 
	Test status: Fail ; Expected: The factorial is:<Output>

5. Enter alphabet and click calculate:
	Enter alphabets and click on calculate button
	Test status: Pass

6. Enter special characters and click calculate:
	Enter special characters and click on calculate button
	Test status: Pass

7. Enter decimal and click calculate:
	Enter decimal number and click on calculate button
	Test status: Pass

8. Check Terms and Conditions navigation link:
	Check href values for Terms and conditions
	Test status: Fail ; Expected: /terms

9. Click Terms and Conditions and check navigation:
	Clicks on terms and conditions link and checks for navigation and page title
	Test status: Fail ; Expected: '/terms' navigation and 'Terms and Conditions' title

10. Check Privacy navigation link:
	Check href values for Privacy
	Test status: Fail ; Expected: /privacy

11. Click Privacy and check navigation:
	Clicks on Privacy link and checks for navigation and page title
	Test status: Fail ; Expected: '/privacy' navigation and 'Privacy' title

12. Check copyright section:
	Check the content of copyright section
	Test status: Pass

13. Click EverReal in copyright section:
	Clicks on EverReal link in copyright section and checks for navigation
	Test Status: Pass
