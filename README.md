# Small_e_RSA
There is a special case in RSA, where if the value of the exponent is too little, the value of n becomes redundant

The decrypted message can simply be extracted by calculating c^(1/e) where n has been redacted for privacy

I wrote a script to help us do that easily

Read this to get some more info about it: 
https://www.johndcook.com/blog/2019/03/06/rsa-exponent-3/
