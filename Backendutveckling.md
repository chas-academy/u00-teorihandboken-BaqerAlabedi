# Teorihandboken - Backendutveckling (BE)

Studerande: Baqer Al-abedi

## BE 1.1 PHP

PHP: HYPERTEXT PREPROCESSER är ett utbrett skriptspråk med öppen källkod som används på backend i en webbapplikation.

Den (php) är kraftfull och kärnan i tillexempel wordpress som är en stort bloggsystem. Den (php) driver även flera stora nätverksapplikationer som är lätt för personer som är nybörjare och är villiga att lära sig. Med php kan man mata ut pdf filer och biler även vilken text som helst som tillexempel XML och XHTML.

PHP filer kan innehålla text css, javascript, html och php. Självaste php koden exekveras på servern och gör så att resultatet returneras till webbläsaren som vanlig html. Filerna har tillägget .php

Fördelarna med php är:

1. php är gratis och kan laddas ner från webben som är www.php.net
2. den är kompatibelt med nästan alla servrar som används idad så som tex iis och apache med mera...
3. php är väldigt lätt att lära sig och den körs mycket effektivt i backenden.
4. php stöder ett mycket bredare utbud av olika databaser som man kan använda sig av
5. Den kan köras på flera olika plattformar så som linux, unix, mac os samt windows. Man kan säga att den kan köras på majoriteten av plattformarna som människorna har.

nackdelarna med php är:

1. Brist på bra verktyg och utvecklingsmiljöer: Jämfört med vissa andra språk och ramverk har PHP ett mindre utbud av kraftfulla verktyg och utvecklingsmiljöer. Detta kan påverka produktiviteten och effektiviteten hos utvecklare som arbetar med PHP.
2. Löst typsystem: PHP använder ett löst typsystem, vilket kan leda till oväntade beteenden och svårigheter att upptäcka fel i koden. Detta kan öka risken för buggar och säkerhetsproblem.
3. Brister i standardbiblioteket: PHP:s standardbibliotek kan vara inkonsekvent och sakna vissa funktioner som andra moderna språk erbjuder. Detta kan leda till att utvecklare måste lita på externa bibliotek eller implementera funktioner själva.
4. Legacy-kod: PHP har funnits i många år och har en stor mängd legacy-kod. Detta kan göra det svårt att underhålla och vidareutveckla äldre PHP-applikationer.
5. Skrymmande syntax: PHP:s syntax kan upplevas som skrymmande och rörig jämfört med andra moderna språk. Det kan ta tid att vänja sig vid och kan vara svårare att läsa och underhålla för vissa utvecklare.
6. Sårbarheter och säkerhetsproblem: PHP har haft en historia av säkerhetsproblem och sårbarheter, delvis på grund av dess långa historia och stora användarbas. Det är viktigt att vara medveten om säkerhetsaspekterna och vidta åtgärder för att skydda PHP-applikationer.
7. Fragmenterad community: PHP har en stor och fragmenterad community, vilket kan göra det svårt att hitta enhetliga och pålitliga resurser för att lära sig och lösa problem.
8. Svag hantering av fel och undantag: PHP har traditionellt haft svag hantering av fel och undantag, vilket kan göra det svårt att upptäcka och hantera felaktigt beteende i programmet.
9. Brist på strikt standard: PHP har länge lidit av en brist på strikt standardisering och konsistens. Detta har lett till olika versioner och implementationer, vilket kan skapa kompatibilitetsproblem och förvirring för utvecklare.
10. Prestandaproblem: PHP är inte känt för att vara det snabbaste språket när det gäller prestanda. För tunga och komplexa applikationer kan PHP visa sig vara mindre effektivt jämfört med andra språk och ramverk.

PHP kan användas för att generera dynamiska webbsidor. PHP kan även skapa, öppna, läsa, skriva, ta bort och stänga filer på servern. Utöver detta kan PHP även samla in formulärdata, skicka och ta emot "cookies", hantera databaser (lägga till, ändra och ta bort data) samt utifrån ett säkerhetsperspektiv kontrollera och administrera användar åtkomst och kryptering av data.

Hur är PHP uppbyggt och funktionalitet? PHP-filer kan innehålla text, HTML, CSS, Javascript och PHP. PHP-kod exekveras på servern och resultatet returneras till webbläsaren som vanlig HTML. PHP-filer har tillägget ".php".

Utseende PHP skrivs mellan specifika PHP-tags som ser ut på följande sätt:

## BE 1.2 OOP i PHP

OOP står för objekt-orienterad programmering.

Procedurprogrammering handlar om att skriva procedurer och funktioner som utför operationer på datan, medan objektorienterad programmering handlar om att skapa objekt som kan innehålla både data och funktioner.

Det finns flera fördelar med objektorienterad programmering om man jämför med procedurell programmering.
OOP, klasser och objekt Klasser och objekt är de två huvudsakliga aspekterna av objektorienterad programmering.
En klass kan förklaras som en mall för ett objekt, och ett objekt är en instans av en klass.
När ett enskilt objekt skapas så äver det alla egenskaper och beteenden från klassen, men varje objekt som skapas kan ha olika värden för dessa egenskaper.


OOP är snabbare / och enklare att utföra
OOP ger en tydlig struktur för programmet man utvecklar
Med OOP kan man undvika upprepningar av kod (DRY - don't repeat yourseld), samt är enklare att underhålla och felsöka tack vare dess strukturella uppbyggnad
OOP möjliggör skapandet av återanvändbara applikationer med mindre kod och kortare utvecklingstid
DRY principen Don't repeat yourself principen (DRY) handlar om att minska upprepning av kod. Som utvecklare bör man extrahera de koder som är vanliga för applikationen och placera dem på en enda plats och återanvända dem istället för att upprepa det. Detta kan OOP hjälpa till med.

## BE 1.3 Säkerhet i PHP

Applikationssäkerhet: Hur vi säkrar information och skyddar delar i vår applikation från attacker. Med andra ord applikationens egen säkerhet.
IT-säkerhet: Hur vi skyddar, konfigurerar och ser till att våra system (fysiska och digitala) är säkra.
IT-säkerhet Inom IT-säkerhet talar man oftas om sårbarheter (vulnerabilities). Man syftar då på svagheter eller brister med implementationen eller lösningarna i antingen system eller fysisk hårdvara. Dessa svagheter kan utnyttjas för att få tillgång till systemet där man också kan ställa till oreda eller skada.

Hacking Hacking kan beskrivas som när man försöker ta sig in och få tillgång till ett system. Med andra ord är hacking de handlingar / aktiviteter man utför för att få tillgång till och kompromettera digitala enheter och nätverk. Hacking är även ett gammalt svenskt uttryck för allmän datavetenskap / programmering (brukas oftast de som lärde sig programmering för ca 20 år sedan).

Det finns olika tillvägagångssätt för hacking:

Virus - Skadligkod som tagit sig in i datorns system som tillexempel trojaner eller ransomware.

Maskar - En mask är ett slags virus som kopierar- och sprider sig själv vidare till andra datorer genom till exempel e-post.

Varför vill man hacka?

Pengar är en bra anledning och ett starkt motiv för att hacka andra människor. Vissa kan göra detta för att "busa" och "jävlas" med andra. Det finns även olika hacker communities som till exempel Anonymous som har sina egna agendor och strukturer. Det kan även användas för olika typer av spionage och används både av olika statliga säkerhetstjänster och privata aktörer för att få fördelar i en värld där information är en allt mer eftertraktad valuta.

Applikationssäkerhet

I applikationskitet behöver utvecklare ha koll på sårbarheter i applikationen som utvecklas. Genom att hantera dessa sårbarheter minskar man risken för att applikationen går att hacka. Man kan läsa mer om de 10 vanligaste sårbarheterna genom att titta på OWASP (open web application security project).

Några av dem som brukar vara högt upp på listan är:

Injecering - en brist där opålitliga kommandon kan skickas med i t.ex. SQL-queries (SQL-injektioner) och utföra skadliga operationer.
Bruten autensering - när en applikations autenseringsflöde är brutet kan användaruppgifter och annan känslig information komprometteras.
Exponering av känslig data - När APIer inte skyddar känslig data på ett korrekt sätt. Detta kan kompromettera personliga användaruppgifter.
Om säkerheten brister inom dessa områden kan hackare komma åt känslig användarinformation som t.ex. namn, efternamn, adress, lösenord och kreditkortsuppgifter.

XXE (XML-Exteral Enteties) - När äldre versioner av XML-tolknngsmjukvara oavkortat läser externa referenser. Dessa externa referenser kan användas för att lista interna filer på disk, öppna portar och för att köra egen kod på servern.

Felaktig säkerhetskonfiguration - Den vanligaste förekommande bristen. Uppstår när en konfiguration för t.ex. system, ramverk, eller bibliotek saknar korrekt konfiguration för att kunna användas säkret i produktionsmiljö. Detta är extremt lätt att misslyckas med om man inte kontinuerligt jobbar med detta.

Otillräcklig loggning och övervakning - När loggar och övervakning är bristande eller saknas kan attacker fortsätta obemärkt och på sikt lyckas manipulera, få ut eller ta bort data. De flesta studier visar att det tar över 200 dagar för att upptäcka ett intrång. Vilket ofta upptäcks av en extern part, snarare än internt.

En framgångsrik inställning är att se användardata som potentiellt skadlig och på olika sätt skydda sig mot detta. I förlängningen innebär även detta att även sparad data från databasen potentiellt kan vara skadlig då denna kommer från användare. Man bör därför överväga detta tankesätt när man utvecklar en applikation för att göra denna så säker som möjligt.

Ett sätt att skydda sig mot skadlig användarinput (även kallat injektioner) kan vara att använda sig av funktionerna htmlspecialchars() och strip_tags() i PHP. Dessa funktioner saniterar inputen då den inte tillåter html specifika symboler (t.ex. & " ' < >), vilket förhindrar användare från att skicka in direkt skadliga skript i databasen.

## BE 1.4 MVC

MVC är generellt ett sätt att tänka när man strukturerar sin kod och som kan implementeras med alla språk som visar för, tar emot data från och sparar data åt en användare i en databas.

Vad är MVC och varför bör man använda det?

För att kunna veta vad MVC är och varför vi behöver det kan vi börja med att tänka på vad vi vill att våra applikationer ska göra.

MVC står för "Model View Controller" och representerar den arkitektur utvecklare implementerar när de utvecklar applikationer. När MVC arkitektur implemmenteras tar man hänsyn till strukturen av applikationens dataflöde och används när man arbetar med user interfaces, data och controllers. Det separerar även en applikations logiska del och det som hanterar det som visas på skärmen. Uppdelningen underlättar underhåll av applikationen.

Uppdelningen ser oftast ut på följande sätt:

Model - Hanterar data och logik
View - Hanterar layout och skärmrelaterat innehåll
Controller (och routes) - Hanterar requests och "route commands" för modellen och vyerna
Server illustration

När man arbetar med MVC så strävar man även efter att strukturera projektet på ett standardiserat sätt. På så vis kan man organisera sina models, views, routs, controllers och migrations så att det alltid är lätt att hitta det man behöver. Detta underlättar om man ska hoppa in i ett nytt projekt eller om man arbetar i ett större projekt.

Ett återkommande begrepp inom MVC eller programmering generellt är "separation of concerns" och "design patterns" vilket kortfattat syftar på uppdelningen av en applikations olika delar eller lager som beskrivs ovan.

Utöver detta så används MVC för att reducera komplexiteten i koden, förenkla återanvändning av kod, öka flexibiliteten.

## BE 1.5 Wordpress

Wordpress är ett av världens mest enkla och populära innehållshanteringsprogram eller CMS (content managment system). Användning av CSM innebär att skaparen tillhandahåller innehållet medan plattformen / systemet genererar nödvändig kod och organiserar innehållet. Därav är Wordpress ett av de enklaste sätten att skapa en egen webbplats.

Wordpress tillhör "open source" som innebär att plattformens källkod är öppen för alla. Som nämnt används Wordpress för att skapa webbsidor och det är gratis att använda och användare behöver inte betala för licens eller dylikt.

Med Wordpress kan man använda anpassade teman och plugins, webbplatsen som skapas kommer vara annonsfri. Med Wordpress får man även tillgång till en uppsättning analysverktyg.

Wordpress skapades 2003 av Mike Little och Mike Mullenweg. Plattformen är enkel, flexibel och kan användas av vem som helst. Det finns ett flertal kända företag vars webbsidor har skapats med Wordpress så som Sony Music, Variety, Time och Disney med flera.

Fördelar med Wordpress

1. Användargränssnitt och flexibilitet: WordPress erbjuder ett användarvänligt gränssnitt som gör det enkelt att skapa och hantera webbplatser. Det har en intuitiv administrationspanel där användare kan skapa, redigera och publicera innehåll utan att behöva ha djupgående teknisk kunskap. Dessutom är WordPress flexibelt och skalbart, vilket gör det möjligt att skapa allt från enklare bloggar till mer komplexa webbplatser och till och med e-handelsplattformar.

2. Aktiv och stödjande community: WordPress har en stor och engagerad community av utvecklare, användare och supportteam som aktivt bidrar till plattformens tillväxt och utveckling. Det finns många forum, användargrupper och online-resurser där användare kan hitta svar på sina frågor, få support och delta i diskussioner om WordPress-relaterade ämnen.

3. Ständiga uppdateringar och säkerhet: Eftersom WordPress är öppen källkod, är det en aktivt underhållen plattform. Det betyder att det kontinuerligt släpps uppdateringar och säkerhetsförbättringar för att hålla webbplatser säkra och skyddade mot potentiella hot. Det är viktigt att regelbundet uppdatera WordPress-versionen och eventuella teman och plugins för att dra nytta av de senaste förbättringarna och säkerhetspatcharna.

4. SEO-vänligt: WordPress är känt för sin goda sökmotoroptimering (SEO). Plattformen är byggd med ren och semantisk kod, vilket är fördelaktigt för att uppnå bättre sökresultat. Dessutom finns det plugins som specifikt fokuserar på att förbättra SEO-funktionaliteten och hjälper användare att optimera sina webbplatser för att ranka högre i sökmotorer.

5. Stort urval av teman och plugins: WordPress har ett omfattande bibliotek med teman och plugins som ger användare möjlighet att anpassa och utöka funktionaliteten på sina webbplatser. Teman styr utseendet och layouten, medan plugins lägger till extra funktioner och verktyg. Det finns tusentals gratis och premium-teman och plugins tillgängliga, vilket gör det möjligt att skapa unika och professionella webbplatser.

## BE 1.6 Heirarkiska databaser

En hierarkisk databas är en typ av databas som är organiserad i en trädliknande struktur, där varje post eller dataelement är länkat till en eller flera andra poster eller dataelement. I en hierarkisk databas lagras data i en förälder-barn relation, med en överordnad post kopplad till en eller flera underordnade poster. Denna typ av databas används vanligtvis för att representera datarelationer, t. ex. de som finns i organisationscheman eller släktträd.

I en hierarkisk databas är data organiserat i en hierarki av poster, där den översta posten är "root" i hierarkin. Varje post kan ha en eller flera "barn" / relaterade poster som är länkade till "föräldern", det vill säga posten som står över dessa i hierarkin. Detta tillåter en form av representation av datarelationer och ger en effektiv hämtning av data. Hierarkiska databasmodeller är dock inte lika flexibla som andra typer av databasmodeller och är mindre lämpade för för hantering av komplexa datarelationer eller förändring av datastrukturer.

En av de viktigaste egenskaperna med hierarkiska databaser är att de tillåter snabb och effektiv hämtning av data. Detta då datan är organiserad på ett strukturellt och förutsägbart sätt. Dock kan denna typ av databas vara svår att underhålla och uppdatera då ändringar i strukturen kan påverka hela databasen.

Nackdelar med hierarkiska databaser

Begränsad flexibilitet då hierarkiska databaser inte är lämpade för komplexa datarelationer
Svårt att underhålla och uppdatera då ändringar kan påverka hela databasen
Begränsad möjlighet att manipulera data
Begränsad kompatibilitet, hierarkiska databaser är inte kompatibla med andra databasmodeller
Brist på standardisering då hierarkiska databasmodeller inte används lika ofta som övriga databasmodeller

Fördelar med hierarkiska databaser

Snabb och effektiv hämtning av data
Lätt att lägga till / ta bort information
Förutsägbar datastruktur vilket gör det lättare att hitta det man söker
Effektiv lagring av data då datan lagras i en förälder-barn relation
Hög prestanda när det gäller hämtning och sökning, framförallt när det gäller stora datamängder

## BE 1.7 Relationsdatabaser, SQL och ER-modellering

En relationsdatabas är en typ av databas som lagrar och ger åtkomst till datapunkter som är relaterade till varandra. Relationsdatabaser är baserade på en relationsmodell, ett intuitivt och enkelt sätt att presentera data i tabeller. I en relationsdatabas är varje rad i tabellen en post med ett unikt ID som nyckel. Kolumnerna i tabellen innehåller olika attribut av data. Varje post har vanligtvis ett värde per attribut vilket gör det enkelt att upprätta relationer mellan olika dataposter.

Struktur I en relationsdatabas är de logiska datastrukturerna (tabeller, vyer och index) separerade från de fysiska lagringsstrukturerna. Delningen innebär att databasens administratörer kan hantera den fysiska lagringen av data utan att påverka åtkomsten till den logiska strukturen av data. Om man till exempel byter namn på en fil i databasen så byter man inte namn på dess tabeller.

Uppdelningen av logisk och fysisk struktur gäller även databas operationer / åtgärder som möjliggör för applikationer att manipulera data, poster och strukturer i databasen. Logiska operationer tillåter en applikation att specificera innehållet den behöver, och fysiska operationer operationer avgör hur åtkomsten till datan ser ut samt utförandet av själva åtagandet.

För att kunna försäkra sig om att data alltid är korrekt och tillgänglig följer relationsdatabaser en uppsättning säkerhets- / integritetsregler. T.ex. kan en regel vara att dubletter av rader inte får existera för att kunna förebygga att skadlig kod / felaktig information hamnar i databasen.

Relationsdatabasmodellen är en brett vedertagen standard.

Den enkla och kraftfulla relationsmodellen används av alla typer av organisationer av olika storlekar med olika behov av informationstillgänglighet. Dessa databaser används för att lagra affärsprodukter, spåra e-handelstransaktioner, hantera enorma mängder affärskritisk kundinformation med mera.

Relationsdatabaser kan övervägas vid alla olika typer av informationsbehov där datapunkter är relaterade till varandra och kräver säker och konsekvent hantering.

## BE 1.8 OAuth i backend

OAuth är ett auktoriseringsprotokoll eller ramverk med öppen standard som ger applikationer möjligheten till "säker tilldelad åtkomst". Du kan t.ex. ge tillåtelse ESPN.com att komma åt din Facebook profil och skicka uppdateringar till din tidslinje utan att behöva ge ESPN ditt lösenord till ditt Facebook konto. Detta förhindrar att ditt lösenord hamnar i fel händer om ESPN skulle råka ut för ett dataintrång.

OAuth delar inte lösenordsdata men tillhandahåller istället ett "auktoriserings-token" för identifikation mellan konsumenter och tjänsteleverantörer.

OAuth är med andra ord ett autentiseringsprotokoll som ger dig möjligheten att godkänna att en applikation interagerar med en annan för din räkning utan att ge bort ditt lösenord.

Det enklaste sättet att förklara detta skulle kunna vara ett exempel där en webbsida säger "Hej, vill du logga in på våran sida med en annan webbsidas inloggningsuppgifter?". I detta fall så är det enda den första webbsidan (utifrån konsumentens perspektiv) vill klargöra är att användaren (konsumenten) är samma person på båda webbsidorna, och att användaren lyckats logga in på den ursprungliga sidan (en annan tjänsteleverantör som t. ex. Facebook eller Google).

## BE 1.9 HTTP-protokollet

HTTP står för hypertext transfer protocol.

HTTP är ett protokoll för att hämta resurser som HTML dokument. Det är grunden för allt datautbyte på webben och är ett klient-server protokoll, vilket innebär request som skickas har initierats av mottagaren, vanligtvis en webbläsare. Ett mottaget dokument rekonstrueras från olika deldokument som hämtas, t. ex. text, layoutbeskrivning, bilder, videor, skript med mera.

Man kan säga att klienter och servrar kommunicerar genom att utbyta individuella meddelanden istället för en dataström. De meddelanden som skickas av klienten, vanligtvis en webläsare, kallas för förfrågningar och de meddelanden som skickas av servern kallas för svar.

Komponenter Som tidigare nämnt är HTTP ett klient-server protokoll. Förfrågningar skickas av en enhet, användaragenten (eller en proxy på uppdrag av denna). Vanligvis är användaragenten en webbläsare, med det kan vara vad som helst, till exempel en robot som genomsöker webben för att fylla i och underhålla ett sökmotorindex.

Varje enskild förfrågan skickas till en server som hanterar den och returnerar ett svar. Mellan klienten och servern finns det många enheter, gemensamt kallade proxyservrar, som utför olika operationer och fungerar t. ex. som gatewayes eller cachar.

I verkligheten finns det fler komponenter mellan en webbläsare och servern som hanterar begäran så som routrar, modem med mera. Dessa är dock dolda i nätverks- och transportlagret på grund av webbens skiktade design. HTTP är övers i applikationslagret. Även om de är viktiga för att diagnostisera nätverksproblem, är de underliggande lagren för det mesta irrelevanta för beskrivningen av HTTP.

Klientsidan Användaragenten är ett verktyg (vilket som helst) som agerar på uppdrag av användaren. Denna roll spelas oftast av en webbläsare, men kan också spelas av program som utvecklare och ingenjörer använder för att felsöka sina applikationer.

Webbläsaren är alltid den enhet som initierar en förfrågan. Det är aldrig servern, även om det med åren har lagts till vissa mekanismer för att simulera server-initierade meddelanden.

Serversidan På andra sidan av kommunikationen finns servern som serverar dokumentet enligt användarens begäran. En server brukar presenteras som en enda maskin men det kan ofta vara flera maskiner som delar serverns belastning. En server kan även vara en komplex mjukvara som kommunicerar med andra datorer (så som cache, en databas-server eller e-handelsservrar).

En server är inte nödvändigtvis en enda maskin men det kan finnas flera serverprogramvaruinstanser på samma maskin.

## BE 1.10 cURL

cURL är ett terminalverktyg som möjliggör utbyte av data mellan en enhet och en server genom en terminal.

Genom att använda detta CLI (command line interface) så kan en användare ange en specifik server URL (adressen dit de vill skicka en request) och den data de vill skicka till serverns URL.

Till skillnad från andra liknande verktyg för detta ändamål så använder cURL endast terminalen och saknar ett GUI. cURL fungerar på Linux, Mac och Windows.

cURL använder "libcURL client-side URL transfer library" som stödjer många olika "transfer protocols" så som HTTPS, SMTP och FTP. Det erbjuder även en möjlighet att inkludera "cookies", sätta upp proxys och lägga till en auktoriserings metod för olika requests.

cURL kan användas för att testa en API, ladda ner data från olika källor, testa webbsidor och följande "redirects" genom terminalen.

cURL kan kombineras med olika kommandon för att utföra olika uppgifter så som GET, POST, PUT, PATCH och DELETE. För att visa hur detta går till kommer jag ge några exempel på hur ett curl-kommando är uppbyggt.

GET curl -X GET http://localhost:3000/posts

Detta kommandå hämtar all data från databasen på angiven URL. I detta fall databasen på localhost, port 3000, posts.

Denna data kommer därefter skrivas ut i terminalen där vi kan ta del av informationen som finns i posts.

POST curl -X POST -d 'title=hello' -d 'author=Freddo' http://localhost:3000/posts

Detta kommando kommer skapa en ny post i posts med title "hello" och author "Bagge" i databasen på localhost, port 3000, posts.

PUT curl -X -d 'title=hello' -d 'author=Freddo' http://localhost:3000/posts/1

Detta kommando kommer ändra den befintliga posten med id 1 (om vi utgår ifrån att det ursprungligen fanns en post med id 1) till title "hello" och author "Bagge".

Observera att PUT ändrar de parametrar man anger men raderar / skriver över övrig data som eventuellt finns i denna post.

PATCH curl -X PATCH -d 'title=newHello' http://localhost:3000/posts/1

Detta kommando kommer endast ändra title på posten med id 1 (ovanstående post) till "newHello" men övrig data lämnas oförändrad.

DELETE curl -X DELETE http://localhost:3000/posts/1

Detta kommande kommer radera post med id 1 från databasen.

cURL som egentligen uttalas curl är ett mycket enkelt, snabbt och bekvämt sätt att hantera och testa t.ex. ett API och kommer bli en mycket älskvärd kompanjon senare i arbetslivet.

Källa: Föreläsning "Dataformat curl och PHP inlogg" av Sebastian Lindgren den 19 januari 2023

## BE 1.11 REST

Vad är REST? REST är en uppsättning arkitektoniska begränsningar. API-utvecklare kan implementera REST på en mängd olika sätt.

När klienten gör en begäran via ett REST-API överför den en representation av resursens tillstånd till klienten. Denna information, eller representation, kan levereras i något av följande format via HTTP: JSON (Javascript Object Notation), HTML, XLT, Python, PHP eller ren text. JSON är generellt det mest populära alternativet. Detta då det är läsbart för både människor och maskiner.

Utöver detta är "headers" och parametrar något som är viktigt att tänka på när det gäller HTTP metoder avsedda för REST APIer och förfrågningar till dessa. Dessa innehåller information som identifierar vad som efterfrågas, metadata, authorization, URI, caching, cookies med mera. Det finns headers för förfrågningar och för svar, vardera med dess egen HTTP-anslutningsinformation och statuskoder.

Ett REST API (även känt som RESTful API) är ett gränssnitt för applikationsprogrammering (API eller Webb-API) som överensstämmer med restriktionerna för REST arkitekturstil och möjliggör interaktion med RESTful webbtjänster. REST står för representational state transfer och skapades av Roy Fielding.

Vad är ett API? Ett API är en uppsättning definitioner och protokoll för att bygga och interagera applikationsprogramvara och kan beskrivas på flera sätt. Det skulle kunna kallas för ett avtal mellan en informationsleverantör och en informationsanvändare - som upprättar och tillhandahåller det innehåll som krävs av användaren (förfrågan) och det innehåll som krävs av tillhandahålllaren (svaret). Designen av ett API kan t. ex. vara en väderapplikation där användaren anger sin plats och tjänsteleverantören svarar i ett två-delat svar, först den högsta tempraturen sedan den lägsta.

Med andra ord används ett API för när man vill interagera med en dator eller ett system för att hämta information eller utföra en funktion. Likt en kypare i en restaurang som tar beställningar från gäster som sedan ges till kocken som lagar maten, hjälper ett API användaren att kommunicera vad hen vill ha av ett system på ett sätt som systemet kan förstå och således uppfylla begäran.

## BE 1.12 XML och andra dataformat

XML står för extensible markup language och är ett markup språk precis som HTML. XML skapades för att lagra och överföra data och är designat för att vara självbeskrivande.

XML är ett språk som främst används för att strukturera och överföra data mellan olika system och plattformar. Det är plattformsoberoende och kan läsas och tolkas av olika applikationer och programvara. XML-data kan användas för att utbyta information mellan olika webbtjänster, system och databaser.

Men koden i exemplet gör ingenting. Man kan säga att XML är information som slagits in i taggar. Man behöver någon typ av mjukvara för att kunna skicka, motta, lagra eller visa det.

Hur skiljer sig XML från HTML XML och HTML har skapat med olika syften:

XML är skapat bära data med fokus på vad det är för slags data
HTML är skapat för att visa data med fokus på hur det presenteras
XML taggar är inte fördefinierade som HTMLs taggar.
En av XML: s stora fördelar är dess flexibilitet. Till skillnad från HTML, som har fördefinierade taggar för specifika ändamål, kan XML-användare själva definiera sina egna taggar och strukturer för att passa sina specifika behov. Detta gör XML mycket anpassningsbart och kan användas för att representera komplexa datastrukturer och hierarkier.

## BE 1.13 Webbservrar

Ordet webbserver syftar både på själva datorn (hårdvaran) som används för ändamålet och även på det program som sköter innehållet och kommunikationen för tjänsten som servern tillhandahåller.

Men vad innebär detta?

Det finns många olika typer av servrar så som applikations- och webbservrar (samt dess hårdvara), men också databas-servrar, fax-servrar, mail-servrar, spel-servrar med mera.

Hårdvara

I detta avsnitt går vi igenom hårdvarusidan av en webbserver.

Server illustration

Som bilden beskriver finns en dator på ena sidan som skickar en request som går via intern och kommer fram till en webbserver (en fysisk dator konfigurerad som server) som behandlar förfrågan och returnerar ett svar.

En webbserver är egentligen inget annat än en dator som är speciellt anpassad för att och konfigurerad för att hantera många hemsidor. Ofta står dessa hos ett driftbolag som har snabb internetuppkoppling och personal som kan hantera support. En webbserver för ett större ändamål behöver dock betydligt mer plats, RAM-minne och en betydligt starkare processor för att kunna hantera så många requests som möjligt och ge en stabil användarupplevelse.

En webbserver behöver kunna hantera flera anslutningar samtidigt och det dröjer inte länge innan det blir arbetsmässigt blir "tungt" för en webbserver. För att komma runt problem med otillräcklig eller övermålig hårdvara kan man använda sig av "clud" tjänster som är skalbara och utgår ifrån tjänstens behov baserat på antal användare / requests.

Mjukvara

Det som finns på webbservern är mjuvara för att hantera serverns olika uppgifter.

Server illustration

I bilden ovan kan vi se hur servern hanterar en request. En webbserver-applikation är ett program som installeras på en fysiskwebbserver och som ansvarar för hantera anslutningar, tolka frågor och skicka svar till användare. Vanliga exempel på webbserver-applikationer är Apache och Nginx. Dessa kan konfigureras för att stödja olika webbprotokoll så som HTTP och HTTPS, och används för att köra olika typer webbplatser och webb-applikationer.

HTTPd

Det som brukar ligga och ta emot inkommande förfrågningar (requests) är och skicka ut svar (responses) är någon typ av HTTPd program. Detta program körs i bakgrunden och har rollen som server i en klient-server modell och använder sig av HTTP och HTTPS protokollen. Vanliga implementationer av dessa är Apache och Nginx. Ca 70% av alla webbplatser använder Apache.

källor:
Källa: https://www.w3schools.com/php/php_intro.asp
Källa: https://www.w3schools.com/php/php_oop_what_is.asp
Källa: https://databasetown.com/hierarchical-database/
Källa: https://www.oracle.com/database/what-is-a-relational-database/
Källa: https://www.varonis.com/blog/what-is-oauth
Källa: https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview
Källa: https://www.redhat.com/en/topics/api/what-is-a-rest-api
Källa: https://www.w3schools.com/xml/xml_whatis.asp
