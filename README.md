![Logo](admin/wolf_logo.png)
# ioBroker.wolf

## Einsatzbereiche: Heizung / Solar / Wohnraumlüftung
der Adapter kann über das ISM8i maximal 4  von den nachfolgenden Heizgeräten auswerten:
  * Gasbrennwertgerät: CGB-2 (beinhaltet: CGW-2, CGS-2, CSZ-2), MGK-2 Öl
  * Brennwertkessel:   TOB 
  * Split-Wärmepumpe:  BWL-1-S 
  Es ist immer ein System-Bedienmodul BM-2 erforderlich. 
  Weiterhin können zusätzliche Komponenten, wie Mischermodul MM, Kaskadenmodul KM, Solarmodul SM1 oder SM2, im eBusSystem vorhanden sein. 
  
  
  Maximale Anzahl der einzelnen Module: 
  * max. 4 Heizgeräte hg(1)-hg(4)  (wobei ein BWL-1-S als hg0 angelegt wird)
  * max. 3 Mischer mm(1)- mm(3)
  * max. 4 Bediengeräte (BM-2) bm(1) -bm(4)
  * max. 1 Kaskadenmodul km(1) 
  * max. 1 Solarmodul (SM1 oder SM2) sm(1) 
  Ein Wohnraumlüftungsgerät der Baureihe CWL Excellent kann mit dem ISM8i ebenfalls ausgewertet und bedient werden. 


## Changelog
### 0.9.2 [2016.12.19]
* (smiling_Jack) Bugfix Type 5.001 Scaling 

### 0.9.1 [2016.12.19]
* (smiling_Jack) Add Bool option
* (smiling_Jack) Add Bar option
* (smiling_Jack) Bugfix Type 5.001 Scaling 

### 0.1.0 [2015.12.01]
* (smiling_Jack) Add writing to ism8

### 0.0.9 [2015.11.06]
* (smiling_Jack) Bugfix
* (smiling_Jack) Add test output


### 0.0.8 [2015.11.02]
* (smiling_Jack) Bugfix io-package

### 0.0.7 [2015.11.02]
* (smiling_Jack) new object management
* (smiling_Jack) Bugfixes

### 0.0.6 [2015.10.20]
* (smiling_Jack) Bugfix parsing

### 0.0.5 [2015.10.16]
* (smiling_Jack) Add support for multiple data
* (smiling_Jack) Add debug output 
* (smiling_Jack) Bugfixes


### 0.0.4 [2015.10.15]
* (smiling_Jack) Bugfix on parse error
* (smiling_Jack) Add DPT_HVACContrMode
* (smiling_Jack) Add DPT_HVACMode

### 0.0.3 [2015.10.14]
* (smiling_Jack) add CWL
* (smiling_Jack) remove ISM8 ip

### 0.0.2 [2015.10.12]
* (smiling_Jack) add BWL-1-S
* (smiling_Jack) update readme

### 0.0.1 [2015.10.08]
* (smiling_Jack) first release






# License

The MIT License (MIT)

Copyright (c) 2015 smiling_Jack

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.