# passwordValidation

The following is my attempt at an assignmet written in html text/javascript code.

# Task: Password Validation

We are creating a login module for our top secret program. We are asking you to create a login validator
for this system. The login validator will ask the user to create a password. The following are required:
• The password must start with a letter and can be eight or more characters long. The
other characters can be any combination of letters and numbers. But there must be at least one number
in the user name
• Once the user has entered their password, then we need to verify that it is valid. If it is,
then we will display the message “Your password XXXXXXX is accepted.” In the message there will be
the same number of X’s as there are characters in the accepted password.
• If the password fails, then the user will receive a message that says “Password invalid –
it is not long enough” If less than 8 characters, “Password invalid – it does not start with a letter” if it
does not start with a letter, and finally “Password invalid – does not contain a number” if it is
missing a number.
HINT: Letters and numbers appear consecutively in ASCII and Unicode tables. This mean that letters go
a,b,c,d,… and you could see if the letter was b or c by using relational operators (check if the value is >a
and <d).
