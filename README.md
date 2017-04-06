# api documentation for  [five (v0.8.0)](https://github.com/jackdcrawford/five)  [![npm package](https://img.shields.io/npm/v/npmdoc-five.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-five) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-five.svg)](https://travis-ci.org/npmdoc/node-npmdoc-five)
#### Gives you five

[![NPM](https://nodei.co/npm/five.png?downloads=true)](https://www.npmjs.com/package/five)

[![apidoc](https://npmdoc.github.io/node-npmdoc-five/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-five_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-five/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-five/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-five/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jack Crawford",
        "email": "jackcrawford19@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/jackdcrawford/five/issues"
    },
    "dependencies": {},
    "description": "Gives you five",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "e7bde97d21265c70c145e1b09f879e41d92d9c75",
        "tarball": "https://registry.npmjs.org/five/-/five-0.8.0.tgz"
    },
    "gitHead": "16335e38b69a09ed0da003040c99cd3530776321",
    "homepage": "https://github.com/jackdcrawford/five",
    "keywords": [
        "five"
    ],
    "license": "MIT",
    "main": "five.js",
    "maintainers": [
        {
            "name": "jackdcrawford",
            "email": "jackcrawford19@gmail.com"
        }
    ],
    "name": "five",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jackdcrawford/five.git"
    },
    "scripts": {
        "test": "node test && echo ✔"
    },
    "version": "0.8.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module five](#apidoc.module.five)
1.  [function <span class="apidocSignatureSpan">five.</span>arabic ()](#apidoc.element.five.arabic)
1.  [function <span class="apidocSignatureSpan">five.</span>azerbaijani ()](#apidoc.element.five.azerbaijani)
1.  [function <span class="apidocSignatureSpan">five.</span>basque ()](#apidoc.element.five.basque)
1.  [function <span class="apidocSignatureSpan">five.</span>binary ()](#apidoc.element.five.binary)
1.  [function <span class="apidocSignatureSpan">five.</span>bosnian ()](#apidoc.element.five.bosnian)
1.  [function <span class="apidocSignatureSpan">five.</span>bulgarian ()](#apidoc.element.five.bulgarian)
1.  [function <span class="apidocSignatureSpan">five.</span>catalan ()](#apidoc.element.five.catalan)
1.  [function <span class="apidocSignatureSpan">five.</span>chinese ()](#apidoc.element.five.chinese)
1.  [function <span class="apidocSignatureSpan">five.</span>choctaw ()](#apidoc.element.five.choctaw)
1.  [function <span class="apidocSignatureSpan">five.</span>croatian ()](#apidoc.element.five.croatian)
1.  [function <span class="apidocSignatureSpan">five.</span>czech ()](#apidoc.element.five.czech)
1.  [function <span class="apidocSignatureSpan">five.</span>dovah ()](#apidoc.element.five.dovah)
1.  [function <span class="apidocSignatureSpan">five.</span>downLow ()](#apidoc.element.five.downLow)
1.  [function <span class="apidocSignatureSpan">five.</span>dutch ()](#apidoc.element.five.dutch)
1.  [function <span class="apidocSignatureSpan">five.</span>elvish ()](#apidoc.element.five.elvish)
1.  [function <span class="apidocSignatureSpan">five.</span>english ()](#apidoc.element.five.english)
1.  [function <span class="apidocSignatureSpan">five.</span>fab ()](#apidoc.element.five.fab)
1.  [function <span class="apidocSignatureSpan">five.</span>finnish ()](#apidoc.element.five.finnish)
1.  [function <span class="apidocSignatureSpan">five.</span>french ()](#apidoc.element.five.french)
1.  [function <span class="apidocSignatureSpan">five.</span>german ()](#apidoc.element.five.german)
1.  [function <span class="apidocSignatureSpan">five.</span>hebrew ()](#apidoc.element.five.hebrew)
1.  [function <span class="apidocSignatureSpan">five.</span>hex ()](#apidoc.element.five.hex)
1.  [function <span class="apidocSignatureSpan">five.</span>hindi ()](#apidoc.element.five.hindi)
1.  [function <span class="apidocSignatureSpan">five.</span>indonesian ()](#apidoc.element.five.indonesian)
1.  [function <span class="apidocSignatureSpan">five.</span>irish ()](#apidoc.element.five.irish)
1.  [function <span class="apidocSignatureSpan">five.</span>italian ()](#apidoc.element.five.italian)
1.  [function <span class="apidocSignatureSpan">five.</span>japanese ()](#apidoc.element.five.japanese)
1.  [function <span class="apidocSignatureSpan">five.</span>kannada ()](#apidoc.element.five.kannada)
1.  [function <span class="apidocSignatureSpan">five.</span>klingon ()](#apidoc.element.five.klingon)
1.  [function <span class="apidocSignatureSpan">five.</span>korean ()](#apidoc.element.five.korean)
1.  [function <span class="apidocSignatureSpan">five.</span>latin ()](#apidoc.element.five.latin)
1.  [function <span class="apidocSignatureSpan">five.</span>loud ()](#apidoc.element.five.loud)
1.  [function <span class="apidocSignatureSpan">five.</span>map (array)](#apidoc.element.five.map)
1.  [function <span class="apidocSignatureSpan">five.</span>mongolian ()](#apidoc.element.five.mongolian)
1.  [function <span class="apidocSignatureSpan">five.</span>morseCode ()](#apidoc.element.five.morseCode)
1.  [function <span class="apidocSignatureSpan">five.</span>negative ()](#apidoc.element.five.negative)
1.  [function <span class="apidocSignatureSpan">five.</span>octal ()](#apidoc.element.five.octal)
1.  [function <span class="apidocSignatureSpan">five.</span>persian ()](#apidoc.element.five.persian)
1.  [function <span class="apidocSignatureSpan">five.</span>piglatin ()](#apidoc.element.five.piglatin)
1.  [function <span class="apidocSignatureSpan">five.</span>polish ()](#apidoc.element.five.polish)
1.  [function <span class="apidocSignatureSpan">five.</span>portuguese ()](#apidoc.element.five.portuguese)
1.  [function <span class="apidocSignatureSpan">five.</span>reduce (array)](#apidoc.element.five.reduce)
1.  [function <span class="apidocSignatureSpan">five.</span>roman ()](#apidoc.element.five.roman)
1.  [function <span class="apidocSignatureSpan">five.</span>romanian ()](#apidoc.element.five.romanian)
1.  [function <span class="apidocSignatureSpan">five.</span>russian ()](#apidoc.element.five.russian)
1.  [function <span class="apidocSignatureSpan">five.</span>slovenian ()](#apidoc.element.five.slovenian)
1.  [function <span class="apidocSignatureSpan">five.</span>smooth ()](#apidoc.element.five.smooth)
1.  [function <span class="apidocSignatureSpan">five.</span>spanish ()](#apidoc.element.five.spanish)
1.  [function <span class="apidocSignatureSpan">five.</span>swedish ()](#apidoc.element.five.swedish)
1.  [function <span class="apidocSignatureSpan">five.</span>tamil ()](#apidoc.element.five.tamil)
1.  [function <span class="apidocSignatureSpan">five.</span>telugu ()](#apidoc.element.five.telugu)
1.  [function <span class="apidocSignatureSpan">five.</span>thai ()](#apidoc.element.five.thai)
1.  [function <span class="apidocSignatureSpan">five.</span>tooSlow ()](#apidoc.element.five.tooSlow)
1.  [function <span class="apidocSignatureSpan">five.</span>upHigh ()](#apidoc.element.five.upHigh)



# <a name="apidoc.module.five"></a>[module five](#apidoc.module.five)

#### <a name="apidoc.element.five.arabic"></a>[function <span class="apidocSignatureSpan">five.</span>arabic ()](#apidoc.element.five.arabic)
- description and source-code
```javascript
arabic = function () { return 'خمسة'; }
```
- example usage
```shell
...
five.negative() // -5
five.loud() // FIVE
five.smooth() // S
'''

##### 5 goes multilingual
'''javascript
five.arabic() // خمسة
five.azerbaijani() // beş
five.basque() // bost
five.bosnian() // pet
five.bulgarian() // пет
five.catalan() // cinc
five.chinese() // 五
five.choctaw() // tahlapi
...
```

#### <a name="apidoc.element.five.azerbaijani"></a>[function <span class="apidocSignatureSpan">five.</span>azerbaijani ()](#apidoc.element.five.azerbaijani)
- description and source-code
```javascript
azerbaijani = function () { return 'beş'; }
```
- example usage
```shell
...
five.loud() // FIVE
five.smooth() // S
'''

##### 5 goes multilingual
'''javascript
five.arabic() // خمسة
five.azerbaijani() // beş
five.basque() // bost
five.bosnian() // pet
five.bulgarian() // пет
five.catalan() // cinc
five.chinese() // 五
five.choctaw() // tahlapi
five.croatian() // pet
...
```

#### <a name="apidoc.element.five.basque"></a>[function <span class="apidocSignatureSpan">five.</span>basque ()](#apidoc.element.five.basque)
- description and source-code
```javascript
basque = function () { return 'bost'; }
```
- example usage
```shell
...
five.smooth() // S
'''

##### 5 goes multilingual
'''javascript
five.arabic() // خمسة
five.azerbaijani() // beş
five.basque() // bost
five.bosnian() // pet
five.bulgarian() // пет
five.catalan() // cinc
five.chinese() // 五
five.choctaw() // tahlapi
five.croatian() // pet
five.czech() // pět
...
```

#### <a name="apidoc.element.five.binary"></a>[function <span class="apidocSignatureSpan">five.</span>binary ()](#apidoc.element.five.binary)
- description and source-code
```javascript
binary = function () { return '101'; }
```
- example usage
```shell
...
five.tamil() // ஐந்து
five.telugu() // ఐదు
five.thai() // ห้า
'''

##### Different radices
'''javascript
five.binary(); // 101
five.octal(); // 5
five.hex(); // 5
'''

##### Map and Reduce
'''javascript
five.map([1, 2, 3]); // [5, 5, 5]
...
```

#### <a name="apidoc.element.five.bosnian"></a>[function <span class="apidocSignatureSpan">five.</span>bosnian ()](#apidoc.element.five.bosnian)
- description and source-code
```javascript
bosnian = function () { return 'pet'; }
```
- example usage
```shell
...
'''

##### 5 goes multilingual
'''javascript
five.arabic() // خمسة
five.azerbaijani() // beş
five.basque() // bost
five.bosnian() // pet
five.bulgarian() // пет
five.catalan() // cinc
five.chinese() // 五
five.choctaw() // tahlapi
five.croatian() // pet
five.czech() // pět
five.dovah() // hen
...
```

#### <a name="apidoc.element.five.bulgarian"></a>[function <span class="apidocSignatureSpan">five.</span>bulgarian ()](#apidoc.element.five.bulgarian)
- description and source-code
```javascript
bulgarian = function () { return 'пет'; }
```
- example usage
```shell
...

##### 5 goes multilingual
'''javascript
five.arabic() // خمسة
five.azerbaijani() // beş
five.basque() // bost
five.bosnian() // pet
five.bulgarian() // пет
five.catalan() // cinc
five.chinese() // 五
five.choctaw() // tahlapi
five.croatian() // pet
five.czech() // pět
five.dovah() // hen
five.dutch() // vijf
...
```

#### <a name="apidoc.element.five.catalan"></a>[function <span class="apidocSignatureSpan">five.</span>catalan ()](#apidoc.element.five.catalan)
- description and source-code
```javascript
catalan = function () { return 'cinc'; }
```
- example usage
```shell
...
##### 5 goes multilingual
'''javascript
five.arabic() // خمسة
five.azerbaijani() // beş
five.basque() // bost
five.bosnian() // pet
five.bulgarian() // пет
five.catalan() // cinc
five.chinese() // 五
five.choctaw() // tahlapi
five.croatian() // pet
five.czech() // pět
five.dovah() // hen
five.dutch() // vijf
five.elvish() // lempe
...
```

#### <a name="apidoc.element.five.chinese"></a>[function <span class="apidocSignatureSpan">five.</span>chinese ()](#apidoc.element.five.chinese)
- description and source-code
```javascript
chinese = function () { return '五'; }
```
- example usage
```shell
...
'''javascript
five.arabic() // خمسة
five.azerbaijani() // beş
five.basque() // bost
five.bosnian() // pet
five.bulgarian() // пет
five.catalan() // cinc
five.chinese() // 五
five.choctaw() // tahlapi
five.croatian() // pet
five.czech() // pět
five.dovah() // hen
five.dutch() // vijf
five.elvish() // lempe
five.english() // Five
...
```

#### <a name="apidoc.element.five.choctaw"></a>[function <span class="apidocSignatureSpan">five.</span>choctaw ()](#apidoc.element.five.choctaw)
- description and source-code
```javascript
choctaw = function () { return 'tahlapi'; }
```
- example usage
```shell
...
five.arabic() // خمسة
five.azerbaijani() // beş
five.basque() // bost
five.bosnian() // pet
five.bulgarian() // пет
five.catalan() // cinc
five.chinese() // 五
five.choctaw() // tahlapi
five.croatian() // pet
five.czech() // pět
five.dovah() // hen
five.dutch() // vijf
five.elvish() // lempe
five.english() // Five
five.finnish() // viisi
...
```

#### <a name="apidoc.element.five.croatian"></a>[function <span class="apidocSignatureSpan">five.</span>croatian ()](#apidoc.element.five.croatian)
- description and source-code
```javascript
croatian = function () { return 'pet'; }
```
- example usage
```shell
...
five.azerbaijani() // beş
five.basque() // bost
five.bosnian() // pet
five.bulgarian() // пет
five.catalan() // cinc
five.chinese() // 五
five.choctaw() // tahlapi
five.croatian() // pet
five.czech() // pět
five.dovah() // hen
five.dutch() // vijf
five.elvish() // lempe
five.english() // Five
five.finnish() // viisi
five.french() // cinq
...
```

#### <a name="apidoc.element.five.czech"></a>[function <span class="apidocSignatureSpan">five.</span>czech ()](#apidoc.element.five.czech)
- description and source-code
```javascript
czech = function () { return 'pět'; }
```
- example usage
```shell
...
five.basque() // bost
five.bosnian() // pet
five.bulgarian() // пет
five.catalan() // cinc
five.chinese() // 五
five.choctaw() // tahlapi
five.croatian() // pet
five.czech() // pět
five.dovah() // hen
five.dutch() // vijf
five.elvish() // lempe
five.english() // Five
five.finnish() // viisi
five.french() // cinq
five.german() // fünf
...
```

#### <a name="apidoc.element.five.dovah"></a>[function <span class="apidocSignatureSpan">five.</span>dovah ()](#apidoc.element.five.dovah)
- description and source-code
```javascript
dovah = function () { return 'hen'; }
```
- example usage
```shell
...
five.bosnian() // pet
five.bulgarian() // пет
five.catalan() // cinc
five.chinese() // 五
five.choctaw() // tahlapi
five.croatian() // pet
five.czech() // pět
five.dovah() // hen
five.dutch() // vijf
five.elvish() // lempe
five.english() // Five
five.finnish() // viisi
five.french() // cinq
five.german() // fünf
five.hebrew() // חמש
...
```

#### <a name="apidoc.element.five.downLow"></a>[function <span class="apidocSignatureSpan">five.</span>downLow ()](#apidoc.element.five.downLow)
- description and source-code
```javascript
downLow = function () { return '₅'; }
```
- example usage
```shell
...
'''javascript
five() / five(); // 1
'''

##### Different sorts of 5
'''javascript
five.upHigh() // ⁵
five.downLow() // ₅
five.tooSlow() // 5, with a ~500 millisecond delay
five.roman() // V
five.morseCode() // di-di-di-di-dit
five.negative() // -5
five.loud() // FIVE
five.smooth() // S
'''
...
```

#### <a name="apidoc.element.five.dutch"></a>[function <span class="apidocSignatureSpan">five.</span>dutch ()](#apidoc.element.five.dutch)
- description and source-code
```javascript
dutch = function () { return 'vijf'; }
```
- example usage
```shell
...
five.bulgarian() // пет
five.catalan() // cinc
five.chinese() // 五
five.choctaw() // tahlapi
five.croatian() // pet
five.czech() // pět
five.dovah() // hen
five.dutch() // vijf
five.elvish() // lempe
five.english() // Five
five.finnish() // viisi
five.french() // cinq
five.german() // fünf
five.hebrew() // חמש
five.hindi() // पांच
...
```

#### <a name="apidoc.element.five.elvish"></a>[function <span class="apidocSignatureSpan">five.</span>elvish ()](#apidoc.element.five.elvish)
- description and source-code
```javascript
elvish = function () { return 'lempe'; }
```
- example usage
```shell
...
five.catalan() // cinc
five.chinese() // 五
five.choctaw() // tahlapi
five.croatian() // pet
five.czech() // pět
five.dovah() // hen
five.dutch() // vijf
five.elvish() // lempe
five.english() // Five
five.finnish() // viisi
five.french() // cinq
five.german() // fünf
five.hebrew() // חמש
five.hindi() // पांच
five.indonesian() // lima
...
```

#### <a name="apidoc.element.five.english"></a>[function <span class="apidocSignatureSpan">five.</span>english ()](#apidoc.element.five.english)
- description and source-code
```javascript
english = function () { return 'five'; }
```
- example usage
```shell
...
five.chinese() // 五
five.choctaw() // tahlapi
five.croatian() // pet
five.czech() // pět
five.dovah() // hen
five.dutch() // vijf
five.elvish() // lempe
five.english() // Five
five.finnish() // viisi
five.french() // cinq
five.german() // fünf
five.hebrew() // חמש
five.hindi() // पांच
five.indonesian() // lima
five.irish() // cúig
...
```

#### <a name="apidoc.element.five.fab"></a>[function <span class="apidocSignatureSpan">five.</span>fab ()](#apidoc.element.five.fab)
- description and source-code
```javascript
fab = function () {
  return ['Juwan Howard','Ray Jackson','Jimmy King','Jalen Rose','Chris Webber'];
}
```
- example usage
```shell
...
'''javascript
five.map([1, 2, 3]); // [5, 5, 5]
five.reduce([1, 2, 3]); // 5
'''

##### Novelty
'''javascript
five.fab(); // ['Juwan Howard','Ray Jackson','Jimmy King','Jalen Rose','Chris Webber']
'''

### Development
##### The code
All of the logic & heavy lifting is achieved in one self-contained file:
'''
./five.js
...
```

#### <a name="apidoc.element.five.finnish"></a>[function <span class="apidocSignatureSpan">five.</span>finnish ()](#apidoc.element.five.finnish)
- description and source-code
```javascript
finnish = function () { return 'viisi'; }
```
- example usage
```shell
...
five.choctaw() // tahlapi
five.croatian() // pet
five.czech() // pět
five.dovah() // hen
five.dutch() // vijf
five.elvish() // lempe
five.english() // Five
five.finnish() // viisi
five.french() // cinq
five.german() // fünf
five.hebrew() // חמש
five.hindi() // पांच
five.indonesian() // lima
five.irish() // cúig
five.italian() // cinque
...
```

#### <a name="apidoc.element.five.french"></a>[function <span class="apidocSignatureSpan">five.</span>french ()](#apidoc.element.five.french)
- description and source-code
```javascript
french = function () { return 'cinq'; }
```
- example usage
```shell
...
five.croatian() // pet
five.czech() // pět
five.dovah() // hen
five.dutch() // vijf
five.elvish() // lempe
five.english() // Five
five.finnish() // viisi
five.french() // cinq
five.german() // fünf
five.hebrew() // חמש
five.hindi() // पांच
five.indonesian() // lima
five.irish() // cúig
five.italian() // cinque
five.japanese() // 五
...
```

#### <a name="apidoc.element.five.german"></a>[function <span class="apidocSignatureSpan">five.</span>german ()](#apidoc.element.five.german)
- description and source-code
```javascript
german = function () { return 'fünf'; }
```
- example usage
```shell
...
five.czech() // pět
five.dovah() // hen
five.dutch() // vijf
five.elvish() // lempe
five.english() // Five
five.finnish() // viisi
five.french() // cinq
five.german() // fünf
five.hebrew() // חמש
five.hindi() // पांच
five.indonesian() // lima
five.irish() // cúig
five.italian() // cinque
five.japanese() // 五
five.kannada() // ಐದು
...
```

#### <a name="apidoc.element.five.hebrew"></a>[function <span class="apidocSignatureSpan">five.</span>hebrew ()](#apidoc.element.five.hebrew)
- description and source-code
```javascript
hebrew = function () { return 'חמש'; }
```
- example usage
```shell
...
five.dovah() // hen
five.dutch() // vijf
five.elvish() // lempe
five.english() // Five
five.finnish() // viisi
five.french() // cinq
five.german() // fünf
five.hebrew() // חמש
five.hindi() // पांच
five.indonesian() // lima
five.irish() // cúig
five.italian() // cinque
five.japanese() // 五
five.kannada() // ಐದು
five.klingon() // vagh
...
```

#### <a name="apidoc.element.five.hex"></a>[function <span class="apidocSignatureSpan">five.</span>hex ()](#apidoc.element.five.hex)
- description and source-code
```javascript
hex = function () { return '5'; }
```
- example usage
```shell
...
five.thai() // ห้า
'''

##### Different radices
'''javascript
five.binary(); // 101
five.octal(); // 5
five.hex(); // 5
'''

##### Map and Reduce
'''javascript
five.map([1, 2, 3]); // [5, 5, 5]
five.reduce([1, 2, 3]); // 5
'''
...
```

#### <a name="apidoc.element.five.hindi"></a>[function <span class="apidocSignatureSpan">five.</span>hindi ()](#apidoc.element.five.hindi)
- description and source-code
```javascript
hindi = function () { return 'पांच'; }
```
- example usage
```shell
...
five.dutch() // vijf
five.elvish() // lempe
five.english() // Five
five.finnish() // viisi
five.french() // cinq
five.german() // fünf
five.hebrew() // חמש
five.hindi() // पांच
five.indonesian() // lima
five.irish() // cúig
five.italian() // cinque
five.japanese() // 五
five.kannada() // ಐದು
five.klingon() // vagh
five.korean() // 오
...
```

#### <a name="apidoc.element.five.indonesian"></a>[function <span class="apidocSignatureSpan">five.</span>indonesian ()](#apidoc.element.five.indonesian)
- description and source-code
```javascript
indonesian = function () { return 'lima'; }
```
- example usage
```shell
...
five.elvish() // lempe
five.english() // Five
five.finnish() // viisi
five.french() // cinq
five.german() // fünf
five.hebrew() // חמש
five.hindi() // पांच
five.indonesian() // lima
five.irish() // cúig
five.italian() // cinque
five.japanese() // 五
five.kannada() // ಐದು
five.klingon() // vagh
five.korean() // 오
five.latin() // quinque
...
```

#### <a name="apidoc.element.five.irish"></a>[function <span class="apidocSignatureSpan">five.</span>irish ()](#apidoc.element.five.irish)
- description and source-code
```javascript
irish = function () { return 'cúig'; }
```
- example usage
```shell
...
five.english() // Five
five.finnish() // viisi
five.french() // cinq
five.german() // fünf
five.hebrew() // חמש
five.hindi() // पांच
five.indonesian() // lima
five.irish() // cúig
five.italian() // cinque
five.japanese() // 五
five.kannada() // ಐದು
five.klingon() // vagh
five.korean() // 오
five.latin() // quinque
five.mongolian() // таван
...
```

#### <a name="apidoc.element.five.italian"></a>[function <span class="apidocSignatureSpan">five.</span>italian ()](#apidoc.element.five.italian)
- description and source-code
```javascript
italian = function () { return 'cinque'; }
```
- example usage
```shell
...
five.finnish() // viisi
five.french() // cinq
five.german() // fünf
five.hebrew() // חמש
five.hindi() // पांच
five.indonesian() // lima
five.irish() // cúig
five.italian() // cinque
five.japanese() // 五
five.kannada() // ಐದು
five.klingon() // vagh
five.korean() // 오
five.latin() // quinque
five.mongolian() // таван
five.persian() // پنج
...
```

#### <a name="apidoc.element.five.japanese"></a>[function <span class="apidocSignatureSpan">five.</span>japanese ()](#apidoc.element.five.japanese)
- description and source-code
```javascript
japanese = function () { return '五'; }
```
- example usage
```shell
...
five.french() // cinq
five.german() // fünf
five.hebrew() // חמש
five.hindi() // पांच
five.indonesian() // lima
five.irish() // cúig
five.italian() // cinque
five.japanese() // 五
five.kannada() // ಐದು
five.klingon() // vagh
five.korean() // 오
five.latin() // quinque
five.mongolian() // таван
five.persian() // پنج
five.piglatin() // ivefay
...
```

#### <a name="apidoc.element.five.kannada"></a>[function <span class="apidocSignatureSpan">five.</span>kannada ()](#apidoc.element.five.kannada)
- description and source-code
```javascript
kannada = function () { return 'ಐದು'; }
```
- example usage
```shell
...
five.german() // fünf
five.hebrew() // חמש
five.hindi() // पांच
five.indonesian() // lima
five.irish() // cúig
five.italian() // cinque
five.japanese() // 五
five.kannada() // ಐದು
five.klingon() // vagh
five.korean() // 오
five.latin() // quinque
five.mongolian() // таван
five.persian() // پنج
five.piglatin() // ivefay
five.polish() // pięć
...
```

#### <a name="apidoc.element.five.klingon"></a>[function <span class="apidocSignatureSpan">five.</span>klingon ()](#apidoc.element.five.klingon)
- description and source-code
```javascript
klingon = function () { return 'vagh'; }
```
- example usage
```shell
...
five.hebrew() // חמש
five.hindi() // पांच
five.indonesian() // lima
five.irish() // cúig
five.italian() // cinque
five.japanese() // 五
five.kannada() // ಐದು
five.klingon() // vagh
five.korean() // 오
five.latin() // quinque
five.mongolian() // таван
five.persian() // پنج
five.piglatin() // ivefay
five.polish() // pięć
five.portuguese() // cinco
...
```

#### <a name="apidoc.element.five.korean"></a>[function <span class="apidocSignatureSpan">five.</span>korean ()](#apidoc.element.five.korean)
- description and source-code
```javascript
korean = function () { return '오'; }
```
- example usage
```shell
...
five.hindi() // पांच
five.indonesian() // lima
five.irish() // cúig
five.italian() // cinque
five.japanese() // 五
five.kannada() // ಐದು
five.klingon() // vagh
five.korean() // 오
five.latin() // quinque
five.mongolian() // таван
five.persian() // پنج
five.piglatin() // ivefay
five.polish() // pięć
five.portuguese() // cinco
five.romanian() // cinci
...
```

#### <a name="apidoc.element.five.latin"></a>[function <span class="apidocSignatureSpan">five.</span>latin ()](#apidoc.element.five.latin)
- description and source-code
```javascript
latin = function () { return 'quinque'; }
```
- example usage
```shell
...
five.indonesian() // lima
five.irish() // cúig
five.italian() // cinque
five.japanese() // 五
five.kannada() // ಐದು
five.klingon() // vagh
five.korean() // 오
five.latin() // quinque
five.mongolian() // таван
five.persian() // پنج
five.piglatin() // ivefay
five.polish() // pięć
five.portuguese() // cinco
five.romanian() // cinci
five.russian() // пять
...
```

#### <a name="apidoc.element.five.loud"></a>[function <span class="apidocSignatureSpan">five.</span>loud ()](#apidoc.element.five.loud)
- description and source-code
```javascript
loud = function () { return 'FIVE'; }
```
- example usage
```shell
...
'''javascript
five.upHigh() // ⁵
five.downLow() // ₅
five.tooSlow() // 5, with a ~500 millisecond delay
five.roman() // V
five.morseCode() // di-di-di-di-dit
five.negative() // -5
five.loud() // FIVE
five.smooth() // S
'''

##### 5 goes multilingual
'''javascript
five.arabic() // خمسة
five.azerbaijani() // beş
...
```

#### <a name="apidoc.element.five.map"></a>[function <span class="apidocSignatureSpan">five.</span>map (array)](#apidoc.element.five.map)
- description and source-code
```javascript
map = function (array) { return array.map(five); }
```
- example usage
```shell
...
five.binary(); // 101
five.octal(); // 5
five.hex(); // 5
'''

##### Map and Reduce
'''javascript
five.map([1, 2, 3]); // [5, 5, 5]
five.reduce([1, 2, 3]); // 5
'''

##### Novelty
'''javascript
five.fab(); // ['Juwan Howard','Ray Jackson','Jimmy King','Jalen Rose','Chris Webber']
'''
...
```

#### <a name="apidoc.element.five.mongolian"></a>[function <span class="apidocSignatureSpan">five.</span>mongolian ()](#apidoc.element.five.mongolian)
- description and source-code
```javascript
mongolian = function () { return 'таван'; }
```
- example usage
```shell
...
five.irish() // cúig
five.italian() // cinque
five.japanese() // 五
five.kannada() // ಐದು
five.klingon() // vagh
five.korean() // 오
five.latin() // quinque
five.mongolian() // таван
five.persian() // پنج
five.piglatin() // ivefay
five.polish() // pięć
five.portuguese() // cinco
five.romanian() // cinci
five.russian() // пять
five.slovenian() // pet
...
```

#### <a name="apidoc.element.five.morseCode"></a>[function <span class="apidocSignatureSpan">five.</span>morseCode ()](#apidoc.element.five.morseCode)
- description and source-code
```javascript
morseCode = function () { return 'di-di-di-di-dit'; }
```
- example usage
```shell
...

##### Different sorts of 5
'''javascript
five.upHigh() // ⁵
five.downLow() // ₅
five.tooSlow() // 5, with a ~500 millisecond delay
five.roman() // V
five.morseCode() // di-di-di-di-dit
five.negative() // -5
five.loud() // FIVE
five.smooth() // S
'''

##### 5 goes multilingual
'''javascript
...
```

#### <a name="apidoc.element.five.negative"></a>[function <span class="apidocSignatureSpan">five.</span>negative ()](#apidoc.element.five.negative)
- description and source-code
```javascript
negative = function () { return -5; }
```
- example usage
```shell
...
##### Different sorts of 5
'''javascript
five.upHigh() // ⁵
five.downLow() // ₅
five.tooSlow() // 5, with a ~500 millisecond delay
five.roman() // V
five.morseCode() // di-di-di-di-dit
five.negative() // -5
five.loud() // FIVE
five.smooth() // S
'''

##### 5 goes multilingual
'''javascript
five.arabic() // خمسة
...
```

#### <a name="apidoc.element.five.octal"></a>[function <span class="apidocSignatureSpan">five.</span>octal ()](#apidoc.element.five.octal)
- description and source-code
```javascript
octal = function () { return '5'; }
```
- example usage
```shell
...
five.telugu() // ఐదు
five.thai() // ห้า
'''

##### Different radices
'''javascript
five.binary(); // 101
five.octal(); // 5
five.hex(); // 5
'''

##### Map and Reduce
'''javascript
five.map([1, 2, 3]); // [5, 5, 5]
five.reduce([1, 2, 3]); // 5
...
```

#### <a name="apidoc.element.five.persian"></a>[function <span class="apidocSignatureSpan">five.</span>persian ()](#apidoc.element.five.persian)
- description and source-code
```javascript
persian = function () { return 'پنج'; }
```
- example usage
```shell
...
five.italian() // cinque
five.japanese() // 五
five.kannada() // ಐದು
five.klingon() // vagh
five.korean() // 오
five.latin() // quinque
five.mongolian() // таван
five.persian() // پنج
five.piglatin() // ivefay
five.polish() // pięć
five.portuguese() // cinco
five.romanian() // cinci
five.russian() // пять
five.slovenian() // pet
five.spanish() // cinco
...
```

#### <a name="apidoc.element.five.piglatin"></a>[function <span class="apidocSignatureSpan">five.</span>piglatin ()](#apidoc.element.five.piglatin)
- description and source-code
```javascript
piglatin = function () { return 'ivefay'; }
```
- example usage
```shell
...
five.japanese() // 五
five.kannada() // ಐದು
five.klingon() // vagh
five.korean() // 오
five.latin() // quinque
five.mongolian() // таван
five.persian() // پنج
five.piglatin() // ivefay
five.polish() // pięć
five.portuguese() // cinco
five.romanian() // cinci
five.russian() // пять
five.slovenian() // pet
five.spanish() // cinco
five.swedish() // fem
...
```

#### <a name="apidoc.element.five.polish"></a>[function <span class="apidocSignatureSpan">five.</span>polish ()](#apidoc.element.five.polish)
- description and source-code
```javascript
polish = function () { return 'pięć'; }
```
- example usage
```shell
...
five.kannada() // ಐದು
five.klingon() // vagh
five.korean() // 오
five.latin() // quinque
five.mongolian() // таван
five.persian() // پنج
five.piglatin() // ivefay
five.polish() // pięć
five.portuguese() // cinco
five.romanian() // cinci
five.russian() // пять
five.slovenian() // pet
five.spanish() // cinco
five.swedish() // fem
five.tamil() // ஐந்து
...
```

#### <a name="apidoc.element.five.portuguese"></a>[function <span class="apidocSignatureSpan">five.</span>portuguese ()](#apidoc.element.five.portuguese)
- description and source-code
```javascript
portuguese = function () { return 'cinco'; }
```
- example usage
```shell
...
five.klingon() // vagh
five.korean() // 오
five.latin() // quinque
five.mongolian() // таван
five.persian() // پنج
five.piglatin() // ivefay
five.polish() // pięć
five.portuguese() // cinco
five.romanian() // cinci
five.russian() // пять
five.slovenian() // pet
five.spanish() // cinco
five.swedish() // fem
five.tamil() // ஐந்து
five.telugu() // ఐదు
...
```

#### <a name="apidoc.element.five.reduce"></a>[function <span class="apidocSignatureSpan">five.</span>reduce (array)](#apidoc.element.five.reduce)
- description and source-code
```javascript
reduce = function (array) { return array.reduce(five); }
```
- example usage
```shell
...
five.octal(); // 5
five.hex(); // 5
'''

##### Map and Reduce
'''javascript
five.map([1, 2, 3]); // [5, 5, 5]
five.reduce([1, 2, 3]); // 5
'''

##### Novelty
'''javascript
five.fab(); // ['Juwan Howard','Ray Jackson','Jimmy King','Jalen Rose','Chris Webber']
'''
...
```

#### <a name="apidoc.element.five.roman"></a>[function <span class="apidocSignatureSpan">five.</span>roman ()](#apidoc.element.five.roman)
- description and source-code
```javascript
roman = function () { return 'V'; }
```
- example usage
```shell
...
'''

##### Different sorts of 5
'''javascript
five.upHigh() // ⁵
five.downLow() // ₅
five.tooSlow() // 5, with a ~500 millisecond delay
five.roman() // V
five.morseCode() // di-di-di-di-dit
five.negative() // -5
five.loud() // FIVE
five.smooth() // S
'''

##### 5 goes multilingual
...
```

#### <a name="apidoc.element.five.romanian"></a>[function <span class="apidocSignatureSpan">five.</span>romanian ()](#apidoc.element.five.romanian)
- description and source-code
```javascript
romanian = function () { return 'cinci'; }
```
- example usage
```shell
...
five.korean() // 오
five.latin() // quinque
five.mongolian() // таван
five.persian() // پنج
five.piglatin() // ivefay
five.polish() // pięć
five.portuguese() // cinco
five.romanian() // cinci
five.russian() // пять
five.slovenian() // pet
five.spanish() // cinco
five.swedish() // fem
five.tamil() // ஐந்து
five.telugu() // ఐదు
five.thai() // ห้า
...
```

#### <a name="apidoc.element.five.russian"></a>[function <span class="apidocSignatureSpan">five.</span>russian ()](#apidoc.element.five.russian)
- description and source-code
```javascript
russian = function () { return 'пять'; }
```
- example usage
```shell
...
five.latin() // quinque
five.mongolian() // таван
five.persian() // پنج
five.piglatin() // ivefay
five.polish() // pięć
five.portuguese() // cinco
five.romanian() // cinci
five.russian() // пять
five.slovenian() // pet
five.spanish() // cinco
five.swedish() // fem
five.tamil() // ஐந்து
five.telugu() // ఐదు
five.thai() // ห้า
'''
...
```

#### <a name="apidoc.element.five.slovenian"></a>[function <span class="apidocSignatureSpan">five.</span>slovenian ()](#apidoc.element.five.slovenian)
- description and source-code
```javascript
slovenian = function () { return 'pet'; }
```
- example usage
```shell
...
five.mongolian() // таван
five.persian() // پنج
five.piglatin() // ivefay
five.polish() // pięć
five.portuguese() // cinco
five.romanian() // cinci
five.russian() // пять
five.slovenian() // pet
five.spanish() // cinco
five.swedish() // fem
five.tamil() // ஐந்து
five.telugu() // ఐదు
five.thai() // ห้า
'''
...
```

#### <a name="apidoc.element.five.smooth"></a>[function <span class="apidocSignatureSpan">five.</span>smooth ()](#apidoc.element.five.smooth)
- description and source-code
```javascript
smooth = function () { return 'S'; }
```
- example usage
```shell
...
five.upHigh() // ⁵
five.downLow() // ₅
five.tooSlow() // 5, with a ~500 millisecond delay
five.roman() // V
five.morseCode() // di-di-di-di-dit
five.negative() // -5
five.loud() // FIVE
five.smooth() // S
'''

##### 5 goes multilingual
'''javascript
five.arabic() // خمسة
five.azerbaijani() // beş
five.basque() // bost
...
```

#### <a name="apidoc.element.five.spanish"></a>[function <span class="apidocSignatureSpan">five.</span>spanish ()](#apidoc.element.five.spanish)
- description and source-code
```javascript
spanish = function () { return 'cinco'; }
```
- example usage
```shell
...
five.persian() // پنج
five.piglatin() // ivefay
five.polish() // pięć
five.portuguese() // cinco
five.romanian() // cinci
five.russian() // пять
five.slovenian() // pet
five.spanish() // cinco
five.swedish() // fem
five.tamil() // ஐந்து
five.telugu() // ఐదు
five.thai() // ห้า
'''

##### Different radices
...
```

#### <a name="apidoc.element.five.swedish"></a>[function <span class="apidocSignatureSpan">five.</span>swedish ()](#apidoc.element.five.swedish)
- description and source-code
```javascript
swedish = function () { return 'fem'; }
```
- example usage
```shell
...
five.piglatin() // ivefay
five.polish() // pięć
five.portuguese() // cinco
five.romanian() // cinci
five.russian() // пять
five.slovenian() // pet
five.spanish() // cinco
five.swedish() // fem
five.tamil() // ஐந்து
five.telugu() // ఐదు
five.thai() // ห้า
'''

##### Different radices
'''javascript
...
```

#### <a name="apidoc.element.five.tamil"></a>[function <span class="apidocSignatureSpan">five.</span>tamil ()](#apidoc.element.five.tamil)
- description and source-code
```javascript
tamil = function () { return 'ஐந்து'; }
```
- example usage
```shell
...
five.polish() // pięć
five.portuguese() // cinco
five.romanian() // cinci
five.russian() // пять
five.slovenian() // pet
five.spanish() // cinco
five.swedish() // fem
five.tamil() // ஐந்து
five.telugu() // ఐదు
five.thai() // ห้า
'''

##### Different radices
'''javascript
five.binary(); // 101
...
```

#### <a name="apidoc.element.five.telugu"></a>[function <span class="apidocSignatureSpan">five.</span>telugu ()](#apidoc.element.five.telugu)
- description and source-code
```javascript
telugu = function () { return 'ఐదు'; }
```
- example usage
```shell
...
five.portuguese() // cinco
five.romanian() // cinci
five.russian() // пять
five.slovenian() // pet
five.spanish() // cinco
five.swedish() // fem
five.tamil() // ஐந்து
five.telugu() // ఐదు
five.thai() // ห้า
'''

##### Different radices
'''javascript
five.binary(); // 101
five.octal(); // 5
...
```

#### <a name="apidoc.element.five.thai"></a>[function <span class="apidocSignatureSpan">five.</span>thai ()](#apidoc.element.five.thai)
- description and source-code
```javascript
thai = function () { return 'ห้า'; }
```
- example usage
```shell
...
five.romanian() // cinci
five.russian() // пять
five.slovenian() // pet
five.spanish() // cinco
five.swedish() // fem
five.tamil() // ஐந்து
five.telugu() // ఐదు
five.thai() // ห้า
'''

##### Different radices
'''javascript
five.binary(); // 101
five.octal(); // 5
five.hex(); // 5
...
```

#### <a name="apidoc.element.five.tooSlow"></a>[function <span class="apidocSignatureSpan">five.</span>tooSlow ()](#apidoc.element.five.tooSlow)
- description and source-code
```javascript
tooSlow = function () {
  var returnIn = new Date(new Date().valueOf() + 555);

  do {} while(new Date() < returnIn);

  return five();
}
```
- example usage
```shell
...
five() / five(); // 1
'''

##### Different sorts of 5
'''javascript
five.upHigh() // ⁵
five.downLow() // ₅
five.tooSlow() // 5, with a ~500 millisecond delay
five.roman() // V
five.morseCode() // di-di-di-di-dit
five.negative() // -5
five.loud() // FIVE
five.smooth() // S
'''
...
```

#### <a name="apidoc.element.five.upHigh"></a>[function <span class="apidocSignatureSpan">five.</span>upHigh ()](#apidoc.element.five.upHigh)
- description and source-code
```javascript
upHigh = function () { return '⁵'; }
```
- example usage
```shell
...
##### Division
'''javascript
five() / five(); // 1
'''

##### Different sorts of 5
'''javascript
five.upHigh() // ⁵
five.downLow() // ₅
five.tooSlow() // 5, with a ~500 millisecond delay
five.roman() // V
five.morseCode() // di-di-di-di-dit
five.negative() // -5
five.loud() // FIVE
five.smooth() // S
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
