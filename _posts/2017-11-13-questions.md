---
layout: post
date: 2017-11-13 19:01:54 -0600
author: Anton Öberg
---

Vad tycker du om att förkompilera din CSS? 

Till skillnad mot hur vi har gjort tidigare i webteknik kursen så är detta ett mer effekttivt sett att skriva CSS. Genom att ha en uppdelad struktur så fördelar man den CSS kod som är relevant med varandra och anknyter dem med varandra. Precis som vi lärt oss i javascript med att dela upp relevant kod i olika filer så är detta samma princip. Fördelarna med denna struktur är att det blir lättare att hitta vad det är man vill ändra på och det underlättar hela arbetet med att underhålla. Eftersom att detta är nytt samt att det inte är vi själva som strukturerat upp det så har det vart en utmaning att förstå sig på det hela men när man väl bekantat sig med det så bler det mer klart.

Vilka tekniker har du använt? 

I den här examinationen har vi använt variabler i CSS

För och nackdelar? Fördelar: 

Mindre CSS-kod, ingen upprepning, organiserad CSS med separata filer (som tidigare nämnt). Nackdelar: svårare att debugga koden då linjenumren i browsen inte stämmer med källan, mer komplext med mer verktyg etc.

Vad tycker du om static site generators? 

Beror på sammanhanget, men i det här fallet när man gör en “blogg” funkar det utmärkt medan Facebook som har ett gående flöde där man slipper uppdatera själv utan det görs av sig själv med bakgrundsaktivitet osv. Statiska hemsidor är mindre komplexa och därför enklare att programmera för. Eftersom det enda jag kan i dagsläget är statiska hemsidor tycker jag det är jättebra. En nackdel kan vara är om man vill ändra något litet då man måste ändra i alla filer och då kan man lätt missa detaljer.

Vilka projekt är det bra att använda till? 

Hemsidor som ska ha samma design med en global navigering, då undviker man som tidigare sagt att man slipper upprepa sig. Då många av dagens webbsidor har global navigering samt gemensam headerbild och liknande skulle jag vilja påstå majoriteten av webbsidor är static site generators bra.

Vad är robots.txt och hur har du konfigurerat det för din webbplats? 

I grund och botten är robots.txt en textfil som är placerad i ens webbserver. I filen talar man om vilka sökmotorer som är välkomna på sajten eller inte. Jag konfigurerade robots.txt genom att lägga den i en fri textfil i src med vilka sökmotorer jag ville skulle komma igenom. I detta fall är det bara Google.

Vad är humans.txt och hur har du konfigurerat det för din webbplats? E

tt sätt att få reda/”känna” människorna bakom en webbplats. Samma som robots.txt är det en textfil som läggs direkt i src som innehåller information om de olika personerna alternativt personen som bidragit till att bygga och konstruera webbplatsen.

Hur har du lagt till kommentarer på dina blogginlägg? 

Med hjälp av hemsidan Disqus som man blev hänvisad via examinationssidan. Jag la in ett kopierat stycke från Disqus in i src/_layouts/post.html. Samt i alla ”bloggpostinlägg” (alla inlägg som finns i “_posts” skriver jag comments: true om jag vill att kommentarsfunktionen ska fungera på just det inlägget. Alternativt skriver man comments: false om man inte vill att besökarna ska kunna kommentera.

Vad är Open Graph och hur använder du det? 

Open Graph är en teknik som infördes av Facebook 2010 som tillåter samt möjliggör en intergration mellan Facebook, dess användardata och en webbplats. (Delning av url, type, image etc på sociala medier, i det här fallet Facebook). Genom att integrera webbsidans metataggar kan man även bestämma vilka delar av sidan som ska visas.ad tycker du om att förkompilera din CSS? Jämfört med vanlig CSS? Det innebär att man har CSS i olika filer och det gör ju så att man delar upp allt och min åsikt är det om man kan verktygen och hur det fungerar korrekt är det ett bättre sätt att jobba på jämfört med ”vanlig” CSS då man lägger all CSS-kod i en enda CSS-fil. Med hjälp av flera CSS-filer kan man på ett enklare sätt göra mer detaljerade sidor med underlättning av fördelningen. Då vi inte jobbat med den här typen av CSS tidigare var det lite svårt att komma igång, men det blev enklare när man väl kommit in i det.

