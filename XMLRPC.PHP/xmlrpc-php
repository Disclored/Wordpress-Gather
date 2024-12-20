1 - Check if the site has xmlrpc.php activated:

https://www.site.com/xmlrpc.php
(You should get "XML-RPC server accepts POST requests only"

2 - Intercept the request with burp suite
3 - Change the request to POST and add the following payload:

<methodCall>
<methodName>system.listMethods</methodName>
<params></params>
</methodCall>

