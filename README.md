# OTP-Generator
One Time Password (OTP) and Password Creator bot in python

Open VS code
open Terminal and type this code 
<pre> $pip install random2</pre>
Then install random in code
Type this code
<pre>
# import library
import math, random

# function to generate OTP
def generateOTP() :

	# Declare a digits variable
	# which stores all digits
	digits = "0123456789"
	OTP = ""

# length of password can be changed
# by changing value in range
	for i in range(4) :
		OTP += digits[math.floor(random.random() * 10)]

	return OTP

# Driver code
if __name__ == "__main__" :
	
	print("Your One Time Password is:", generateOTP())

</pre>
Then copy this code -

![code](https://user-images.githubusercontent.com/90886082/218302252-20080cce-1b5d-436c-a47a-efe41e0b0366.png)

# open Terminal

![command 2](https://user-images.githubusercontent.com/90886082/218302257-d05a2150-85dc-4983-af12-9fc98873a254.png)

# Run command to generate OTP

![terminal](https://user-images.githubusercontent.com/90886082/218302259-9c717c87-443b-46b1-aabd-e335cf4293e1.png)
