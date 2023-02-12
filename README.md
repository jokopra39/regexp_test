# regexp_test
for learning regular expression

(?= [0-9]) 		      == only single digit<br />
/(0|[1-9][0-9])/  	== get number<br />
p=(\d+) 		        == get digit after "p=" <br />
/ (\d+)/  		      == only digit<br />
/[^\d+]*/ 		      == get only string<br />
[^|]*$  		        == get last in word<br />
/[^\d+]*/ 		      == get all char except digit<br />
/(.+?):/  		      == get string with ":"<br />
/[^:]*/ 		        == get char after and before ":"<br />
