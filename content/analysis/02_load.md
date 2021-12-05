---
Title: 02 Load
Description: This is our 02 load page.
Template: technology
menu: analysis
---

# Laddningstid

Jag kommer utvärdera tre webbplatser för att mäta hur snabbt de laddas och om de innehåller några saker som kan förbättras med tanke på laddningstid och användbarhet.

Urval
-----------------------

Jag valde samma tre leksaksaffärer, som förra veckans analys då jag anser att det kan vara intressant att följa dessa tre butiker, men också eftersom alla tre leksaksbutiker slåss om samma kunder. De valda undersidorna är också likvärdiga per sida, dvs startsida, kundservice och en spelsida, för att resultatet ska bli så rättvist som möjligt.

Metod
-----------------------

Jag har mätt olika variabler tre gånger per sida, och angett ett medelvärde i tabellerna. Jag har delat upp tabellerna i mobilvy och datorvy, där det även framgår länkar till de sidorna jag kontrollerat. De siffror som framgår från PageSpeed Insight har dessutom fått den färg som resultatet representerar för att tydligt kunna utläsa hurvida värdet är bra, eller mindre bra. 

Jag tog också reda på hur många förfrågningar som läses in, hur lång tid det tar, samt hur lång laddningstid respektive sida har. Sidstorleken antecknades, men även hur stor del som består av JavaScript och bilder.

Bilderna på datorvyn och mobilvyn tog jag från PageSpeed Insight, då de visas i resultaten där.

#### De verktyg jag använt är: 
PageSpeed Insights - För att kontrollera hastigheter och hur snabbt sidan svarar. <br>
devtools - Jag använde mig av fliken network och kontrollerade både all, JS och Img.

Resultat
-----------------------

### Lekmer

<div class="img-container">
    <picture class="img-box">
        <source media="(min-width: 481px)" srcset="../image/lekmer-mobil.gif?h=300">
        <img src="../image/lekmer-mobil.gif?h=200" alt="Lekmer - bild på mobilvy">
    </picture>
    <picture class="img-box">
        <source media="(min-width: 481px)" srcset="../image/lekmer-dator.gif?h=300">
        <img src="../image/lekmer-dator.gif?h=200" alt="Lekmer - bild på datorvy">
    </picture>
</div>

#### Mobil

<div class="analysis-container">
<iframe class="analysis" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTxA-kv0qM5lLuDVJs6oUK_9GA_a2EUb45uWPXap22394Z3hFD009NJ_vvF9p30RWNOJ0iiERjonbNi/pubhtml?gid=351606946&amp;single=true&amp;widget=true&amp;headers=false" frameborder="0" scrolling="no"></iframe>
</div>

Den tid det tar innan man kan se den första texten eller bilden hamnar mellan 1-1,6 i den mobila vyn, vilket anses som snabbt. 
Likaså den tid det tar för websidan att svara efter en interaktion, ger gröna siffror, vilket indikerar på en snabb respons. 
CLS, vilket indikerar hur stabilt en websida beter sig visuellt, hamnar för alla undersidor också på gröna siffror. Så här långt är resultaten bra.

Det är först när prestandan mäts, dvs när flera olika mätvärden läggs ihop och ger ett viktat medelvärde, som vi ser både gula och röda siffror vilket pekar på att det finns saker som behöver förbättras och att det inte längre ser så bra ut.

Startsidan är den sida som gör sämst ifrån sig. Prestandan hamnar på ynka 43 poäng, vilket ger röda siffror. Det beror på bland annat att det tar i snitt 5 sekunder innan innehåll visas visuellt under sidladdningen och att det tar hela 8,4 sekunder innan sidan blir helt interaktiv. Startsidan har 115 förfrågningar, vilka tar 11,33 sekunder att ladda in. Startsidan är totalt 4,9 MB stor, varav JavaScript tar upp 2,7 MB och bilder 1,6 MB. JavaScript och bilder motsvarar därför hela 4,3 MB, alltså 88% av startsidans totala storlek. Startsidan hamnar på en laddningstid på 888 ms, vilket får anses som snabbt. 

Kundservice hamnar på 69 poäng, vilket ger gula siffror. Det tar i snitt 3,2 sekunder innan innehåll visas visuellt under sidladdningen och att det tar hela 7,1 sekunder innan sidan blir helt interaktiv. Kundservice har 37 förfrågningar, vilka tar 2,3 sekunder att ladda in. Kundservice är totalt 1,9 MB stor, varav JavaScript tar upp 1,5 MB och bilder ynka 9 kB. JavaScript tar därför upp 79% av den totala storleken av kundservice-sidan. Laddningstiden för sidan hamnar på 1,05 sekunder, vilket är något mer än startsidan. 

Spelsidan hamnar på 77 poäng, vilket ger gula siffror. Det tar i snitt 3,5 sekunder innan innehåll visas visuellt under sidladdningen och att det tar hela 7,6 sekunder innan sidan blir helt interaktiv. Spelsidan har 122 förfrågningar, vilka tar 16,34 sekunder att ladda in. Spelsidan är totalt 3,4 MB stor, varav JavaScript tar upp 2,7 MB och bilder ynka 98 kB. JavaScript tar därför upp 79% av den totala storleken av spelsidan. Laddningstiden för sidan hamnar på 968 ms, vilket är något mer än startsidan, och något mindre än kundservice-sidan. 

De förbättringsåtgärder som jag ser att Lekmer kan göra för sin mobila vy är att dels använda bilder i rätt storlek, men också att använda bildformat som ger bättre komprimering än exempelvis jpeg. Lekmer skulle också behöva se över den JavaScript som används och reducera det som inte används, och se till att det viktigaste läses in först, men även försöka undvika äldre JavaScript i nyare webbläsare. 

#### Dator

<div class="analysis-container">
<iframe class="analysis" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTxA-kv0qM5lLuDVJs6oUK_9GA_a2EUb45uWPXap22394Z3hFD009NJ_vvF9p30RWNOJ0iiERjonbNi/pubhtml?gid=1768757180&amp;single=true&amp;widget=true&amp;headers=false" frameborder="0" scrolling="no"></iframe>
</div>

Den tid det tar innan man kan se den första texten eller bilden hamnar mellan 0,9-1,4 i datorvyn, vilket anses som snabbt. 
Likaså den tid det tar för websidan att svara efter en interaktion, ger gröna siffror, vilket indikerar på en snabb respons. 
CLS, vilket indikerar hur stabilt en websida beter sig visuellt, hamnar för alla undersidor också på gröna siffror. Så här långt är resultaten bra.

När prestandan mäts, dvs när flera olika mätvärden läggs ihop och ger ett viktat medelvärde, ser vi bara värden vilka alla överstiger 90 poäng, vilket är jättebra.

Startsidan är den sida som gör sämst ifrån sig, av de tre sidor vi testat. Prestandan hamnar på 90 poäng. Det beror på bland annat att det tar i snitt 1,4 sekunder innan innehåll visas visuellt under sidladdningen, vilket ger gula siffror, och att det tar 1,9 sekunder innan sidan blir helt interaktiv. Startsidan har 124 förfrågningar, vilka tar 11 sekunder att ladda in. Startsidan är totalt 5,7 MB stor, varav JavaScript tar upp 2,7 MB och bilder 2,5 MB. JavaScript och bilder motsvarar därför hela 5,2 MB, alltså 91% av startsidans totala storlek. Startsidan hamnar på en laddningstid på 860 ms, vilket får anses som snabbt. 

Kundservice hamnar på 98 poäng, vilket är jättebra. Det tar i snitt 0,9 sekunder innan innehåll visas visuellt under sidladdningen och att det tar 1,2 sekunder innan sidan blir helt interaktiv. Kundservice har 35 förfrågningar, vilka tar 1,9 sekunder att ladda in. Kundservice är totalt 1,9 MB stor, varav JavaScript tar upp 1,5 MB och bilder ynka 9 kB. JavaScript tar därför upp 79% av den totala storleken av kundservice-sidan. Laddningstiden för sidan hamnar på 608 ms, vilket är något mindre än startsidan. 

Spelsidan hamnar på 99 poäng, vilket ger det bästa värdet av de jämförda sidorna. Det tar i snitt 1 sekund innan innehåll visas visuellt under sidladdningen och att det tar hela 1,5 sekunder innan sidan blir helt interaktiv. Spelsidan har 136 förfrågningar, vilka tar 8,28 sekunder att ladda in. Spelsidan är totalt 3,6 MB stor, varav JavaScript tar upp 2,7 MB och bilder 322 kB. JavaScript tar därför upp 75% av den totala storleken av spelsidan. Laddningstiden för sidan hamnar på 1,11 sekunder, vilket är mer än för startsidan och kundservice-sidan. 

De förbättringsåtgärder som jag ser att Lekmer kan göra för sin datorvy, är främst att reducera den JavaScript som inte används och se till att det viktigaste läses in först, men också att använda bilder i rätt storlek och bildformat som ger bättre komprimering än exempelvis jpeg. 

### Hiko

<div class="img-container">
    <picture class="img-box">
        <source media="(min-width: 481px)" srcset="../image/hiko-mobil.gif?h=300">
        <img src="../image/hiko-mobil.gif?h=200" alt="Hiko - bild på mobilvy">
    </picture>
    <picture class="img-box">
        <source media="(min-width: 481px)" srcset="../image/hiko-dator.gif?h=300">
        <img src="../image/hiko-dator.gif?h=200" alt="Hiko - bild på datorvy">
    </picture>
</div>

#### Mobil

<div class="analysis-container">
<iframe class="analysis" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTxA-kv0qM5lLuDVJs6oUK_9GA_a2EUb45uWPXap22394Z3hFD009NJ_vvF9p30RWNOJ0iiERjonbNi/pubhtml?gid=1758805393&amp;single=true&amp;widget=true&amp;headers=false" frameborder="0" scrolling="no"></iframe>
</div>

Den tid det tar innan man kan se den första texten eller bilden hamnar mellan 1-1,3 i den mobila vyn, vilket anses som snabbt. 
Likaså den tid det tar för websidan att svara efter en interaktion, ger gröna siffror, vilket indikerar på en snabb respons. 
CLS, vilket indikerar hur stabilt en websida beter sig visuellt, hamnar för två undersidor också på gröna siffror, och en sida får en gul siffra. Så här långt är resultaten bra.

Det är först när prestandan mäts, dvs när flera olika mätvärden läggs ihop och ger ett viktat medelvärde, som vi ser mycket gula och röda siffror vilket pekar på att det finns saker som behöver förbättras och att det inte längre ser lika bra ut.

Startsidan hamnar på 59 poäng, vilket ger röda siffror. Det beror på bland annat på att det tar i snitt 3,9 sekunder innan innehåll visas visuellt under sidladdningen, vilket är en gul siffra, och det tar hela 9,8 sekunder innan sidan blir helt interaktiv, vilket är en röd siffra. Startsidan har 94 förfrågningar, vilka tar 2,63 sekunder att ladda in. Startsidan är totalt 2,3 MB stor, varav JavaScript tar upp 1,4 MB och bilder 383 kB. JavaScript tar därför upp 61% av den totala storleken av startsidan. Laddningstiden för sidan hamnar på 1,5 sekunder. 

Kundservice hamnar på 74 poäng, vilket ger gula siffror. Det tar i snitt 3,1 sekunder innan innehåll visas visuellt under sidladdningen och att det tar hela 8,6 sekunder innan sidan blir helt interaktiv. Kundservice har 63 förfrågningar, vilka tar 2,53 sekunder att ladda in. Kundservice är totalt 2 MB stor, varav JavaScript tar upp 1,4 MB och bilder 69,6 kB. JavaScript tar därför upp 70% av den totala storleken av kundservice-sidan. Laddningstiden för sidan hamnar på 1,42 sekunder, vilket är något mindre än startsidan. 

Spelsidan är den sida som gör sämst ifrån sig. Prestandan hamnar på 55 poäng, vilket ger gula siffror. Det tar i snitt 3,8 sekunder innan innehåll visas visuellt under sidladdningen och att det tar hela 9,4 sekunder innan sidan blir helt interaktiv. Spelsidan har 88 förfrågningar, vilka tar 2,46 sekunder att ladda in. Spelsidan är totalt 2,4 MB stor, varav JavaScript tar upp 1,4 MB och bilder 383 kB. JavaScript tar därför upp 58% av den totala storleken av spelsidan. Laddningstiden för sidan hamnar på 1,33 sekunder, vilket är något mindre än för både startsidan och kundservice-sidan. 

De förbättringsåtgärder som jag ser att Hiko kan göra för sin mobila vy är att dels se över den JavaScript som används och reducera det som inte används, och se till att det viktigaste läses in först, men även försöka undvika äldre JavaScript i nyare webbläsare. Hiko skulle också kunna använda bildformat som ger bättre komprimering än exempelvis jpeg. Hiko skulle också behöva se till att det som är viktigast läses in först. 

#### Dator

<div class="analysis-container">
<iframe class="analysis" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTxA-kv0qM5lLuDVJs6oUK_9GA_a2EUb45uWPXap22394Z3hFD009NJ_vvF9p30RWNOJ0iiERjonbNi/pubhtml?gid=52321698&amp;single=true&amp;widget=true&amp;headers=false" frameborder="0" scrolling="no"></iframe>
</div>

Den tid det tar innan man kan se den första texten eller bilden hamnar mellan 0,8-1,1 i datorvyn, vilket anses som snabbt. 
Likaså den tid det tar för websidan att svara efter en interaktion, ger gröna siffror, vilket indikerar på en snabb respons. 
CLS, vilket indikerar hur stabilt en websida beter sig visuellt, hamnar för två undersidor också på gröna siffror, och en sida får en gul siffra. Så här långt är resultaten bra.

När prestandan mäts, dvs när flera olika mätvärden läggs ihop och ger ett viktat medelvärde, ser vi två gröna värden och ett gult. Alla värden överstiger 89. vilket ändå får ses som bra.

Startsidan är den sida som gör sämst ifrån sig, av de tre sidor vi testat. Prestandan hamnar på 89 poäng. Det tar i snitt 0,8 sekunder innan innehåll visas visuellt under sidladdningen, och att det tar 0,8 sekunder innan sidan blir helt interaktiv. Startsidan har 94 förfrågningar, vilka tar 2,1 sekunder att ladda in. Startsidan är totalt 2,3 MB stor, varav JavaScript tar upp 1,4 MB och bilder 383 kB. JavaScript tar därför upp 61% av startsidans totala storlek. Startsidan hamnar på en laddningstid på 1,28 sekunder. 

Kundservice hamnar på 95 poäng, vilket är bra. Det tar i snitt 0,8 sekunder innan innehåll visas visuellt under sidladdningen och att det tar 0,8 sekunder innan sidan blir helt interaktiv. Kundservice har 63 förfrågningar, vilka tar 3,43 sekunder att ladda in. Kundservice är totalt 2 MB stor, varav JavaScript tar upp 1,4 MB och bilder 69,6 kB. JavaScript tar därför upp 70% av den totala storleken av kundservice-sidan. Laddningstiden för sidan hamnar på 2,25 sekunder, vilket är betydligt mer än startsidan. 

Spelsidan hamnar på 92 poäng, vilket ger det bästa värdet av de jämförda sidorna. Det tar i snitt 0,9 sekunder innan innehåll visas visuellt under sidladdningen och att det tar 0,8 sekunder innan sidan blir helt interaktiv. Spelsidan har 91 förfrågningar, vilka tar 2,65 sekunder att ladda in. Spelsidan är totalt 2,4 MB stor, varav JavaScript tar upp 1,4 MB och bilder 385 kB. JavaScript tar därför upp 58% av den totala storleken av spelsidan. Laddningstiden för sidan hamnar på 1,41 sekunder, vilket är mer än för startsidan och mindre än för kundservice-sidan. 

De förbättringsåtgärder som jag ser att Hiko kan göra för sin datorvy är att främst att se över den JavaScript som används och reducera det som inte används, och se till att det viktigaste läses in först, men även se över den CSS som inte är aktuell.

### LekAkademin

<div class="img-container">
    <picture class="img-box">
        <source media="(min-width: 481px)" srcset="../image/lekakademin-mobil.gif?h=300">
        <img src="../image/lekakademin-mobil.gif?h=200" alt="LekAkademin - bild på mobilvy">
    </picture>
    <picture class="img-box">
        <source media="(min-width: 481px)" srcset="../image/lekakademin-dator.gif?h=300">
        <img src="../image/lekakademin-dator.gif?h=200" alt="LekAkademin - bild på datorvy">
    </picture>
</div>

#### Mobil

<div class="analysis-container">
<iframe class="analysis" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTxA-kv0qM5lLuDVJs6oUK_9GA_a2EUb45uWPXap22394Z3hFD009NJ_vvF9p30RWNOJ0iiERjonbNi/pubhtml?gid=1604888652&amp;single=true&amp;widget=true&amp;headers=false" frameborder="0" scrolling="no"></iframe>
</div>

Den tid det tar innan man kan se den första texten eller bilden hamnar mellan 1,6-2,4 i den mobila vyn, vilket anses som långsamt. 
Den tid det tar för websidan att svara efter en interaktion, ger gröna siffror, vilket indikerar på en snabb respons. 
CLS, vilket indikerar hur stabilt en websida beter sig visuellt, hamnar för alla undersidor på gula siffror, vilket inte är så bra.

När prestandan mäts, dvs när flera olika mätvärden läggs ihop och ger ett viktat medelvärde, ser vi bara röda siffror vilket pekar på att det definitivt finns saker som behöver förbättras och att det inte ser bra ut.

Startsidan hamnar på ynka 16 poäng, vilket är katastrofalt dåligt. Det beror på bland annat att det tar i snitt 11,1 sekunder innan innehåll visas visuellt under sidladdningen och att det tar hela 21,4 sekunder innan sidan blir helt interaktiv. Startsidan har 325 förfrågningar, vilka tar 6,36 sekunder att ladda in. Startsidan är totalt 6,3 MB stor, varav JavaScript tar upp 4,1 MB och bilder 680 kB. JavaScript och bilder motsvarar därför hela 4,78 MB, alltså 76% av startsidans totala storlek. Startsidan hamnar på en laddningstid på 3,86 sekunder, vilket får anses som väldigt långsamt. 

Kundservice hamnar på 28 poäng, vilket av de tre sidorna är den bästa poängen, men ändå ger gula siffror och är ett fruktansvärt dåligt resultat. Det tar i snitt 8,3 sekunder innan innehåll visas visuellt under sidladdningen och att det tar hela 15,2 sekunder innan sidan blir helt interaktiv. Kundservice har 271 förfrågningar, vilka tar 5,26 sekunder att ladda in. Kundservice är totalt 5,6 MB stor, varav JavaScript tar upp 4 MB och bilder 223 kB. JavaScript tar därför upp 71% av den totala storleken av kundservice-sidan. Laddningstiden för sidan hamnar på 3,1 sekunder, vilket är något mindre än för startsidan. 

Spelsidan är den sida som gör sämst ifrån sig. Prestandan hamnar på 15 poäng, vilket ger röda siffror. Det tar i snitt 15,8 sekunder innan innehåll visas visuellt under sidladdningen och att det tar hela 20,2 sekunder innan sidan blir helt interaktiv. Spelsidan har 327 förfrågningar, vilka tar 10,68 sekunder att ladda in. Spelsidan är totalt 6,6 MB stor, varav JavaScript tar upp 4,2 MB och bilder 384 kB. JavaScript tar därför upp 64% av den totala storleken av spelsidan. Laddningstiden för sidan hamnar på 8,07 sekunder, vilket är betydligt mer än för startsidan och kundservice-sidan. 

De förbättringsåtgärder som jag ser att LekAkademin kan göra för sin mobila vy är att dels se till att det som är viktigast läses in först, och att det som är mindre viktigt läses in senare för att inte förhindra renderingen. Minska serverns första svarstid och se över den JavaScript som används och reducera det som inte används, men också använda bildformat som ger bättre komprimering än exempelvis jpeg.

#### Dator

<div class="analysis-container">
<iframe class="analysis" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTxA-kv0qM5lLuDVJs6oUK_9GA_a2EUb45uWPXap22394Z3hFD009NJ_vvF9p30RWNOJ0iiERjonbNi/pubhtml?gid=489379626&amp;single=true&amp;widget=true&amp;headers=false" frameborder="0" scrolling="no"></iframe>
</div>

Den tid det tar innan man kan se den första texten eller bilden hamnar mellan 1,4-2,3 i datorvyn, vilket anses som långsamt. 
Den tid det tar för websidan att svara efter en interaktion, ger gröna siffror, vilket indikerar på en snabb respons. 
CLS, vilket indikerar hur stabilt en websida beter sig visuellt, hamnar för en undersida på gul siffra och för de andra två undersidorna på röda siffror, vilket inte är bra.

När prestandan mäts, dvs när flera olika mätvärden läggs ihop och ger ett viktat medelvärde, ser vi gula och röda siffror vilket pekar på att det definitivt finns saker som behöver förbättras och att det inte ser bra ut.

Startsidan hamnar på 59 poäng, vilket ger en gul siffra. Det beror på bland annat att det tar i snitt 2,4 sekunder innan innehåll visas visuellt under sidladdningen, och att det tar 3,9 sekunder innan sidan blir helt interaktiv. Startsidan har 328 förfrågningar, vilka tar 5,97 sekunder att ladda in. Startsidan är totalt 6,4 MB stor, varav JavaScript tar upp 4,1 MB och bilder 736 kB. JavaScript och bilder motsvarar därför hela 4,836 MB, alltså 76% av startsidans totala storlek. Startsidan hamnar på en laddningstid på 3,55 sekunder, vilket får anses som långsamt. 

Kundservice hamnar på 79 poäng, vilket är dåligt, men åt det bättre hållet. Det tar i snitt 1,9 sekunder innan innehåll visas visuellt under sidladdningen och att det tar 3 sekunder innan sidan blir helt interaktiv. Kundservice har 279 förfrågningar, vilka tar 4,31 sekunder att ladda in. Kundservice är totalt 5,6 MB stor, varav JavaScript tar upp 4 MB och bilder 251 kB. JavaScript tar därför upp 71% av den totala storleken av kundservice-sidan. Laddningstiden för sidan hamnar på 2,91 sekunder, vilket är något mindre än för startsidan. 

Spelsidan är den sida som gör sämst ifrån sig, av de tre sidor vi testat. Prestandan hamnar på 33 poäng, vilket ger röda siffror. Det tar i snitt 4,8 sekunder innan innehåll visas visuellt under sidladdningen och att det tar hela 5,3 sekunder innan sidan blir helt interaktiv. Spelsidan har 329 förfrågningar, vilka tar 10,59 sekunder att ladda in. Spelsidan är totalt 6,6 MB stor, varav JavaScript tar upp 4,2 MB och bilder 385 kB. JavaScript tar därför upp 64% av den totala storleken av spelsidan. Laddningstiden för sidan hamnar på 8,02 sekunder, vilket är betydligt mer än för startsidan och kundservice-sidan. 

De förbättringsåtgärder som jag ser att LekAkademin kan göra för sin datorvy är att minska serverns första svarstid, låta det som är mindre viktigt läses in senare för att inte förhindra renderingen. LekAkademin behöver se över den JavaScript som används och reducera det som inte används, men också kunna använda bildformat som ger bättre komprimering än exempelvis jpeg.

Analys
-----------------------
#### Mobil

<div class="analysis-container">
<iframe class="analysis-all" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTxA-kv0qM5lLuDVJs6oUK_9GA_a2EUb45uWPXap22394Z3hFD009NJ_vvF9p30RWNOJ0iiERjonbNi/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false" frameborder="0" scrolling="no"></iframe>
</div>

Det vi kan se när vi jämför de tre olika websidorna och dess undersidor, är att Lekmer är den sidan som bara har gröna siffror vad gäller tiden det tar innan man kan se den första texten eller bilden, tiden det tar för websidan att svara efter en interaktion och för CLS, vilket indikerar hur stabilt websidan beter sig visuellt. Hiko kommer inte långt efter, med endast en gul siffra för CLS-värdet på startsidan. Faktum är att Hiko faktiskt har bättre siffror än Lekmer på några av värdena. LekAkademin har ungefär hälften grönt och hälften gult, och dessutom avsevärt sämre värden än vad både Lekmer och Hiko har.

När prestandan mäts, dvs när flera olika mätvärden läggs ihop och ger ett viktat medelvärde, ser vi att Hiko presterar bäst, med enbart gula siffror i spannet 55-79, Lekmer kommer på andraplats med två gula siffror och en röd, vilket gör att Lekmer hamnar mellan 43-77 i poängskalan. Återigen kommer LekAkademin sist, med tre röda siffror i spannet 15-28, vilket är väldigt dåligt. 

Om vi tittar på två av de mätvärden som är en del av prestandapoängen, så ser vi att Lekmer precis med nöd och näppe får bättre resultat än Hiko. Däremot så har Lekmer och Hiko varsin grön siffra, resten består till ungefär hälften av gult och hälften av rött. LekAkademin får enbart röda siffror som är upp till 4,5 gånger så högt som Lekmers ena värde, men ungefär dubbelt så höga på det mesta. När vi tittar på hur många förfrågningar de olika sidorna har, får vi delvis svaret på hur deras siffror skiljer sig åt så här markant. Lekmer har mellan 37-122 förfrågningar beroende på sida, Hiko har ett mer konsekvent antal mellan 63-94, och LekAkademin har mellan 271-327. 

LekAkademin har inte bara flest förfrågningar, utan har också den absolut största sidan och hamnar på 5,6-6,6 MB på de olika undersidorna. Det är däremot inte bilderna som gör att sidan blir så stor, utan det är främst JavaScript, då sidans storlek i snitt består av JavaScript till 67%. Det tar mellan 5,26-10,68 sekunder för sidan att ta emot alla förfrågningar, och mellan 3,1-8,07 sekunder att ladda Hikos sida. 

Lekmer hamnar i mitten både vad gäller förfrågningar och sidstorlek. Sidans storlek hamnar mellan 1,9-4,9, och består i snitt av 71% JavaScript. Bilderna tar inte någon större plats för kundservice- och spelsidan, men för startsidan tar bilderna upp 1,6 MB, vilket gör att bilderna och JavaScript tillsammans för startsidan tar upp 4,3 MB av 4,9 MB, vilket motsvarar 88%. Lekmer presterar absolut sämst med den tid det tar för förfrågningarna att läsas in helt. För kundservicesidan tar det 2,3 sekunder, men för startsidan och spelsidan hamnar det på mellan 11,33-16,34 sekunder, vilket är väldigt lång tid. Själva laddningstiden för Lekmer hamnar däremot på mellan 0,888-1,05 sekunder, vilket får ses som väldigt bra. Speciellt med tanke på de antal förfrågningar och den storlek Lekmers sida ändå faktiskt har. 

Hiko Presterar bäst både vad gäller antalet förfrågningar och sidans storlek. Sidstorleken ligger konsekvent på mellan 2-2,4 MB, och det tar mellan 2,46-2,63 sekunder för att läsa in förfrågningarna. Själva laddningstiden för Hiko hamnar mellan 1,33-1,50 sekunder, vilket ändå är längre tid än vad det tar för Lekmer att ladda in sin sida. JavaScripten som läses in ligger på 1,4 MB för samtliga tre undersidor, och består därför består Hikos sida i snitt av 63% JavaScript.

#### Dator

<div class="analysis-container">
<iframe class="analysis-all" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTxA-kv0qM5lLuDVJs6oUK_9GA_a2EUb45uWPXap22394Z3hFD009NJ_vvF9p30RWNOJ0iiERjonbNi/pubhtml?gid=1987593451&amp;single=true&amp;widget=true&amp;headers=false" frameborder="0" scrolling="no"></iframe>
</div>

Det vi kan se när vi jämför de tre olika websidorna och dess undersidor, är att Lekmer är den sidan som bara har gröna siffror vad gäller tiden det tar innan man kan se den första texten eller bilden, tiden det tar för websidan att svara efter en interaktion och för CLS, vilket indikerar hur stabilt websidan beter sig visuellt. Hiko kommer inte långt efter, med endast en gul siffra för CLS-värdet på startsidan. Hiko har förutom en gul siffra, resten grönt och presterar bättre än Lekmer. LekAkademin har två röda, tre gula och fyra gröna siffror och har oavsett färg avservärt sämre siffror än både Lekmer och Hiko.

När prestandan mäts, dvs när flera olika mätvärden läggs ihop och ger ett viktat medelvärde, ser vi att Hiko presterar bäst, åtminstone om man ser till siffrorna som representerar tiden tills att sidan är fullt interaktiv och hur snabbt innehållet laddas upp på sidan. Lekmer kommer på andraplats och LekAkademin sist med avsevärt sämre resultat. Om vi ser till prestandapoängen, som räknar med andra faktorer också som inte syns i tabellerna så kommer Lekmer på förstaplats med poäng mellan 90-99, men precis bakefter kommer Hiko med 89-95, och sist kommer LekAkademin med intervallet 33-79, vilket är dåligt. Lekmer har mellan 35-136 förfrågningar beroende på sida, Hiko har ett mer konsekvent antal mellan 63-94, och LekAkademin har mellan 279-329. 

LekAkademin har inte bara flest förfrågningar, utan har också den absolut största sidan och hamnar på 5,6-6,6 MB på de olika undersidorna. Det är däremot inte bilderna som gör att sidan blir så stor, utan det är främst JavaScript, då sidans storlek i snitt består av JavaScript till 66%. Det tar mellan 4,31-10,59 sekunder för sidan att ta emot alla förfrågningar, och mellan 2,91-8,02 sekunder att ladda Hikos sida. 

Lekmer hamnar i mitten både vad gäller förfrågningar och sidstorlek. Sidans storlek hamnar mellan 1,9-5,7, och består i snitt av 67% JavaScript. Bilderna tar inte någon större plats för kundservice- och spelsidan, men för startsidan tar bilderna upp 2,5 MB, vilket gör att bilderna och JavaScript tillsammans för startsidan tar upp 5,2 MB av 5,7 MB, vilket motsvarar 91%. Lekmer presterar sämst med den tid det tar för förfrågningarna att läsas in helt, om man räknar ihop alla tre resultaten. För kundservicesidan tar det 1,9 sekunder, men för startsidan hamnar det på 11 sekunder, vilket är väldigt lång tid. Själva laddningstiden för Lekmer hamnar däremot på mellan 0,608-1,11 sekunder, vilket får ses som väldigt bra. Speciellt med tanke på de antal förfrågningar och den storlek Lekmers sida ändå faktiskt har. 

Hiko Presterar bäst både vad gäller antalet förfrågningar och sidans storlek. Sidstorleken ligger konsekvent på mellan 2-2,4 MB, och det tar mellan 2,1-3,43 sekunder för att läsa in förfrågningarna. Själva laddningstiden för Hiko hamnar mellan 1,28-2,25 sekunder, vilket ändå är längre tid än vad det tar för Lekmer att ladda in sin sida. JavaScripten som läses in ligger på 1,4 MB för samtliga tre undersidor, och består därför består Hikos sida i snitt av 62% JavaScript.

### Rangording

#### Mobil

<div class="analysis-container">
<iframe class="analysis-rang" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTxA-kv0qM5lLuDVJs6oUK_9GA_a2EUb45uWPXap22394Z3hFD009NJ_vvF9p30RWNOJ0iiERjonbNi/pubhtml?gid=1112881564&amp;single=true&amp;widget=true&amp;headers=false" frameborder="0" scrolling="no"></iframe>
</div>

Jag har rangordnat mobilvyn enligt Ttol (Time to interactive), vilket innebär hur lång tid det tar för sidan att bli helt interaktiv. Det resulterade i att samtliga Lekmers sidor kom i topp och vann den rangordningen. Jag valde även att rangordna den andra tabellen enligt laddningstiden, vilket resulterade i samma upplägg. Lekmers samtliga sidor kom i topp, tätt följda av Hiko, och i botten LekAkademin. Det speglar också den uppfattning jag upplevde när jag besökte sidorna utan några mätverktyg.

#### Dator

<div class="analysis-container">
<iframe class="analysis-rang" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTxA-kv0qM5lLuDVJs6oUK_9GA_a2EUb45uWPXap22394Z3hFD009NJ_vvF9p30RWNOJ0iiERjonbNi/pubhtml?gid=636625649&amp;single=true&amp;widget=true&amp;headers=false" frameborder="0" scrolling="no"></iframe>
</div>

Jag har rangordnat datorvyn på samma vis som för mobilvyn. Det jag däremot utgick ifrån när TtoI var samma, var Speed index, och i ett tredje steg fick prestandapoängen avgöra placering. Det resulterade i att Hiko knep första platsen i den tabellen. Den andra tabellen, som rangordnades precis som i mobilvyn, dvs laddningstiden, resulterade i att Lekmer knep första platsen i den här rangordningen även i datorvyn. 

### Syntes av analysen

Det vi kan komma fram till är att Lekmer är den totala vinnaren i den här granskningen, även om Hiko kommer hack i häl. Trots Lekmers stora sida, så laddas sidan fort och blir fullt interaktiv, åtminstone via dator. Även om det förekommer många förfrågningar, och tiden till att alla dessa är klara är lång ibland, så bli sidan fullt interaktiv snabbt och det märks inte av för mig som surfande kund att det mindre nödvändiga laddas in i bakgrunden. Hiko trots sin mindre storlek, nästan hälften av Lekmer, har längre laddningstid, även om den befinner sig i ett godkänt spann. LekAkademin kommer sist i den här granskningen då det är en stor tung sida, som ibland tar flera sekunder att ladda in, vilket skapar en frustration.

Personligen blir jag otålig ganska snabbt när sidorna tar för lång tid på sig att laddas in. Jag tror att min gräns för vad som räknas som långsamt går vid ungefär 3 sekunder. Dvs 0-3 sekunder är snabbt, 3-5 sekunder långsamt, men okej, 5+ sekunder långsamt och kan få mig att klicka mig vidare om det inte är något alldeles särskilt jag väntar på. 

Om jag utgår från min uppfattning när jag surfar till de olika sidorna, så upplever jag oftast både Lekmer och Hiko som snabba, och LekAkademin gör mig otålig. När jag kollar på siffrorna så speglar de min upplevelse. De är något långsammare för att kunna klicka mig vidare, vilket är något som kan göra mig otålig ifall jag har siktet inställt på något särskilt att klicka mig vidare på.

### Syntes av de vanligaste förbättringsåtgärderna

Det som genrellt skulle kunna förbättra både vad gäller mobilvy som datorvy är att se över den JavaScript som används och reducera det som inte används. Dessutom är det fördelaktig att låta det som är mindre viktigt läsas in senare, för att inte förhindra renderingen. Något som också skulle behöva göras är att använda bildformat som ger bättre formatering än exempelvis jpeg, och även se till att bilderna laddas in i rätt storlek.

Referenser
-----------------------

https://web.dev/lighthouse-performance/

Övrigt
-----------------------

Författare: Anna Nilsson