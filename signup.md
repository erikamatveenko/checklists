#### Sign Up checklist:
__*Smoke test:*__  
Fill in all fields with correct data

__*Critical path test:*__  
Correct data:
- First name, Last name:
	- First letter is capital
	- First letter is lowercase
	- With valid word count
	- With valid special characters
	- With spaces before and after the name
	- Latin
	- Cyrillic
- E-mail:
	- Latin
	- Cyrillic
- Mobile number:
	- With + at the beginning
	- Without + at the beginning
	- With country code
	- Without country code
	- With special characters and spaces
- Password:
	- With capital letters
	- With numbers
	- With special characters
	- With spaces
	- Latin
	- Cyrillic
- Birthday:
	- Valid date
- Gender:
	- Custom:
		- Empty field «Gender»
		- «Gender» with a valid word count
		- Latin
		- Cyrillic

Incorrect data:
- First name:
	- Invalid length
	- With numbers
	- With letters of different alphabets
	- With invalid special characters
	- With an invalid number of capital letters
	- With an invalid word count
	- The first character is a valid special character
	- Consists of spaces
	- Empty field
- Last name:
	- Invalid length
	- With numbers
	- With letters of different alphabets
	- With invalid special characters
	- With an invalid number of capital letters
	- With an invalid word count
	- The first character is a valid special character
	- Consists of spaces
	- Empty field
- E-mail:
	- Registered
	- Nonexistent
	- Invalid format
	- Mismatched E-mail
	- Empty field
	- Empty retry field E-mail
- Mobile number:
	- Registered
	- Nonexistent
- Password:
	- Invalid length
	- Of the same symbols
- Birthday:
	- Date is greater than current
	- Age is less than the minimum
- Gender:
	- Not selected
	- Custom:
		- No pronoun field selected
		- «Gender»:
			- With invalid special characters
			- With numbers
			- Consists of spaces
			- With an invalid word count
- Links:
	- Terms
	- Data Policy
	- Cookies Policy

__*Extended test:*__  
HTML characters code in all text fields  
XSS attacks in all text fields  
SQL injections in all text fields  
HTML tags in all text fields  
Copy, cut and paste with keys in all text fields  
Copy, cut and paste via the context menu in all text fields  
Tab navigation  
Pressing buttons with Enter  
Entering birthday and year from the keyboard  
