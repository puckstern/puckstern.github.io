---
layout: post
title:  "Reflection Exam 1"
date:   2016-11-16 21:15:19
---
<p>Jag tycker att det är roligare och mer effektivt att arbete med CSS-preprocessors.
Frågan avsedde pre-compilators, men då de ibland anses vara samma sak valde jag att tolka frågan som vad jag
tyckte om arbetet jag gjort nu. Jag har använt mig av SASS/ scss, dels för att Github + scss = sant, och dels för
att jag har jobbat lite med scss förut. Jag har i den här uppgiften inte använt mig av några mixins eller funktioner,
men lite variabler och enklare uträkningar on the fly. Jag tycker att scss är lättare att hålla koll på än vanlig css,
i och med att en kan dela upp det på ett helt annat sätt. Då det oftast är rätt dåligt ur prestanda-synpunkt att ha
många http-anrop, och onödigt/ tidskrävande att hålla kolla så att alla css-filer kommer med i headen, så fyller (bl.a.) 
scss en viktig funktion där - genom att kompilera ihop alla scss filer till en, göra den kompilerade filen till en 
vanlig css och först efter det skicka iväg reglerna. Jag anser att detta bidrar till ett bättre arbetsflöde. </p>

<p>Jo, förstås blir det ytterligare en grej att lära sig - men så är det ju alltid. För att kunna utvecklas inom sitt
område krävs ny kunskap, och när en besitter den blir arbetet oftast/ i bästa fall snabbare och effektivare - vilket
jag tycker att det blir med CSS-prekompilatorer. Återanvändandet och dupliceringen av regler gör att en kan göra stora
genom att ändra på enbart ett par ställen. En nackdel kan väl tänkas att en verkligen behöver hålla koll på var en 
har använt en variabel, så en inte omedvetet ändrar på fel ställe. </p>

<p>När det kommer till SSG - statiska sitegeneratorer fyller de absolut en funktion inom sitt område. För stora webbsidor, med
mycket dynamiskt innehåll - t.ex. IKEA's hemsida - så skulle jag inte säga att det passar. Där krävs en annan typ av 
struktur helt enkelt. Men för mindre projekt så som detta, en portfoli, en blogg, enklare webbsidor - så tycker jag att
det passar bra. Jag gillar att det är lätt att få en sammanhängande struktur, och att en inte behöver ändra på så många
olika ställen.</p>

<p>Robot.txt: Detta var helt nytt för mig fram tills denna uppgift. Jag skulle säga att det är en fil som talar ger de
webrobotar som kommer på besök en snabb karta över webbsidan. Vilka sidor vi vill att de ska besöka och inte - som en 
riktlinje typ. Det underlättar för den att veta vad den ska titta på för att få fram t.ex. ett relevant sökresultat. 
Det ger mig som sidägare möjlighet att peka på specifika filer. I den här uppgiften har jag valt att säga åt alla 
robotar att de inte ska gå in här. Detta för att det är en ofärdig plats och därför vill jag inte få onödig trafik dit i
dagsläget. Men när den är färdig kommer jag att öppna för alla robotar, och kanske specifikt pusha de filer där det finns
exempel på webbprojekt eller fotografier.</p>

<p>Humans.txt: Humans.txt är en textfil där en skriver information om site-ägarna, författarna, eventuellt företag,
kontaktuppgifter, positioner osv. Men även vilka verktyg som använts, vilket datum sidan blivit uppdaterad och dylikt.
Här skrivs denna typ av information för att slippa skriva ut den på sidan. Det är ett smidigt sätt att skicka med 
identifikation, utan att för den sakens skull låta den ta upp en massa onödig plats på sin sida. Jag har i dagsläget bara 
 tre rader i min humans.txt -> mitt namn, min mailadress och min geografisk plats. Jag anser inte att någonting annat
 är relevant just nu. </p>
 
 <p>Jag använde mig av Disqus för att tillåta kommentarer på mina inlägg. Det gjordes genom att lägga in ett script i mallen
 som används för inlägg. Jag ville även ha en "comment count" på samlingssidan för inläggen, och då krävdes ytterligare 
 ett script. Disqus gjorde det hela enkelt, och det känns som ett tryggt verktyg att använda. Dock fick jag det inte att
fungera när jag körde sidan på github - det fungerar bara lokalt. Jag valde att gå vidare i mitt arbete och tänkte att jag
får komplettera det vid ett senare tillfälle när jag har möjlighet att djupdyka i, vad jag tror kommer lösa det hela,
absoluta URL-er. </p>

<p>Opengraph är ett verktyg som används för att kunna dela sin sida/ sina inlägg på sociala medier på ett snyggt och kontrollerat
sätt. Det ger oss möjligheten att bestämma vad som skickas med, hur det ska se ut och vilken text som ska synas. Det ger
ett proffsigare intryck och ett måste i dagens samhälle. Jag har skickat med titel, sampletext, URL och en samplebild.
</p>
