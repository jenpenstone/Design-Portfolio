---
Title: Kmom02
Description: Redovisningstext för Kmom02.
---

Kmom02
==========================

<!---Vad tycker du om SASS än så länge?--->
Så här långt så tycker jag att SASS verklar väldigt bra och spännande. Det är en del jag behöver sätta mig in i och prova men jag tror definitivt att det kan möjliggöra helt andra lösningar. CSS koden kan struktureras på ett helt annat sätt och bli mycket enklare att uppdatera och underhålla. Jag behöver bara lära mig ett bra sätt för hur jag ska bygga upp strukturen. Jag har börjat med att använda mig av variabler och ett grundtema som sedan ska kunna anpassas och förändras.


<!---Är du bekant med Node, npm eller npm scripts (t.ex. npm run lint) sedan tidigare? Vad anser du om det?--->
Jag har inte använt mig av Node eller så tidigare men jag har hört talas om det. Dock har jag aldrig läst in mig på vad det faktiskt är för något. Jag tycker det är svårt att ha en åsikt om det så här långt. Det är något jag installerat för att jag ska kunna skapa CSS kod av SCSS. Det fyller sin funktion helt enkelt och jag har inte direkt funderat så mycket mer på det. Det kluriga är alltid att få allt rätt vid installationen men när det väl är gjort så tänker jag sällan mer på det. Det är en hjälp för att ge mig det resultat som jag är ute efter helt enkelt. När det gäller lint så stör jag mig lite på att den klagar på "webkit" rader i stylingen eftersom det inte är något som jag själv kodat utan som var en del av webbsidan från början.


<!---Hur kändes det att kompilera SASS till CSS, var det något du reflekterade över?--->
Att kompilera SASS till CSS kändes simpelt och bra. Första gången var jag noga med att se till att allt var uppsatt rätt så att det skulle lyckas korrekt. I övrigt funderade jag inte så mycket över det. Jag valde att inte sätta någon watch för att köra kompileringen eftersom jag föredrar att kunna bygga på något och sen när jag kommer till en punkt där jag vill testa, själv kunna köra kompileringen. På så vis tycker jag att det blir lättare att se det som nya verioner och backa tillbaka om något inte fungerar. Däremot funderade jag en del på hur jag skulle strukturera koden i de olika filerna och hur importerna fungerar och filerna laddas in i en viss ordning till den slutgiltiga styling-filen.

<!---Kommentera ditt tema, hur kan man beskriva dess design och hade du några planer på “design” när du byggde ditt tema--->
När jag tog fram mitt tema så började jag med att välja ut en passande färgskala. Eftersom det är min portfolio så måste det vara färger som representerar mig som person, och de ska samverka till en bra helhet som är behaglig att titta på.
Jag är en ganska färgstark person så gillar att använda mig av färg och inte köra på för mesigt med grått, marinblått eller vitt. Därefter letade jag upp bilder som passar till temat från min egna bildbank med bilder jag tagit. Jag tyckte glaskonst passade bra eftersom det liksom en portfolio är något konstnärligt och estetiskt. Eftersom jag har mycket färg i sidan så har jag medvetet jobbat med att skapa ett lugn genom en avskalad och stilren layout. Att representera navigationen med både text och bild är något jag lärt mig är bra ur UX-synpunkt eftersom det underlättar för användaren att hitta rätt. De kan antlingen läsa eller tolka symbolen. Fonten för rubrikerna är lite mer utmanande och rolig än för den löpande texten. Detta skapar en mer konstnärlig känsla på sidan samtidigt som texten inte blir svårtläst och jobbig att ta sig igenom. Det genomgående temat för min portfolio blir därmed det konstnärliga.

<!--Valde du att dela upp din kod? Vilka uppdelningar valde du att göra?--->
Jag valde att använda mig av "shared"-mappen som beskrivdes i övningen. Jag använde inte "layout"-filen men "base" innehåller all grundkod för mitt tema med grundramarna. Där finns header, navigation och footer med vilket kommer vara gemensamt för alla sidorna. I "variables" har jag börjat bygga upp med variabler för färg och font som skapar en default för webbsidan.
Sedan använder jag mitt tema "Bubblegum" och dess "style"-fil till att göra alla importer och ändringar av eventuella variabler. Tanken är att ytterligare design som skapas för sidan ska läggas i en separat scss-fil i Bubblegum som importeras i "style". På så vis blir "style" en typ av projektledare som håller i alla trådar och binder samman det till en helhet.

<!---Vilken är din TIL för detta kmom?--->
Mitt TIL för detta Kmom är att jag lärt mig om vilka möjligheter som finns med SASS och jag har börjat att testa på dessa genom variabler och hur dessa kan nyttjas för att kunna ändra färg på sitt tema på ett enkelt sätt. 