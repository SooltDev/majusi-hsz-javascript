# aprilis-kcs-javascript-2025

## 1. JavaScript `(ECMAScript, ES6)` alapok
> [!NOTE]
> Az `ES6` után több új szabvány is megkjelent, mégis, azért emeljük ki pont ezt a verziót, és nem valamelyik későbbit, mert ez volt a "nagy" vízválasztó, melyben nem csupán náhány függvénnyel, vagy osztályal bővült a Javascript, hanem olyan radikális változásokat hozott, mint a változók hatáskörének kibővítése vagy az OOP nagy átalakulása.

- Mi is az a JavaScript?
- A JavaScript eredete és felhasználási lehetőségei
- JavaScript elhelyezése, importálása, betöltése egy HTML dokumentumban
### Egy kis ízelitő
- A programozás alapvető koncepciói
- A JavaScript programozás alapjai
- DOM Manipuláció
- Gyakorlás: Tartalom megjelenítése HTML oldalon JavaScript segítségével

## 2. A programozás alapjai `Javascript` nyelven
> [!NOTE]
>Ebben a részben elsajáítjuk a programozás alapjait. Ha ezt megérted, akkor a többi programnyelvvel is boldogulni fogsz, hiszen a logikája minden programnyelvek hasonló. Természetesen ezeken az órákon bemutatjuk a JavaScript programozás sajátosságait is.

- Típusok, változó, állandok
    - #### Típusok csoportosítása:
        - Primitívek - (egyszerű típusok) melyek egyszerre csak egy adat tárolására alkalmasak
            - Szám - `Number`
            - Szöveg - `String`
            - Logikai - `Boolean`
            - undefined - `undefined`
        - Összetett Adattípusok, melyek egyszerre több adat tárolására alaklmasak
            - Object, mint adattípus
               - Tömbök
- Operátorok
    - Aritmetikai műveletek
    - Hozzárendelő vagy értékadó operátorok
    - Összehasonlító operátorok
    - Logikai operátorok
    - Léptető operátorok
- Típuskonverzió
- A `Math` object

* ####  Vezérlési szerkezetek
    * `function` - Függvények
       * `arrow function` - nyílfüggvény, rövidített függvény. `ES6 szintaxis`
    * `if-else` - feltételes mód
    * `switch-case` - szelekciós vezérlési szerkezet
    * #### Ciklusok - Iterációk
        - `for` - léptető ciklus
            - `for in`
            - `for of`
        - `while` - feltételes ciklus
            - `while` - elől tesztelő ciklus
            - `do while` - hátúl tesztelő ciklus
    * `try-catch-finaly` - hibakezelés, kivételkezelés
    
* #### Változók hatásköre
- Sztringműveletek
    - Stringkezelő függvények
- Reguláris kifejezések

- Tömbműveletek:
    - Tömbkezelő függvények
    - A tömbök magasabb rendű függvényei
- #### A Spread syntax, avagy a `...` (másoló) operátor:
    - mely segítségével tömböket és objectecet tudunk ki és be csomagolni. Többek közt, lehetővé teszi két változó, harmadik változó ígénybevétele nélküli felcserélését.
- Halmaz műveletek:
    - A Set Object
- Műveletek Object adattípussal
- #### Referencia típusok:
    - Ebben a fejezetben újra csoportosítjuk az adattípusokat. Hiszen nem csak értékük alapján lehet őket csoportosítani, hanem egy adott típus, hozzárendelésben való működése alapján is. 
- A `Date` object, avagy dátumok a Javascriptben

## 3. `DOM` (Document Object Modell) 
#### Javascript alkalmazása front-enden

> Ebben a részben gyakorlatban alkalmazzuk azt, amit elméletben már megalapoztunk Hasznos, vagy szórakoztató mini-alkalmazásokat készítünk a weboldalunkra.

> [!WARNING]
> Ebben a fejezetben, már szükség lesz az eddigi ismereteinkre.

- `DOM` (Document Object Model)
    - DOM szerkezet
    - Csomópontok (Node)
        - Text
        - HtmlElement
    - a `document` object
    - DOM műveletek - HTML elemek manipulálása, Javascript segítségével
        - a children és a childnode
            - köztük levő különbség
        - DOM kezelő függvények
            - egy HTML elem elérése
                - Hagyományos módszerrel, mint pl a `.getElementById`
                - Modern módszer, avagy a `.querySelector` és a `.querySelectorAll`, melyek segítségével egy CSS selector alapján tudunk eg vagy akár több elemt kiválasztani.
                  >[!NOTE] Többek közt ez az `ES6` újítás ásta alá a `jQuery` létjogosultságát, mert most már nem szükséges a jQuery használata a CSS selectorok alapján történő HTML elemek kiválasztásához.
            - a `document` object-en keresztül elérhető függvények
            - Egy Text, vagy HTMLElement csomóponton keresztül elérhető függvények
        - A DOM, egy HTML elemre vonatkozó fontosabb attribútumai
            - Ahol külömbséget teszünk a pusztán csomópont, és HTML csomópont viszonyítási pontok közt
            - Stíluslap (style) kezelése
        - Attribútumok kezelése
        - Saját attríbútumok kezelése:
            - A `dataset` 
    - Eseménykezelés
        - Attribútum típusú eseménykezelés
        - EventTarget-en keresztül való eseménykezelés

## 4. Struktúrális programozás
> Ahhoz, hogy a `3.` fejezetben elkezdett projekteket tovább tudjuk fejleszteni, szükségünk van arra a tudásra, melynek segítségével a kódjainkat, bizonyos modellek alapján rendszerezni, `strukturálni` tudjuk.

- Függvénytárak
    - Vezérlők készítése
- `Module Pattern` - A moduláris programozás
    - Hagyomásnyos függvény alapu modulok
    - A felefedő modul modell
- `ES6 modules` - A `module` mód
    - `export`
    - `import`

## 5. A `document.cookie` - Sütik kezelése
- Mik azok a sütik?
- Mire használhatjuk a sütiket? (Mire valóak egyáltalán)
#### Egy komplett `cookie` modul építése
> A `cookie` modul építése közben, átismételjük, és gyakoroljuk a modulos programozást, miközben megtapasztaljuk azok előnyeit, és nagyszerűségét, egy hasznos gyakoralti példa keretén belül.
#### A `localStorage`
- külömbségek, a `document.cookie`-val szemben

## 6. `Form Validation` - Űrlapok ellenőrzése
>[!NOTE]
> Ebben a fejezetben, Egy összetett, gyakorlati, és a mindennapi programozásban, igen hasznos példán keresztül nézzük meg, mindazt, amit eddig tanultuk.

> Az eddigiekben Javascript nélkül elküldtük a kitöltött űrlapot vagy kérdőívet, és majd kiderült, hogy az jó, vagy hiba van benne. Viszont a böngészőben futó Javascript segítségével, szabályokat határozhatunk meg a felhasználó számára, és csak ezen szabályok mentén tesszük számára lehetővé az űrlap elküldését.
> Ilyen szabályok például: helyes email formátum, karakterszámra vonatkozó megkötések, bizonyos mezők kötelező kitöltése, stb.

## 7. Programozási Paradigmák
### `OOP` - Objektum Orientált Programozás

> Egy olyan programozási paradigma, mely az életből vett mintákra alapszik, és ahol egy objektumnak, egyaránt vannak tulajdonságai, és funkcionalitásai is. Segítségével, egész, működési mechanizmusokat hozhatunk létre, melyeket ezután példányosíthatunk.

- Osztály szerkezete
    - Osztályok tulajdonságai és metódusai
- `function` - prototype alapú osztálydefiníció
- `class` alapú osztálydefiníció 
    - Setter és Getter függvények
    - `private` változók és függvények
    - `statikus` változók és függvények
- Osztályok származtatása - öröklődés
- Nyílfüggvények objektumokban való viselkedése, függvények objektumokhoz való tapadásának szabályai
- A `OOP` és a `DOM`
- ##### Gyakorlati példák, feladatok megvalósítása OOP-vel

## 8. `AJAX` - Asynchron Javascript And XML
### Adatok lekérése más szerveren lévő adatbázisból.

> Itt egy gyakorlati példa erejéig egy nagyobb hangszer adatbázisból kérünk le hangszer adatokat. A böngészőből kéréseket küldünk a szerver felé, amelynek válaszát utána feldolgozzuk és megjelenítjük a felhasználónak. Ez újabb oldalletöltés nélkül megy végbe, `AJAX` felhasználásával.

>[!NOTE]
> Ebben a fejezetben nemcsak a programozásban való megvalósításáról lesz szó, hanem szó esik többek közt:
> - Az URL szerkezetéről
> - A kérés szerkezetéről, mely a kérésben küldött adatok mellett, sok fejléc adat is utazik.
> - stb. ...

- Időzített scriptek - a javascript több szálon való kezelése - belépés az `AJAX` világába.
    - `setTimeout`
    - `setInterval`
- Az `XMLHttpRequest`
    - Kérések küldése távoli erőforrásra
    - Válasz fogadása és feldolgozása és megjelenítése
- `JSON` - (JavaScript Object Notation, JavaScript objektumjelölés)
    - Javascript nyelven alapuló, olvasható adastruktúra, melyet többek közt, kliens-szerver közti adatcsere megvalósítására használunk.
    - A `JSON` függvényei:
        - `parse` - mely segítségével a szövegként érkezett JSON adatstruktúrát használható formára hozzuk.
        - `stringify` - mely segítségével szöveggé alakítjuk a JSON-t. Ebben a formában tudjuk tartósan tárolni, vagy akár egy kérésben a szerver felé továbbítani.
- a `Promise` - Mint igéret, melyet 2 forgatókönyv jellemez.
    - Mi történjen akkor, ha az ígéretet sikerült teljesíteni
    - Mi történjen akkor, ha az ígéret nem teljesült.
- A `Fetch` API - Ami egy `Promise` alapú kérés kezdeményezését teszi lehetővé.

* Rekurzív függvények

***
# 9. `Frontend Vizsga`
***
