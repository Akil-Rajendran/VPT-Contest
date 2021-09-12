# VPT-Contest
NLP translation for VPT Contest.
We created a function 'openfile' that reads the file for translation from the Google Drive.
Then cleaning is done on the Bracket data and some unwanted data using 'clean' function.
The data is then fed into translation model and the output is stored in a list.
The list is then compared with the given English text for BLEU Score calculation.

BLEU Score for our translation : 6.433
