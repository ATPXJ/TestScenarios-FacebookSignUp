# Facebook Sign Up

## Description
This set of test scenarios aims to analyze the functionality of the Sign Up feature on Facebook's website. It is intended to serve as a preliminary planning tool before conducting actual testing. The content of these test scenarios does not involve real testing and serves as an exercise derived from my learning journey. The primary objective is to practice thinking critically and analyzing user actions that may impact the system.
- Password rules: Enter a combination of at least six numbers, letters, and punctuation marks (such as ! and &)
  1. Six digits
  2. Includes Numbers
  3. Includes Letters
  4. Includes special characters

## Valid Scenarios
- Validate Sign Up with valid phone number.
- Validate Sign Up with valid email number.
- Validate Sign Up with valid Thai First name & Surname.
- Validate Sign Up with valid English First name & Surname.
- Validate Sign Up with valid Chinese First name & Surname.
- Validate providing a mobile number with and without country code. (E.g.: 0812345678 & +66812345678)
- Validate providing a mobile number in Thai digits. (E.g.: ๐๘๑๒๓๔๕๖๗๘)
- Validate sign up with valid age in the range of 13 to 18 years old.
- Validate sign up with valid age in the range of 18 to 120 years old.
- Validate providing different values for Gender.

## Invalid Scenarios
- Validate leaving First Name field empty.
- Validate leaving Surname field empty.
- Validate leaving Mobile or Email field empty.
- Validate leaving password field empty.
- Validate leaving gender field empty.
- Verify providing numbers or special characters in First Name.
- Verify providing numbers or special characters in Surname.
- Verify providing very short First Name is "G".
- Verify providing very short Surname is "G".
- Verify providing very long First Name (more than 50 characters).
- Verify providing very long Surname (more than 50 characters).
- Verify providing a short mobile number "1234".
- Verify providing a long mobile number (more than 14 digits).
- Verify providing a space in mobile number field.
- Verify Copy/Paste mobile number from another website or application.
- Verify adding an email with wrong format "abcdie$".
- Verify adding an email with a mistake in the format "abvdec@gliam.com".
- Validate a password with less than 6 digits (e.g., A28#G).
- Validate a password without letters (e.g., 1234!@#).
- Validate a password without numbers (e.g., ABCD!@#).
- Validate a password without special characters (e.g., ATPGF1S).
- Validate providing a date of birth less than 13.
- Validate providing a date of birth more than 120.
