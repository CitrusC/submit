#Submit
A command line tool to submit assignments. For SHIBAURA-IT Introduction to Programming course.

##Install
`$ wget https://github.com/CitrusC/submit/archive/v1.0.tar.gz`  
`$ tar -zxvf v1.0`  
`$ chmod a+x ./submit-1.0/submit`  
`$ echo 'set path=($path ~/submit-1.0)' >> ~/.cshrc`  
`$ source ~/.cshrc`
  
If not download to the ~/ directory, change `($path ~/submit-1.0)` to the right path.  
##Usage
###Upload assignment:
`$ submit post <file>`  

Filename should be  
`<kihon or hatten><week number>-<question number>.c`

Example:  
`$ submit post kihon1-2.c`
###Check status:
`$ submit status`
