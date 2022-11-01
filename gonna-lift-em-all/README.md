# Gonna-Lift-Em-All

This is the first ctf question I made. The knowledge used was all learned in university.

By reading the python program we can get three equations:$c1=g·y\,mod\,p \ ; \ c2=m·s\,mod\,p \ ; \ s = h^y \, mod \, p$
From the output file: “data.txt”,  we’ve already known $p,g,h,c1,c2$. 

To obtain m, or flag, we can write python programs for the following calculations:$y=g^{-1}·c1 \,mod\,p \ ; \ s = h^y \, mod \, p \ ; \ m = c2·s^{-1} \,mod\,p$
Don't forget to convert m to hexadecimal.