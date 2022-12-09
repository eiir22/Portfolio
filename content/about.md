---
Title: About
Description: About my page
---

Om min sida
==================

## Layout
Först körs normalize.css för att skapa en layout som funkar för de allra flesta webbläsare. Sedan har jag försökt skapa ett lugnt och stilrent tema, detta har jag gjort genom att bland annat centrera samt begränsa main till en maxbredd på 1200px. Utöver det så har jag lagt till padding, margins och min-height till olika element för att få mer whitespace och bättre vertikal rytm. 

## SASS
För att få en lättbegriplig kod så skapade jag variabler med scss som innehöll HEX koderna till de färger jag kommer använda. Utöver det så skrevs alla {style} element i scss (som sedan omvandlades till css med ett custom kommando "npm run style").

## Typografi
Till skillnad från min logga så har all annan text en rak stil för att vara lättläst. Eftersom jag hade satt .main till en maxbredd på 1200px med en auto margin så fick jag problem med responsiviteten. För att lösa detta så gjorde jag textens storlek till 100% vid den mobila breakpointen. Dock så har code elementen fortfarande en horisontell scrollbar.