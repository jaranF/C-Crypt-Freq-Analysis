# C-Crypt-Freq-Analysis
## Description
Performs frequency analysis on an CIPHERTEXT (assumes English characters A-Z). Works from the command line like your usual tool accessible from BASH / .CSH / Terminal etc.

Receives input (as the first argument) of the CIPHERTEXT file to perform analysis on. Outputs statistics for frequency of each letter's usage.

Why no unit tests? Appologies, but I still a learner of C (in fact Im only 60% my beginners book) on it so - time allowing - I will get there eventually
## Todo (short-term)
Also can recognise a second parameter (searches for the switch "`-o`") which I hope to be able to trigger the re-ordering of the frequency analysis output so it displays the most frequently occurred letters from the top in descending order. Presently does not work because I need to migrate the code away from using arrays to something (probably a struct...which I am just learning about) that lends itself better to sorting.
