This Python program checks whether the details entered by a user are valid before approving registration. It is written using only basic Python concepts and focuses on understanding string handling and conditional logic.

The program asks the user to enter four details: student ID, email ID, password, and referral code. 

What the Program Checks 

Student ID:

Should follow a fixed pattern used by the department

Must begin with CSE

Should include a hyphen after CSE

The remaining characters should be numbers

Email ID:

Should look like a proper email address

Must contain @ and .

Should not start or end with @

Must be a university email ending with .edu

Password:

Should be 8 characters or more

The first character should be capital

At least one number must be present

Referral Code:

Should begin with a specific keyword

Must include numbers in between

Should end with a special character

Validation Flow

Because my register number ends with an even digit, the program starts by checking the password first. After that, the remaining details are validated one by one. If any check fails, the process stops and the input is rejected. or else the input is approved 
