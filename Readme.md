#MetaProgramming: prints at correct points... for free!
Basically a logger<br>
uses naming conventions, (the better your naming conventions the better it prints)<br><br>
"smallest #of_Lines_of_Code"<br>
modular... (quickly_ activated and deactivated)<br>
...printing at the correct points to give the best feedback.<br>


###How it will work:
(1) when there is a variable change... print out variables... deliminated by next variable name colon and space
(2) when there is one or more lines of code before the next variable change ... two "\n" is printed.
(3) again, when there is a variable change... print out variables... deliminated by next variable name colon and space


###example
####code:
<pre>
L code
1 int x = 0;
2 int y = 1;
3
4 x = y + y;
5 y = x + y;
6
</pre>
some will say ... this is just a debugger. They are correct.<br> but it is really light weight.<br> and works for my console.
####output
<p style = "padding-left: 25%">"line "code""</p>
<pre>
"1-2 "x: 0 y: 1""

"3-4 "x: 2 y: 3""	
</pre>
