# HackerOne

* Using the “root” or “sa” accounts to connect your web application to your database server is one of the worst mistakes you can commit. best to use an account that only has simple read-write permissions to the specific database that sits behind your website, so in case your site becomes hacked through SQL injection, the scope of damage remains within the boundaries of that single database.    
* In MySQL, improve security by limiting access to the user account to specific IP address ranges instead of the “%” model, in order to prevent compromised accounts from being accessed from remote locations.  
* In MS SQL server, I would strongly advise you to use the Windows Authentication model, which would limit hackers’ access to the database  
× planning on using some of the advanced features of SQL Server, it is preferable to set up the windows service to use a limited account instead of the high privilege “Local System” account  

* Insert into field       hello<script>alert(1);</script>  
* <button onclick=window.open("http://www.google.com")>Some button</button>  
* SELECT password FROM admins WHERE username='' UNION SELECT 'random' AS PASSWORD#'    #' UNION SELECT 'random' AS PASSWORD#'  pw:randowm  
* add ' or random text after id or = parameter  
* 1.) b64d = lambda x: base64.decodestring(x.replace('~', '=').replace('!', '/').replace('-', '+'))   
  2.) ValueError: Input strings must be a multiple of 16 in length  
  PadBuster tool  

