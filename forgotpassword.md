#### Forgot Password checklist:
__*Smoke test:*__  
Enter the correct E-mail, send the code to E-mail, enter the correct code and password  
Enter the correct mobile number, send the code to the number, enter the correct code and password

__*Critical path test:*__  
Incorrect data:
- E-mail or Mobile number:
  - Nonexistent
  - Unregistered
  - Empty field
- Code:
	- Incorrect
	- Empty field
- Password:
  - Invalid length
  - Of the same symbols
  - Old password
  - Empty field 

Enter a number for which more than one account is registered

__*Extended test:*__  
Pressing buttons:
- «Cancel»
- «Not You?»
- «No longer have access to these?»:
  - «Enter Password to Log In»
- «I Cannot Access My Email»:
	- «Learn more about other ways to access your Facebook account»
	- «Done»
- «Didn't get a code?»
- Hide/show password
- Password Help  

HTML characters code in all text fields  
XSS attacks in all text fields  
SQL injections in all text fields  
HTML tags in all text fields  
Copy, cut and paste with keys in all text fields  
Copy, cut and paste via the context menu in all text fields  
Tab navigation  
Pressing buttons with Enter
