# Caeser Cipher

You will be writing a caeser cipher in ARM assembly.

# Steps You Should Follow
    Step 1:
        The first thing you should do is modify the case conversion program that Neil did in class.
        Instead of subtracting 32 from all numbers you want to add a constant number which we will call the key.
        Assume that all input will be lowercase. 
        So it'll look like this,
            k = 2;
            letter = 'a';
            newletter = k+letter;
        Above is pseudocode and ABOVE NOT ASSEMBLY CODE DO NOT COPY.
        Use bl puts the same way Neil did in class to show that everything is working correctly.
    Step 2:
        If the key + letter is bigger is 'z' then you have to subtract 26.
        If the key + letter is less than 'a' then you have to add 26.

# Extra credit  
    Get the key and plain-text from the commandline (10 points of extra credit)

        
        
    