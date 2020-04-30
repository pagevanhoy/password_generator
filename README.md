# password_generator
GIVEN I need a new, secure password
WHEN I click the button to generate a password
THEN I am presented with a series of prompts for password criteria
WHEN prompted for password criteria
    
THEN I select which criteria to include in the password
WHEN prompted for the length of the password
THEN I choose a length of at least 8 characters and no more than 128 characters
    code in greater than or equal to 8 and less than or equal to 128
WHEN prompted for character types to include in the password
THEN I choose lowercase, uppercase, numeric, and/or special characters
WHEN I answer each prompt
THEN my input should be validated and at least one character type should be selected
WHEN all prompts are answered
THEN a password is generated that matches the selected criteria
WHEN the password is generated
THEN the password is either displayed in an alert or written to the page


Pseudocode:
Given New Password needed
When I click the button to generate password
    prompt:
Choose a length of at least 8 characters and no more than 128 characters
        If user answer is less than 8 characters return: not enough characters
        If user answer is greater than 128 characters return:  too many characters
    prompt 2:
        Select character types for your password:
            Uppercase, Lowercase, numeric, special characters
Then generate a password based on their selection
