## Generate-6-digit-random-secure-OTP
## Sample code to check the 6 digit randoms
```sh
import secrets

#Getting systemRandom class instance out of secrets module
secretsGenerator = secrets.SystemRandom()

print("Generating 6 digit random OTP")
otp = secretsGenerator.randrange(100000, 999999)

print("Secure random OTP is ", otp)
```
##  Expected output
Random integer from 0 to 9
Random integer:  5

Random integer from 10 to 100
Random integer:  89
