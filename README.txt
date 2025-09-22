Lines 43
hashes the original code
Lines 45 - 47
Is the ecryption method used in the code to keep the program safe.
Line 63 - 64
Is the code's way of decrypting the code provided. 
line 66
hashes the decrypted content
line 69-73
Verifies the integrity of the decripted code

This program upolds the three factors of the CIA triad, 
with confidentiallity the only person to know what the code changed to is only the user so nobody else can steal it,
with integrity the code does not get sent out to other systems meaning the code has less places to potentially fail and causing the code to leak,
with availibility the code is availibe to anyone who downloads it so no one is left out of using the code.

The code's entropy is from the hash table process and from the key used by defult or given by the user if they have a special key only they know about. 