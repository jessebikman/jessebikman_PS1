# jessebikman_PS1
This is the PS1 command that I run in any BASH environment I claim ownership of:

`export PS1='\n[\d \t]\[\e]0;\w\a\]\[\e[32m\]\u@\H: \[\e[33m\]\w\[\e[0m\]\n\$ '`

Here's how it looks in my local environment:

>Last login: Fri Aug  5 20:59:15 on ttys000
>
>[Sun Aug 07 16:22:38]jessebikman@Jesses-MacBook.local: ~
>$

I'm a big fan of this PS1 because initially, it tells me when I last logged in. 
Then it gives me a nice timestamp that is non-ambiguous across AM/PM, and non-ambiguous between folks that put the month first in a date, and folks that put the day first in a date. 
It also tells me which user is logged in, and what environment I am running code in - be it my local machine, or a remote computing environment. 

I hope you find this useful!
