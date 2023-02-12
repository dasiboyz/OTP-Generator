# OTP-Generator
One Time Password (OTP) and Password Creator bot in python

Open VS code
open Terminal and type this code 
<pre> $pip install random2</pre>
Then install random in code
Type this code
<pre>import random
<span>import string</span>
<span>def rand_pass(size):</span>
<span>    generate_pass=''.join([random.choice(string.ascii_uppercase +
                                        string.ascii_lowercase +
                                        string.digits)
                                        for n in range(size)])

return generate_pass
                                               
</pre>

Then copy this code -

![code](https://user-images.githubusercontent.com/90886082/218302252-20080cce-1b5d-436c-a47a-efe41e0b0366.png)

![command 2](https://user-images.githubusercontent.com/90886082/218302257-d05a2150-85dc-4983-af12-9fc98873a254.png)

![terminal](https://user-images.githubusercontent.com/90886082/218302259-9c717c87-443b-46b1-aabd-e335cf4293e1.png)
