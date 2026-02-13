## PASSWORD STRENGTH CHECKER 

A web-based Password Strength Checker built using HTML, CSS, and JavaScript.

This project validates password strength based on modern security rules and provides a randomly generated strong password suggestion if the entered password is weak.

---

## Features

- Minimum 10 character requirement
- Requires at least:
  - One uppercase letter
  - One lowercase letter
  - One number
  - One special character
- Detects sequences longer than 3 characters (e.g., 1234, abcd)
- Displays specific error messages
- Generates a different strong password suggestion each time
- Prevents page reload on submission
- Simple and clean user interface

## Technologies Used
- HTML
- CSS
- JavaScript (Vanilla JS)

## How It Works

The application validates:

- Password length
- Character variety
- Sequential patterns
- Structural weaknesses

If validation fails:
- The user sees the reason.
- A new strong password example is generated automatically.

If all conditions pass:
- The password is marked as strong.

## Shows Example Passwords

Example (changes every time):

## Future Improvements

- Real-time validation while typing
- Password strength meter
- Copy-to-clipboard button
- Show/Hide password toggle
- Cryptographically secure password generator

---

## License

This project is for educational and practice purposes.
