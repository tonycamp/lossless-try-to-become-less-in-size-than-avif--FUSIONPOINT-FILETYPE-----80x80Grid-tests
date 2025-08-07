RELATIVE TABLE EXPLANATION
ITS THE SIMPLIEST THING

I HAVE VALUES OF 0 to 255 in a y row of a bitmap for luminess
I store in a table of 0 and 1 ocupping 32 bytes 256 bits witch are active for instances luminance of x = 10 and , y=1 its 34 i store the 1 on 34 place bits value of 32 bytes = 0 to 255 possibilites it gives like for instances in that row 150 diferent ones values.. i count them , Relate them to that value in num1 soo that 34 value for instances corresponds to just 12 value or soo much less and save the lumincance relative values for each byte of that row but before i save the 32 bytes tlbe of zeros and ones...
Moving on on height of bitmap i do this for every rows of y. 
Then i do the same for chromo radiance and chromoluminosity soo that the Y U V its all stored into no single bit loss ( i hope)..

The to reconstruct i will just need to regain those YUV values and RGB them out
Most likely high quality image lossless over less size than avif

After the dat compressed

