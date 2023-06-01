# Teorihandboken - Programmeringsmetodik (PG)

Studerande: Baqer Al-abedi

## PG 1.1 Versionshantering (Git)

VCS är en enkel databas som innehåller alla de ändringar till filer som hänt under revisionssystemets kontroll. Liten historia om VCS. Det finns 3 generationer inom VCS. Ett system som fanns tidigt blev populärt som heter RCS och utvecklades 80-tal. Denna första version fungerade genom att man lät varje ändring bli en "patch". Denna ändring sparades i disk som har en väldigt speciellt format.

Den andra versionen behövdes, RCS var bra men krävdes att verktygen klarade av att samverka mellan de olika systemen som finns. Eftersom det behövdes ett nytt system som klarade av att samverka mellan varandra så upptäckte man CVS. CVS har en enkel server som har alla de versionhanterade filerna.

Den trejde versionen hämtar inte bara de senaste snapshot av filter. Detta innebär att ifall servern skulle dö så kan vilket system som helst som använde sig av den servern kopiera tillbaka innehållet. Dessa DVCSer består bland annat git. Git är som en gemensam ansträngning av BitKeeper och Linux communityn. Git skulle kunna hantera stora projekt, vara helt distriberat, ha simpel design och det allra viktigaste att den ska vara snabb.

Git har olika delar, bland annat att den har tre tillstånd, snapshots inte skillnader och har integritet. Med hjälp av den skärskild kod så sparas allt i git och den kallas för SHA, SHA fil är 40 tecken långt. Det är som en nyckel. Använder HEX decimal HEX decimal - värden 0-9 A-F (0123456789ABCDEF) Nummer A3: 10+3 (13) C5 (17). Git har tre tillstånd en Commited som innebär att datan säkert förvarad i den lokala databasen, Stageade som ett sätt att en modifierad fil har markerats att i sin nuvarande version gå in i nästa commit snapshot. Kommandon i git.

<git init> För att skapa ett repo
<git add filename> För att lägga till filer
<git add .> Lägga till alla filer
<git branch> För att se vad som finns för branches
<git branch branchname> För att skapa en branch
<git switch branchname> För att byta till en branch

## PG 1.2 Benchmarking

Benchmarking är en process som innebär att mäta prestanda, effektivitet eller kvalitet hos ett system eller applikationer för att identifera bästa praxis. genom att benchmarka it-relaterade processer kan organisationer få insikt om hur deras miljö presterar jämfört med branchstandarder. Det kan hjälpa att identifera flaskhalsar och möjligheter till optimering. Man kan använda sig utav olika metoder beroende på vad som ska mätas och jämföras.

1. kostnadbenchmarking - Det är här som kostnaderna och utgifterna jämförs med konkurenterna eller brancshstandarder. Detta metod hjälper organisationen att identifera överdrivna kostnader och innefektiva utgifter.

2. applikations benchmarking - Det innebär att jämföra prestanda och funkonalitet inom olika progarmmerings applikationer inom samma domän.
   Genom att använda sig av denna metod kommer företaget hitta och välja de bästa lösningarna och där efter kunna förbättra användar upplevelsen.

3. prestanda benchmarking - Detta innebär att mäta och jämföra prestanda hos system, nätverk och databaser. genom att analysera faktorer som svarstider, hantering av användarbelastning och tillgänglighet för att kunna optimera systemets kapacitet och effektivitet.

nackdelarna med benchmarking :

1. Tids- och resurskrav: Benchmarking är en tids-
2. Kontextuell relevans: Benchmarkingresultat från andra organisationer kan vara användbara, men de behöver anpassas och tolkas i enlighet med din organisations specifika behov och kontext. Det som fungerar för en annan organisation behöver inte nödvändigtvis fungera för dig, och det kan vara svårt att överföra lärdomar direkt utan att ta hänsyn till unika omständigheter och mål.
3. Konfidentialitet: I benchmarkingprocessen kan det krävas att du delar viss information om din organisation med andra. Det kan vara känslig information som du inte vill eller kan dela av konkurrensskäl eller juridiska skäl. Det är viktigt att noggrant överväga vilken information som delas och att försäkra sig om att adekvata sekretessavtal är på plats för att skydda företagshemligheter.
4. Datakvalitet: För att få tillförlitliga resultat i en benchmarkingprocess krävs korrekt och jämförbar data. Det kan vara utmanande att säkerställa att jämförbara data samlas in och att den är representativ för både din organisation och referensorganisationerna. Om datakvaliteten är bristfällig kan benchmarkingresultaten vara missvisande eller svåra att tolka.

fördelar med benchmarking :

1. Kunskapsöverföring: Genom benchmarking kan du lära dig av andra organisationers framgångar och misstag. Detta ger möjlighet till kunskapsöverföring och att dra nytta av andras erfarenheter. Genom att identifiera bästa praxis och tillämpa dem inom din organisation kan du snabba upp inlärningskurvan och undvika att göra samma misstag som andra.
2. Prestandaförbättringar: Genom att jämföra din organisations IT-prestanda med branschstandarder och bästa praxis kan du identifiera områden där förbättringar kan göras. Detta kan leda till effektivare processer, bättre system och en övergripande förbättring av IT-miljön.
3. Mätning av framsteg: Benchmarking möjliggör en objektiv bedömning av din organisations framsteg över tiden. Genom att regelbundet utföra benchmarking kan du mäta och följa upp förändringar och se om dina insatser har gett önskade resultat. Detta kan vara särskilt användbart för att utvärdera långsiktiga IT-initiativ eller förändringsprojekt.
4. Konkurrensfördel: Genom att benchmarka din IT-miljö mot konkurrenter eller ledande företag inom din bransch kan du identifiera och implementera bästa praxis och innovativa lösningar. Detta kan ge dig en konkurrensfördel genom att förbättra din organisations effektivitet, produktivitet och kundnöjdhet.

## PG 1.3 Testdriven utveckling

Det som kallas Test driven utveckling eller förkorningen TDD som det kallas i kretsarna är en viktig mjukvaruutvecklingsprocessen. Genom att detta sätt kan det bli lättare att testa ett specefikt kod som ska utföras.

I varje projekt även känt som testfall så skapas det en funkonalitet i programvaran och när funkonaliteten misslyckas i sjävaste testet skulle det isånnafall betyda att koden omarbetas och skapar en ny kod. Det gäller även för den nya koden att den ska klara testet och vara buggfri. TDD handlar om att designa och utveckla tester för varje funktion i applikationen.

Processen för TDD handlar om att skriva en test först och om testet misslyckas så gör man sedan ett par eller flera ändringar i koden. Detta hjälper också till att undvika debblering av kod. För att testdriven utveckling ska fungera så är det lämpligaste att skriva fallen till simplare fall.

Fördelar med TDD:

1. Ökad kodkvalitet: TDD främjar skrivandet av ren och modulär kod genom att testerna skrivs innan koden implementeras. Detta leder till mindre buggar och en mer robust programvara.

2. Förbättrad design: TDD uppmuntrar till att skapa välstrukturerade och löst kopplade system genom att testerna tvingar utvecklaren att tänka på gränssnitt och ansvarsområden innan koden skrivs.

3. Snabbare feedback: Genom att skriva testerna först får utvecklaren omedelbar feedback om koden fungerar som avsett. Detta möjliggör snabb upptäckt och åtgärd av eventuella fel.

4. Ökad produktivitet: TDD kan hjälpa till att eliminera "återgångsloopar" genom att fånga fel tidigt. Det sparar tid som annars skulle ha lagts på felsökning och testning i senare skeden av utvecklingsprocessen.

5. Bättre underhållbarhet: Genom att ha omfattande testsviter kan utvecklare enkelt verifiera att ändringar eller uppdateringar inte har orsakat oavsiktliga buggar eller brytit befintlig funktionalitet. Detta gör underhåll och vidareutveckling av systemet mer hanterbart.

Nackdelar med TDD:

1. Inledande inlärningskurva: TDD kan vara svårt att bemästra för utvecklare som inte är vana vid att skriva tester först. Det kan ta tid att lära sig den nödvändiga tankeprocessen och teknikerna för att effektivt implementera TDD.

2. Ökad initial tidsinvestering: Att skriva tester först innebär att utvecklaren behöver lägga extra tid på att skapa och underhålla testsviter. Detta kan innebära en initial tidsinvestering som kan uppfattas som negativ.

3. Överdrivet fokus på testbarhet: Ibland kan utvecklare överprioritera testbarhet och skapa onödigt komplex kodstruktur för att kunna testa varje enskild del. Detta kan påverka kodens läsbarhet och underhållbarhet.

4. Risk för bristande testtäckning: Det är möjligt att utvecklare fokuserar för mycket på att skriva kod för att uppfylla testkraven, men utan att tillräckligt täcka alla scenarier. Det kan leda till ofullständig testning och missade buggar.

5. Svårt att tillämpa på vissa typer av projekt: TDD kan vara mindre lämpligt för projekt där kraven och specifikationerna ändras mycket frekvent eller för projekt som är svåra att testa automatiskt, till exempel projekt med mycket grafiskt användargränssnitt eller

## PG 1.4 Deploy och staging

Deploy:
Deploy (distribution) hänvisar till processen att ta en färdigbyggd applikation och göra den tillgänglig för användare. Det innebär att ta den kod och konfiguration som utvecklats och installera den på en server eller plattform där den kan köras och användas. Deployment kan vara en automatiserad process som sker vid varje uppdatering av applikationen eller manuell process som görs vid behov.

Fördelar med deploy:

Snabbare leverans: Genom att automatisera deployments kan du snabbt och effektivt leverera nya funktioner och uppdateringar till användare.

Bättre skalbarhet: Deploymentprocesser kan vara utformade för att enkelt hantera ökade användarbelastningar och skalning av infrastrukturen efter behov.

Enklare felsökning: Genom att ha en tydlig process för deployment blir det lättare att isolera och åtgärda eventuella fel som uppstår efter att applikationen har distribuerats.

Kontinuerlig förbättring: Genom att ständigt distribuera uppdateringar och förbättringar kan du snabbt iterera och anpassa din applikation baserat på användarfeedback och behov.

Nackdelar med deploy:

Risk för fel: Om deployments inte utförs korrekt kan det leda till instabilitet, buggar eller driftstörningar i applikationen.

Ökad komplexitet: Att implementera och underhålla en effektiv deploymentprocess kan vara komplicerat och kräva tekniska resurser och expertis.

Beroende av infrastruktur: Deployment kräver en stabil och pålitlig infrastruktur för att applikationen ska kunna köra smidigt. Problem med infrastrukturen kan påverka tillgängligheten och prestandan hos den distribuerade applikationen.

Versionshantering: Att hantera flera versioner av applikationen kan vara utmanande, särskilt när det gäller att koordinera användares övergång till nya versioner och hantera bakåtkompatibilitet.

Staging:
Staging (etableringsmiljö) är en miljö där en applikation körs och testas innan den deployas till produktionsmiljön. Stagingmiljön replikerar så nära som möjligt produktionsmiljön, inklusive konfiguration och data, för att säkerställa att applikationen fungerar korrekt och testas i en mer realistisk miljö innan den blir tillgänglig för användare.

Fördelar med staging:

Minskad risk: Genom att testa applikationen i en stagingmiljö kan du upptäcka och åtgärda potentiella problem och fel innan de påverkar produktionsmiljön och användare.

Bättre kvalitetskontroll: Staging ger utvecklare och testare möjlighet att utföra grundliga tester och verifiera att applikationen fungerar korrekt och möter kvalitetsstandarder innan den går live.

Användartestning: Stagingmiljön kan användas för att involvera användare eller kunder i tester och användarupplevelseutvärderingar innan en deployment till produktionsmiljön.

Säkrare uppgraderingar: Genom att använda stagingmiljön kan du testa och validera uppgraderingar och förändringar innan de implementeras i produktion, vilket minskar risken för oväntade problem.

Nackdelar med staging:

Ökad komplexitet: Att ha en separat stagingmiljö kräver extra resurser och underhåll, inklusive infrastruktur och konfiguration.

Tids- och resurskrävande: Att duplicera och underhålla en stagingmiljö kan vara tids- och resurskrävande för utvecklingsteamet.

Risk för inkonsekvens: Om stagingmiljön inte korrekt replikerar produktionsmiljön kan det finnas risk för att problem upptäcks först när applikationen går live.

Kostnad: Att ha en separat stagingmiljö kan medföra extra kostnader för infrastruktur, underhåll och resurser.

Det är viktigt att anpassa deploy- och stagingprocessen efter specifika behov och krav för varje projekt och organisation.

## PG 1.5 Debugging

vad är debugging och varför ska jag kunna det?
utvecklare arbetar med information, vi flyttar det, redigerar det och skickar det till ställen som man senare tar emot igen. Buggar är vanlig i mjukvaruutveckling eftersom det är konceptuell och abstarkt aktivitet.

programmering kan vara en mycket känslig aktivitet och det är lätt att tappa siktet som vad som händer. Detta leder till att man kan ge fel kod eller instruktioner till datorn vilket leder till att man missar det man letar efter. som utvecklare kommer man alltid lägga otroligt många timmar på att felsöka kod och lösa problem. Det borde kallas probleming istället för programmering nästan. Därför måste man bli bättre och snabbare på att identifera problem och det är därför debugging hjälper oss.

I nästan alla utvecklingsmiljöer, om din kod misslyckas, kommer du sannolikt att få ett felmeddelande som (till viss del) förklarar varför din kod misslyckas.

Ta den här koden till exempel:

"Från webben" //

mickTheBug('Im a scary bug!')

const mickTheBug = message => console.log(message)
Denna kod ger följande fel:

ReferenceError: Cannot access 'mickTheBug' before initialization
at Object.<anonymous> (/home/German/Desktop/ger/code/projects/test.js:4:1)
//

## PG 1.6 Dokumentation

När vi skriver och dokumenterar så beskriver tankar, och situationer men även för att följa, utvärdera samt utveckla självaste "uppdraget" som man gör. Vi har haft nu en del grupp arbeten och då hjälper det oss att dokumentera vad vi gör under daily scrum möten samt hur vi ska gå vidare och lösa problem. Jag skulle säga att backlog är också en del av dokumentationen eftersom det visar vad personerna i gruppen eller vad som behöver göras för att bli klar med uppgiften. Man bryter ner uppgiften i olika delar för att det går snabbare och man ej behöver ha många bollar i luften.

Dokumentation har hjälp oss en hel del i denna utbildning. Allt från laravels dokumentation till react och alla andra framework som vi använder oss av. Dokumentationen har bra struktur och beskriver samt visar oss hur vi ska gå tillväga med koden eller reglerna. Jag gillar dokumentationen eftersom den visar en hel del kod exempel som man kan använda och göra om eller att man får en hum om hur koden ska ske ut och vad som man behöver göra samt utveckla för att kunna lösa problemet.

Det som även är bra med dokumentation är till exempel laravels API dokumentation som visar oss hur vi ska gå tillväga på controllers och använda oss av de API:erna.

Det kan även finnas några nackdelar med dokumentation, Här är några delar som är dåliga med tex laravels dokumentation

Otydlighet eller brist på exempel: Ibland kan dokumentationen vara otydlig eller sakna tillräckligt med exempel för att förklara vissa koncept eller funktioner. Detta kan göra det svårt för nybörjare att förstå och tillämpa vissa delar av ramverket.

Uppdateringsfördröjning: Laravel är ett aktivt utvecklat ramverk, och det släpps regelbundet uppdateringar och förbättringar. Ibland kan dokumentationen vara något föråldrad och inte helt uppdaterad med de senaste funktionerna och ändringarna. Det kan leda till förvirring för utvecklare som använder den senaste versionen av Laravel.

## PG 1.7 Struktur av kod i projekt

En strukturerad kod har en stor betydelse för hur framgången kommer vara i ett programutvecklingsprojekt. Det spelar inte riktigt roll hur stor eller litet projektet är så spelar kodens struktur en stor roll för att uppnå fördelar. När det uppstår problem eller buggar i koden är det lättare att felsöka och avhjälpa dem av koden.

Genom att ha en tydlig struktur kan du skapa kod som är användarbar för andra, Om du delar din kod i olika funktioner eller klasser som utför upggifter kan du använda dig av samma kod igen i olika andra delar av projektet men tillochmed använda det i andra projket som du kanske kommer hålla på med i framtiden.

En välstrukturerad kod underlättar även samarbetet mellan flera, ett exempel är just nu i u08. Våran kod är väl strukturerad och vi lämnar det väl strukturerat eller åtminstonde lagt en kommentar så att ifall en annan person ska ta över så förstår man vad man ska bygga på eller utveckla.

En strukturerad kod gör det även lättare att läsa och förstå koden som jag skrev högre upp. Genom att ha tydliga namn samt att dela upp koden i logiska delar kan en annan person i gruppen ta över och snabbt förstå vad koden gör. Detta är extremt viktigt när man är flera personer i gruppen.

Det blir även lättare att åtgärda buggar som kan finnas i koden men även att det blir lättare att testa kodens eventuella problem som kan uppstå. Man kan även göra förbättringar.

## PG 1.8 Automatisering av arbetsflöde

Beskriv rubriken här

## PG 1.9 Virtualisering av utvecklingsmiljö

Beskriv rubriken här

## PG 1.10 Bundeling-verktyg

Beskriv rubriken här

## PG 1.11 Terminalinterface

Terminalen kan verka svår att komma igång med ger den dig därmed många möjligheter som grafiska gränssnitt helt enkelt inte kan erbjuda. Terminalen är en gränssnitt som styrs via kommandon du skriver in. till skillnad från grafiska gränssnitt så låter terminalen dig enkelt använda och till och med exekvera egen kod.  
Fördelen med terminalen är att den helt enkelt fungerar. Med hjälp av terminalen redigera textfiler på datorer som är uppkopplade till ett nätverk, Skapa mappar, filer, se din nuvarande plats och se innehåll i mappen.

Terminal är en sorts CLI. CLI eller kommandoradgränssnitt som det kallas på svenska är ett textbaserat användargränssnitt för att hantera datafiler och interagera med datorn. Det vi använder normal sätt för att göra filer kallas GUI (Grafisk användargränssnitt). Ett GUI visar objekt som förmedlar informartion och representerar åtgärder som kan vidtas av användaren. Man kan även använda GUI objekt genom att inkludera knappar, markörer och ikoner. Exempel på GUI i operativsystem är Microsoft Windows, MacOS och linux varianter.
Terminal kommandon som vi har lärt oss och vad de gör är bland annat.

<PWD> Se nuvarande plats
<ls> se innehåll i mappen
<cd> gå till annan mapp
<mkdir> skapa mapp
<mv> flytta och döpa om
<rm> ta bort
<touch> pinga fil

kÄLLOR:
KÄLLA:https://www.software-developer-india.com/sv/vad-ar-testdriven-utveckling-eller-tdd/
KÄLLA: SEBBES LEKTION (git)
KÄLLA: SEBBES LEKTION (terminalinterface)
källa: https://www.bmc.com/blogs/it-benchmarking-metrics/
källa: https://en.wikipedia.org/wiki/Deployment_environment
källa: https://www.techtarget.com/searchsoftwarequality/definition/staging-environment
källa:https://www.freecodecamp.org/news/what-is-debugging-how-to-debug-code/#howdebuggingstarted
källa: https://en.wikipedia.org/wiki/Debugging
källa: https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Tools_and_setup/What_are_browser_developer_tools
