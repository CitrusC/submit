#Submit
A command line tool to submit assignments. Made for SHIBAURA-IT Introduction to Programming course.

##install
$ https://github.com/CitrusC/submit.git
$ chmod a+x ~/submit/submit
$ echo 'set path=($path ~/submit)' >> ~/.cshrc
$ source ~/.cshrc

##usage
###upload assignment:
$ submit post <file>
(filename should be <assignment type><week number>-<question number>.c)

###check status:
$ submit status
