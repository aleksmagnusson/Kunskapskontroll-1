# Kunskapskontroll-1
Ni ska bygga en responsiv portfolio med hjälp av de tekniker ni lärt er hittills.
Detta inkluderar HTML, CSS och responsiv web design.

Ni ska bygga en responsiv portfolio med hjälp av de tekniker ni lärt er hittills. Detta inkluderar HTML, CSS och responsiv web design.


För att uppnå "Godkänt" är kraven att:


Den ska innehålla tre stycken sidor: index.html (som är förstasidan), experience.html (som som visar er erfarenhet) och contact.html (som innehåller ett litet formulär menat för att kunna kontakta er. 
Formuläret på contact.html skall innehålla tre element som representerar: message, email och en submit button).
All CSS ska vara placerad i minst en extern css-fil som läses in via <link>. Se om ni har anledning att skapa fler filer än en (inget måste).
Innehålla en huvudnavigationsmeny som består av länkar till de olika sidor (Home, Experience, Contact).
Den är anpassad till att “se bra ut” på enheter från iPhone 6/7/8 (i Chrome device toolbar är denna enhet 375px i bredd) hela vägen upp till 1024px (en av de vanliga större bredder att stödja). Anpassning utöver detta intervall är ej nödvändigt.
Minst en användning av en media query för att anpassa enligt kraven ovan.
Det är upp till er i vilken ordning ni väljer att anpassa er hemsida (mobile first, desktop first etc), men ett tips är att välja en process och hålla er till den för att underlätta byggandet av projektet
Flexbox eller Grid eller båda tekniker skall användas minst en gång i projektet (gärna fler om ni har behov av det). Dessa verktyg kommer hjälpa er avsevärt i implementationen av era layouter.
Språket för innehållet på er portfolio ska vara svenska eller engelska. Lorem (latin) får även användas för innehåll (om ni känner att ni ej kommer på erfarenhet eller liknande på egen hand)
Inlämning sker via .zip-fil som laddas upp till Canvas (som innehåller hela katalogen för projektet), alternativt via länk till eget GitHub repository. Vi kommer lära oss i nästa vecka hur man skapar och laddar upp egna projekt till GitHub.


För att uppnå "Väl Godkänt" är kraven (utöver ovan nämnda krav för Godkänt):


En <img> skall läggas in någonstans på hemsidan och vara responsiv. Detta innebär att den formar sig efter den tillgängliga yta som finns. Var på hemsidan den läggs har ingen större betydelse.
Designen måste vara skriven i en CSS-fil per HTML-fil (index.css, experience.css och contact.css). Utöver detta så skall CSS vara uppdelad ytterligare per funktion som delas mellan de tre sidor som du byggt. Funktioner som skall finnas uppdelade i separata filer är typography, forms och colors. Namngivning av dessa filer är upp till dig, men det viktiga är att CSS som berör given funktion är skriven i den specifika filen (font-size, line-height och font-weight hör hemma i typography, exempelvis). En process för detta skulle kunna vara att skriva CSS för typografi för respektive sida (index.css, experience.css och contact.css), och sedan flytta ut denna styling till den s.k. "delade CSS-filen" när du ser att du börjar repetera dig i vad du skriver (dvs. skriv först identisk CSS för olika sidor endast, och när du märker att font-styling börjar användas på mer än en sida, skapa då typography.css för att undvika repetition). På så sätt introducerar du endast fler filer när det anses "behövas". Denna process används i regel i större projekt för att underlätta framtida arbete, något som är väldigt bra att lära sig nu.
Formuläret på sidan contact.html skall ha sina fält required, vilket innebär att det ej går att submitta formuläret utan att ha fyllt i dem korrekt.
Övriga mål (ej krav) som kan vara intressanta att tackla:

Använd Grid eller Flexbox för att skapa en responsiv layout. Den ska se bra ut på alla ovan nämnda skärmstorlekar utan att du använder media queries. Tekniker är inbyggda i dessa layout-teknologier för att göra detta möjligt (framtiden av webben handlar även mycket om att kunna bygga responsiva hemsidor utan att använda sig av media queries).
Tänk på att använda semantisk HTML när ni bygger ert projekt :)

OBS: Tekniker som introduceras nästa vecka (vilken är vår sista vecka innan introduktionen av JS) är inte ett måste, men ni får gärna lov att använda dem i projektet.

Lite länkar för inspiration:

För layouter kan ni titta på https://dribbble.com/search/portfolio (Länkar till en externa sida.).
För att generera färger som passar tillsammans: https://mycolor.space/ (Länkar till en externa sida.) eller https://coolors.co/ (Länkar till en externa sida.)
För att hitta en custom font: https://fonts.google.com/ (Länkar till en externa sida.).
För gratis bilder: https://unsplash.com/ (Länkar till en externa sida.)
Gratis ikoner på https://fontawesome.com/ (Länkar till en externa sida.) och https://heroicons.com/ (Länkar till en externa sida.)
Min egen lösning till Kunskapskontrollen: 

Inspiration från https://dribbble.com/shots/15473091-MoonexLab-Digital-Agency-Index (Länkar till en externa sida.)
Koden för lösningen kommer göras tillgänglig först efter inlämning
Min lösning innehåller en del “socker” som introduceras nästa vecka. Dessa inkluderar bl. a: background-image, pseudoklasser (hover, focus), css variabler, custom google font, transforms, transitions, inheritance, relative CSS units (em, rem, vh).
