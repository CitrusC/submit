#Submit
A command line tool to submit assignments. Made for SHIBAURA-IT Introduction to Programming course.

##Install
`$ chmod a+x ~/submit/submit`
`$ echo 'set path=($path ~/submit)' >> ~/.cshrc`
`$ source ~/.cshrc`

##Usage
###Upload assignment:
`$ submit post <file>`  

Filename should be  `<kihon or hatten><week number>-<question number>.c`

Example:  
`$ submit post kihon1-2.c`
###Check status:
`$ submit status`
