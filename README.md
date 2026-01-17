# Ransom_in_C_for_BBC_Micro
This is an implementation of the short adventure game Ransom (an example from GAC) written about 10 years ago in C on a BBC Master using Twin as an editor and Norcroft C as a compiler. 

I have just started refactoring this on an A5000 I got recently using !ZAP as an editor and Acornsoft C version 5. This process is basically a case of splitting the functions out into separate files to organise the code a bit better (being written originally on a Beeb using Twin it was not well organised) and also isolated any code that would need rewriting to work on other computers - it would be nice to get it running on a Tatung Einstein.

The actual game code is in the file 'gCode', the other files contain functions to load and save and deal with the counters etc.
