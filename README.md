# regexp_test
for learning regular expression

(?= [0-9]) 		    == only single digit
/(0|[1-9][0-9])/  	== get number
p=(\d+) 		    == get digit after "p="
/ (\d+)/  		    == only digit
/[^\d+]*/ 		    == get only string
[^|]*$  		    == get last in word
/[^\d+]*/ 		    == get all char except digit
/(.+?):/  		    == get string with ":"
/[^:]*/ 		    == get char after and before ":"