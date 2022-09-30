# Teorihandboken - HTML & CSS (HC)
Studerande: Baqer Al-abedi

## HC 1.1 HTML & CSS
Html eller Hyper text markup language är ett märksspråk för hypertext. Med hjälp av tcp/ip (En arkitektur för datakommunikation) och Http så utgör de tillsammans det grundläggande standarden för www (WORLD WIDE WEB).

Lite historia om html och vad som fanns innan den, vi människor försökte redan på 60-talet effektiversa och automatisera vårt arbete med hjälp av datorer. Pga att vi ville utveckla vårt arbete så kom männiksorna på SGML (Standard Generalized Markup) denna "språk" användes för att lagtexter, industri och struktureera upp dokumentation.

Världen var annorlunda på den tiden. Dataskärmarna på den tiden hade fortfarande inte färg. Det såg ut som terminalen vi använer idag, svart bakgrund och grön text. 

Men på 80-talet så hände det grejer, Tim Bernerslee skapade webben. 1989 så kom den första fungerande prototypen, Han var smart och istället för att komma på en helt ny meta-notation så byggde han vidare på frunden som lades av SGML och det var så mina vänner HTML kom till världen som vi ska lära oss.  

Html eller Hyper text markup language är ett märksspråk för hypertext. Med hjälp av tcp/ip (En arkitektur för datakommunikation) och Http så utgör de tillsammans det grundläggande standarden för www (WORLD WIDE WEB). Lite historia om html och vad som fanns innan den, vi människor försökte redan på 60-talet effektiversa och automatisera vårt arbete med hjälp av datorer. Pga att vi ville utveckla vårt arbete så kom männiksorna på SGML (Standard Generalized Markup) denna "språk" användes för att lagtexter, industri och struktureera upp dokumentation. Världen var annorlunda på den tiden. Dataskärmarna på den tiden hade fortfarande inte färg. Det såg ut som terminalen vi använer idag, svart bakgrund och grön text. Men på 80-talet så hände det grejer, Tim Bernerslee skapade webben. 1989 så kom den första fungerande prototypen, Han var smart och istället för att komma på en helt ny meta-notation så byggde han vidare på frunden som lades av SGML och det var så mina vänner HTML kom till världen som vi ska lära oss.  

Html byggdelar, element, taggar, innehåll och attribut
                        element
            ___________________________________
            <h1 id="headline">jag är en rubrik</h1>
h1 är en start tag medans /h1 är en endtag
id="headline" är en attribut        
jag är en rubrik är innehåll

"Attribut" vilket tilldelar taggar ytterligare
värden som i sin tur låter elementet ändra sitt beteende på olika vis för att möta användarens kriterier. 
Själva idén med "innehåll" är att märka upp text i ett dokument vilar lite på att det finns ett innehåll i elementet, men det är inte ett krav.
I HTML är "taggar" det som avgör början och slutet på ett element i markup.De flesta element i HTML har en start och en slut-tagg för att indikera var de börjar och slutar.

Ett "element" i HTML representerar det som man i dokumentet försöker strukturera, eller märka upp, för att ge det semantisk innebörd. (Sebastians anteckningar)

CSS eller Cascading Style Sheets är ett stilmallsspråk som används för att beskriva presentationen av ett dokument skrivet i ett märkningsspråk som html. CSS Skapades år 1996. css är en hörnstensteknik för www tillsammans med JS (Javascript) och html. css används för att definera stilar för dina webbsidor, inklusive design, layout och variationer i visning för olika enheter och skärmstorlekar. Html är inte avsatt för att innehålla taggar för att formatera en webbsida, html skapades för för att beskriva innehållet på en webbsida. En mardröm för webbutvecklare är när taggar som <font> lades till i html 3.2 för att lösa detta problem skapade www css. Css sparar mycket arbete, med en extern stilmallsfil kan du ändra utseendet på en hel webbplats genom att ändra filen som behövs. 

Ett "element" i HTML representerar det som man i dokumentet försöker strukturera, eller märka upp, för att ge det semantisk innebörd.

CSS eller Cascading Style Sheets är ett stilmallsspråk som används för att beskriva presentationen av ett dokument skrivet i ett märkningsspråk som html. CSS Skapades år 1996. css är en hörnstensteknik för www tillsammans med JS (Javascript) och html. css används för att definera stilar för dina webbsidor, inklusive design, layout och variationer i visning för olika enheter och skärmstorlekar. Html är inte avsatt för att innehålla taggar för att formatera en webbsida, html skapades för för att beskriva innehållet på en webbsida. En mardröm för webbutvecklare är när taggar som <font> lades till i html 3.2 för att lösa detta problem skapade www css. Css sparar mycket arbete, med en extern stilmallsfil kan du ändra utseendet på en hel webbplats genom att ändra filen som behövs.

CSS eller Cascading Style Sheets är ett stilmallsspråk som används för att beskriva presentationen av ett dokument skrivet i ett märkningsspråk som html. CSS Skapades år 1996. css är en hörnstensteknik för www tillsammans med JS (Javascript) och html. css används för att definera stilar för dina webbsidor, inklusive design, layout och variationer i visning för olika enheter och skärmstorlekar. Html är inte avsatt för att innehålla taggar för att formatera en webbsida, html skapades för för att beskriva innehållet på en webbsida. En mardröm för webbutvecklare är när taggar som <font> lades till i html 3.2 för att lösa detta problem skapade www css. Css sparar mycket arbete, med en extern stilmallsfil kan du ändra utseendet på en hel webbplats genom att ändra filen som behövs. 
## HC 1.2 Responsiv design
  Inom responsiv webbdesign finns det dels fem aledningar som är viktigt. Men innan vi snackar om de fem viktiga anledningarna ska vi tala om vad responsiv webbdesign är.
 1 förenkla underhåll
 2 kosstnadseffektivitet
 3 flexbilitet
 4 sökmotoropimering
 5 användarupplevelse

 Detta innebär att en hemsida ska anpassas efter vilken enhet och skärmstorlek man använder när man besöker hemsidan.  
 Men varför responsiv design? ja det är enkelt eftersom att det inte räcker längre med att designa för en enhet. Utan att mobil webbtrafiken har gått om datorernas webbtrafik och utgör majoriteten av webbplatsenernas trafik. Det är viktigt med användarupplevelse och just därför kan man inte ge de en sida som är gjord och avsedd för datorn. hälften av dina besökare kommer att potentiellt vara mobilenhet besökare och just därför måste man göra en bra upplevelse. Byggstenarna i responsiv webbdesign är 
 1 css och html
 2 mediafrågor
 3 flytande layout
 4 flexbox layout
 5 hastighet
 6 responsiva bilder

 Flytande layout är en del av modern responsiv design. En flytande layout förlitar sig på dynamiska värden som procentandel av vyports-bredden tex width: 63% eller width:32% denna metod kommer dynamsikt att minska eller öka storlekerna på container-elementen baserad på skärmens storlek. Responsiva bilder är den mest grundläggande upprepringen som följer samma koncept som en flytande layout. En dynamsik enhet avnänds för att styra höjden eller bredden. ett exempel kan var 
 img {
    width: 100%
 }
 
 Hastighet bör vara högsta priotering när man skapar en responsiv design, Din responsiva design får inte fördröja eller blockera sidans första rendering mer än vad det krävs. sidan som laddas på två sekunder har en genomsnitt 9% avvsiningsfrekvens. Det finns sätt att göra dina sidor snabbare tillexempel att optimera dina bilder. 
 En del av layouten är den flytande delen men webbutvecklare känner att det inte är tillräckligt dynamiskt eller flexibelt. Där kommer flexbox in i bilden, flexbox är en css modul som är utformad som ett effektivare sätt att lägga ut flera element, även när storleken på innehållet inuti containern är okänt. Flexbox är också ett kraftfullt sätt att kontrollera layouten i en webbläsare. Den ersätter alltså inline/block modellen.  

## HC 1.3 Tillgänglighet inom webb
Flexibilitet innebär att man kan anpsassa sig efter sina användare och att det finns tillgänglighet till människor med funktionshinder så att de också kan använda webben. Det innebär att människor med funktionshinder kan förstå, uppfatta, navigera, och bidra med information till webben. Det gynnar även människor utan funktionshinder, för att nämna ett exempel så är en av huvudprinciperna för tillgänglighet att konstruera webbplatser och program så att de är flexibla nog att passa flera typer av användarbehov. flexibilitet kan även gynna människor utan funktionshinder, till exempel människor med temporära funktionshinder och långsam internetuppkoppling. Vissa webbplatser idag har tillgänglighetsbarriärer som gör det svårt för många funktionshinder att använda webben. Webben blir allt mer viktigare och en viktig verktyg för alla delar i en människans liv.

 När det kommer till arbete, staten, för företag och utbildning. En av huvudmålen är att se till människor med hinder får samma tillgång till webben och möjligheter att uttnyttja den som alöla andra. Det kan vara ett sätt att göra så att folk med hinder kan få en mer aktiv roll i samhället. Svårt eller lätt det är att göra en webbplats tillgänglig beror på faktorer tex storlek, komplexitet eller innehåll. Det blir mycket lättare att jobba med tillgänglighet om den redan är med i planen för utvecklingen av en ny webbplats. Om man försöker i efterhand att förbättra tillgängligheten blir det svårare. Det finns också vissa initiativ som ARIA och A11Y finns några till men jag kommer snacka just om de två.

A11y listar ut mönster för layout,böcker,checklistor och andra resurser på ett och sammaställe. Det är också en satsning av open-source communityn för att göra tillgänglighetsanpassning för webbsidor och applikationer enklare. ARIA är tillgänglighetattribut i html men även i andra märkspråk. ARIA beskriver också hur semantiken och metadatan kan användas för att göra gränssnitt och dynamiskt innehåll mer tillgängligt. Med hjälp av några verktyg kan vi nå dessa standarder. skärmläsare chromevox, inbyggda skärmläsare. Testning och rapporter för tillgänglighet chrome lighthouse, wave evaulation tool. 
## HC 1.4 Aktuella webbstandarder (gällande och kommande standarder)
Webbstandarder är rekommanditioner från WORLD WIDE WEB consortium. Webbstandarder finns för att visa hur webbbaserat innehåll ska skapas och tolkas. Webbstandarder finns för att säkerställa hållbarheten för information som publicerad på webben och samtidigt göra det möjligt att så många som möjligt har det tillgängligt. webbstandarder har funnits sen webben började utvecklas men det har tagit många år förrens rekommendationerena har uppnåt ett brett stöd i de större webbläsarna. vad man menar med att följa webbstandarder menar man att ens webbsidor
1 är skapat för att fungera i alla webbläsare
2 använder css istället för tabeller för layout
3 har logiskt uppmärkt innehåll
4 använder giltig html eller xhtml
5 följer w3c:s rekommendationer

Det finns massa affärsfördelar med webbstandarder.
när filstorlekarna på webbsidorna minskar vilket ger kortare nedladdningstideer blir det snabbare ladning, stöd för fler plattformar kan anpassas till de medium som används för att tillgodogöra informationen ett exempel på detta är utskrift eller mobiltelefonen. minskade kostnader för utveckling och förvaltning, ifall man följer webbstandarder går det snabbare att sätta sig in i hur webbplats fungerar och att minskade underhållskostnader så som att webbsidorna blir mindre och kräver inte lika mycket resurser. 

vi har snackat mycket om webbstandarder med vad är det och vad finns det? XHTML 1.1 STRICT är den senaste och striktaste standarden som finns och denna standar fungerar inte på alla webbläsare. sen finns det också XHTML 1.0 STRICT vilket är den populäraste standarden som finns, eftersom den inte tillåter någon kod som syftar till att beskriva hur webbsidan ska se ut tvingar den fram en bra seperation av innehåll och presentation. xhtml är en form av xml är den mer framtidssäker än vanligt html och mer anpassad fungera i andra typer av webbläsare som tv- skärmar och mobiltelefoner. om du är en person som använder mycket ramar på webbplatsen men ändå vill följa xhtml är xhtml 1.0 frameset för dig fast att denna standard inte är en rekommendation. Vi har snackat mycket om xhtml men vad är det? xhtml är ett märkes språk och en vidareutveckling av html. xhtml är baserat på det flexiblare sgml baserat på det strikare xml. xhtml började som en omformulering av html i xml anses det vara sen senaste versionen av html. 

xhtml 1.0 strict så ser "koden" ut såhär:  DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd"

xhtml 1.0 transitional så ser "koden" DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd"

## HC 1.5 CSS Pre-processorer (ex SASS/LESS) 
 Ramverk (framework) i css kan ses som utgångspunkt för hur en webbplats ska estetiskt ut och kännas, be använda ofta för att ta hand om din responsiva css. varför ska man använda css-ramverk? Du behöver inte komma "på" samma hjul varje gång man ska skapa en design för en webbplats. tillgång till en uppsättning i css kan användas direkt med resultat som går att förutse. Css ramverk använding genom ett verktyg som kallas nodejs kommer vi kunna använda css ramverk och pre-prosessorer, Många framework kan ofta med hjälp av cdn. Exempel på ramverk som finns är
 1 Bootstrap
 2 tailwind css
 3 bulma css
 pre-processor är en ett program som tar input och senare producerar outputen som senare kommer att användas som input till ett annat program. Med andra ord så kan man tillexempel skriva i sass för att det blir enklare och senare "göra" den till en css kod det leder till att koden blir simplare. Med andra ord en pre-processor i ett css program som tar i sin tur något som är skrivet i ett eget "språk" och gör den till en ren css. Man kan säga att en pre-processor är när man vill bygga koden själv ifrån grunden. Det finns flera anledningar varför vi ska använda pre-processor dels hantera nya tillägg i css, för varje leverantör av webbläsare, öka produktivitet, att enklare kunna hantera och strukturera större projket och återanvändning slippa upprepa oss i css. 
 SASS- kallar sig för ett css extension language och har funnits med relativt länge.
 Less- kallar sig för ett bakåt kompatibelt. språktillägg för css och vara ett av de få alternativet som finns till sass.
 Stylus- kallar sig för ett "css språk" och är den senaste pre-processor av de som finns tillgängliga. 
 När man använder vissa ramverk såsom html kan bli väldigt jobbigt med många klasser i varje element och vi är beroende av någon lösning. 
 


## HC 1.6 Optimering och validering av HTML & CSS
Beskriv rubriken nedan här
