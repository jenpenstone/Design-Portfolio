---
Title: Om
Description: Presentation av de tekniker som används i sidan.
icon: far fa-lightbulb
---

Om - sidans olika tekniker
==========================

Sidan använder sig av Normalize för att skapa en neutral grund så skillnader i utseende mellan webbläsare motverkas.
De fonter som används är importerade från Googles font-bibliotek och är inte nedladdade utan hämtas direkt från Google.
Webbsidan har även ikoner och dessa importeras från Fontawsome som är installerat och ligger lokalt på webbsidan.

När det gäller CSS så använder sig sidan av en del SASS för att möjliggöra en bättre struktur och mer avancerade typer av design och kod. Variabler används för att sätta en standard för färger och fonter. Dessa kan sedan med enkelhet uppdateras och förändras.

Flex används på flera ställen, t.ex. för att sträcka ut body för att nyttja maximalt med höjd mellan header och footer.
För att skapa en snyggare och bättre navbar för mindre skärmar så används en "hamburger-meny" och möjligheten att med CSS göra objekt dolda med hjälp av "hidden".

För att skapa en snygg effekt runt bilderna så används skuggning med hjälp av box-shadow.
Genom att använda full bredd för flash-bilden samtidigt som den har en begränsning i sin tillåtna höjd så skalar den snyggt mellan större och mindre skärmar på ett responsivt sätt.
