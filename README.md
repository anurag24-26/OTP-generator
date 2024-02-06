# One-Time Password (OTP) Generator Overview
This is a basic script for generating One-Time Passwords (OTPs) in JavaScript. It generates a random OTP of a specified length.

# Usage
Open the otp.js file.

Run the script using a JavaScript environment such as a browser console or Node.js.

# OTP Generation Logic
The OTP is generated using a simple loop that iterates over the specified length, appending a random digit (0-9) to the OTP string in each iteration.

```javascript
let otp = '';
const otpLength = 6;

for (let i = 1; i <= otpLength; i++) {
    otp += Math.floor(Math.random() * 10);
}

console.log(otp);
```
Feel free to customize the otp Length variable in the script to generate OTPs of different lengths.

# Acknowledgments
This script was created for educational purposes and can be used as a basic OTP generation example.

# Author
[Anurag Tripathi](https://www.instagram.com/thename_isanurag/)

GitHub:2005anurag2602
