# Teorihandboken - JavaScript (JS)
Studerande: Baqer Al-abedi

## JS 1.1 JavaScript / ECMAScript
Intro - Javascript är ett programmeringsspråk som började med sitt liv genom ett sätt att lägga funktionalitet på webbsidor. Den har utvecklas och används överallt. Man kan skriva en hel applikation med enbart javascript. Enligt statistik så använder 65% av alla programmerare javaScript vilket gör att det är det största ledande språket. 

Programmering som koncept är i grunden väldigt enkelt. Vi vill ge beetende och skapa funktionalitet som kan köra för att utföra uppgifter eller förbättra upplevelsen för användare. 
Men vad är programmering? Det är ett sätt för oss människor att kunna förklara för en dator vad vi vill att den ska göra, men för tillfället så är språken som vi talar fortfarande olikt det datorn talar så vi behöver något som underlättar kommunikationen och på så vis behöver vi ett programmeringsspråk. Man kan säga också säga att det är instruktioner, 1 och 0.

Det binära talsystemet är grundat på talbasen 2 och utnyttjar endast två siffror, 0 och 1. Liksom i det decimala talsystemet är siffran längst till höger minst signifikant. Med en siffra kan endast 0 och 1 skrivas. För att skriva talet två så måste ytterligare en siffra skrivas till vänster om den första. Det vill säga “10”. Varpå talet 3 följer representerat som “11” osv. 
Det är ett sätt att bygga en verklighet. Datan är uppbyggt av miljoner ljuskällor som går över olika transaktioner som gör så att datorn läser av de till olika 1 och 0 som presenterar vad den ska göra. Instruktioner är också bra eftersom vi vill ge datorn en “uppgift” så att den kan göra. En av de viktigaste sakerna för att kunna programmera ett system för nånting så gäller det att först ge sig in i systemet och förstå det själv för att kunna göra det ordentligt. 

Man måste ha en jätte tydlig syn på vilka verkligheter som man vill modulera. Man måste också kunna kontrollera vad som händer eller kan hända. Man vill kunna kontrollera vad som händer och vilka värden en användare kan ge och vilken input som den kan ge.
Det finns många och olika programmeringsspråk och dessa har alla utvecklats på framgång och begränsningarna av programmeringsspråken som har funnit innan. Historien börjar med utvecklingen av de första datorerna.  
Abakusen är ett slags miniräknare som man kan räkna med de och dela upp olika sifferkombinationer, Människan har hela tiden försökt förenkla sin tillvaro och hjälpa lasta av minnet. Den äldsta analog datorn 200 före kristus. 
Som man ville använda för att se på stjärnor. 

Det fanns en matematiker som fanns 300 år före kristus redan vid namnet pingala och utvecklar den första kända varianten av det binära talsystemet, 1600 år innan matematikerna i väst utvecklar den moderna versionen av det binära talsystemet som utnyttjas av alla datorer idag. 
Javascript introduceras år 1995 för att ge språkmöjligheter till webbplatser i netscape navigator. Den har växt till sig och har möjliggjort att göra webbapplikationer också. Började användas av alla större webbläsare och efter det behövde det ett standar och det var så ecmascript kom in i bilden. Ecmascript är ett språk som standardiseras av ecma international och ses över av TC 39 kommitten. När man pratar om ecmaScript så pratar man till standarden.  JavaScript är namnet för alla implementationer av ecmascript standarden. 

Ecma Internationals TC39 är en grupp JavaScript-utvecklare, implementerare, akademiker och mer, som samarbetar med samhället för att upprätthålla och utveckla definitionen av JavaScript. Det är så att “Människor” skriver olika koder som javaScript behöver och därefter så går man igenom det och ser till att det är möjligt att den kommer in i javaScript. Vi använder javascript för att det är mångsidigt och nybörjarvänligt. Efter att man har skaffat sig mer erfarenhet kommer man att kunna skapa massa olika saker, Bland Annat databasdrivna appar, spel och mycket mer.  JavaScript kan båda användas i en frontend och en backend utveckling. 

Frontend - Är ett artefakt (program) Som skapas med webb teknologierna html, css och javaScript och som används på klientens enhet. Upprättar vanligast en kontakt med en backend via ett API.  

Backend - En artefakt (som skapas med något programmeringsspråk, tex javaScript, php, eller c# eller många fler. Upprättar vanligast en kontakt mellan databas och frontend via ett API. 
när man använder JavaScript så måste man även köra programmet. JavaScript är ett språk som bara kör en tråd i taget. Man kan använda den på följande vis antingen i en webbläsare eller med node. När vi ska använda javaScript i ett html-fil så måste det skrivas inom en "script" tag.  Man kan bestämma ifall man vill lägga till den i slutet av en head eller en body. Men det finns oskrivna “regler” eftersom att sidan läses in uppifrån och ned så kommer användaren att se en blank sida tills den laddas in och just därför så vill man ha den helst i slutet av body.  

Man kan skriva in all JavaScript direkt i en html dokument eller lägga den i en separat javaScript fil som man sedan länkar till. Att länka sin javascript dokument till html så är det bättre eftersom du håller de separerade och det är mer strukturerat för att hålla reda på all kod. Eftersom att man har den på en separat fil så kommer sidan även att laddas snabbare. Infon som jag har fått har lett till att i framtiden så kommer jag länkade filerna in till html ist för att ha koden i självaste filen. (separation of concerns) 
## JS 1.2 JavaScript-ramverk och -bibliotek
Beskriv rubriken här

## JS 1.3 Promises
Promises
Ett nytt sätt att hantera asykrona anrop är promises. Detta gör så att man enkelt kan ange vad som ska ske när ett asynkront kod anrop är avklarat. Promises kan skapa kod som inte är så mycket komplicerad eller svårläst än vanlig synkron kod. 

Ett exempel på asynkron programmering med promises kan se ut så här:
	// Vi hämtar lite data ifrån en databas

	// Den här metoden körs igång direkt, men
	// det är inte säkert att den blir klar
	// direkt
	HämtaResultat()
		// 	När HämtaResultat är klar körs detta
		.then(BehandlaResultat(resultat))
		// Om något går fel körs den här biten
		.catch(BehnadlaFel(felkod);
källa: (https://webbling.se/index.php/Introduktion_till_asynkron_programmering)

Promises har 3 olika tillstånd. Pending, fulfilled och rejected och genom att använda if-satser kan man kolla dessa states för att få det beetende man vill. För att beskriva vad som kan hända efter att funktionen blivit fulfilled eller rejected så kan man använda sig utav “then” 

Exempel på promise
const promise = new Promise(
function (resolve, reject) {
const x = "student";
const y = "student";
if (x === y) {resolve();}
else {reject();}
});
promise.then(
function () {
console.log("Success, You are a student");
},
function (error) {
console.log("Rejected, You are not a student");
}
källa: (https://drive.google.com/file/d/11UJrJ_QjYW-VzpvhJOM1hJ58G9Z0I1p2/view)
);


## JS 1.4 OOP i JavaScript
JavaScript OOP
OOP står för object oriented Programming, OOP är en programmeringsparadigm vilket betyder en slags utbrett metod att arbeta som centrerar sig kring objekt. Man kan nästan bygga vad som helst med strukturerad programmering men då måste det vara väldigt strukturerad. Man vill gruppera variablerna. Man vill skapa en objekt som sen kan innehålla det som man behöver från objektet. Tex ett djur. Då kan man tillexempel ha namn, beetende, ålder, ägare, ras. Då gör man en objekt som har en gruppering med tex katt innehåll. 

vi använder objekt inom programmering för att likna saker i verkligheten. Det är en av sätten att beskriva vår data och funktionalitet som är relaterade. Ifall vi använder oss av objekt så har vi kapslat in funktionalitet och data för att sedan skapa ett specifikt ändamål vilket gör det lättare att strukturera och gruppera kod samt komma åt koden som vi behöver. 

Genom att gruppera data och funktioner kan kan man då förbättra strukturen i programmet och öka återanvända barheten och slippa repetition och det gör så att man kommer undan med att data och funktioner ligger utspridda. 

I javaScript så används inte abstraktion men i PHP används det-

Arv - eliminera redundant kod, tex ta objekt, en katt kan ärva från djur (namn, ben, levande eller död) ta en objekt, som tar saker från en annan objekt. 
Hierarkier där klasser bygger på andra klasser

Abstraktion - Reducera komplexitet och effekten av ändringar, tex 
separation av och fokuset på interfaces hos en klass och inte implementationen
logik delas upp i interface och faktiskt utförande i klasser

Polymorfism - Refaktorisera konduktionsblock, tex Man kan komma åt en metod som finns i en objekt om de heter samma sak, Ett djur kan skapa ljud. Tex katt säger mjau och hund voff.
Enhetlig behandling av klasser i en hierarki. Så länge man kan hantera objekt i toppen av hierarkin kan man hantera objekt som kommer senare också

Inkapsling - Reducera komplexitet och öga återanvändbarhet, tex Skapa grupper, 
Ha data och funktioner kopplade till en entitet
Bara visa de detaljer som är viktiga att interagera med

Inkapsling
inkapsling är e process som organiserar så att funktioner och variabler i separata enheter. En enhet inom OOP är ett objekt. I OOP så kallas variabler för egenskaper efter som att egenskaper har som har blivit grupperat i en intitet. Funktioner kallas för metoder och funktioner ligger lite överallt i ett dokument medans metoder är en del av ett objekt. 
Med andra ord så är funktioner och variabler lite överallt medans egenskaper och metoder tillhör något. inkapsling handlar om att skapa en intitet. 

Abstraktion
Att skapa enkel modell av en komplext och endast visa att bara det som behövs för att interagera med objekt. De egenskaperna och variablerna som man behöver komma åt är de enda som man vill komma åt. Döljer detaljer och visar endast nödvändiga detaljer i ett objekt vilket leder till ett enklare interface till objektet. Vi reducerar även effekten av förändringar.

Arv
Arv används för att vi som programmerare inte behöver upprepa oss i kod och kan låta objekt ärva egenskaperna och metoder från andra objekt. Man vill skriva så lite som möjligt i kod utan att upprepa sig. Man vill skriva en funktion och det “löser” allt. 


## JS 1.5 DOM-manipulation
Beskriv rubriken här

## JS 1.6 HTTP-requests
Beskriv rubriken här

## JS 1.7 Lexical scope
Beskriv rubriken här

## JS 1.8 Event handling
Beskriv rubriken här

## JS 1.9 Prototype inheritance
Prototype inheritance

JavaScript är ett prototyp baserat språk vilket innebär att man kan skriva oop i javascript men fungerar ej som äkta språk utan ett prototyp baserat språk. i ett prototyp objekt så har alla en mall, När nya objekt skapas så ärver de egenskaper och metoderna från den prototypa objektet. Man ärver det ifrån moder objektet som nästan allt är baserat på. 

Den prototypiska arv modellen är mer kraftfull än den klassiska modellen. Ett exempel är att det är ganska trivialt att bygga en klassisk modell ovanpå en prototypisk modell. Det är så klasser kommer att implementeras. 

JavaScript-objekt är “påsar” av egenskaper, objekt har en länk till ett prototyp objekt.
När du försöker komma åt egenskaper för olika objekt kommer egenskapen att söka på objektets prototyp, prototypen och få fortsätter det till prototyp kedjans slut eller tills den hittar en egenskap som matchar. 

JavaScript har inte “metoder” som klassbaserade språk definerar dem. Vilken funktion som helst kan läggas till ett objekt i form av egenskap i JavaScript. Ärvda funktioner fungerar precis som alla andra egenskaper. När en ärvd funktion exekveras pekar värdet this på det ärvda objektet. 

Exempel från (https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain)
const parent = {
  value: 2,
  method() {
    return this.value + 1;
  }
};

console.log(parent.method()); // 3
// When calling parent.method in this case, 'this' refers to parent

// child is an object that inherits from parent
const child = {
  __proto__: parent,
};
console.log(child.method()); // 3
// When child.method is called, 'this' refers to child.
// So when child inherits the method of parent,
// The property 'value' is sought on child. However, since child
// doesn't have an own property called 'value', the property is
// found on the [[Prototype]], which is parent.value.

child.value = 4; // assign the value 4 to the property 'value' on child.
// This shadows the 'value' property on parent.
// The child object now looks like:
// { value: 4, __proto__: { value: 2, method: [Function] } }
console.log(child.method()); // 5
// Since child now has the 'value' property, 'this.value' means
// child.value instead

This
This är en nyckelord som finns i JavaScript och beter sig annorlunda.
Den används för att hänvisa till ett objekt, vilket objekt beror på hur det anropas eller används. I en objektmetod syftar this på ett objekt. Vi kan använda oss av en kort exempel.

const fotbollslag = {
firstName: “Real”,
lastName: “Madrid”,
id: 7788,
fullName: funtion () {
return this.firstName + “ “ + this.lastName;
  }
};
// retunerar Real Madrid


## JS 1.10 Higher-order functions
Beskriv rubriken här

## JS 1.11 Single-thread programming
Asynkrona funktioner
Man jobbar mycket och ofta med något som kallas asynkron programmering, När man skapar webbapplikationer i JavaScript vare sig det är koden som körs på serversidan eller klientsidan. Man är van med att i programmering så sker sakerna synkront, Det sker i en förutsägbar och bestämd ordning. Direkt när en funktion körs så bildas det ett programflöde där instruktionen B följer efter instruktion A och då kan man använda sig av resultatet som skapades i funktionen. De flesta programmeringsspråk i grunden fungerar likadant.
 
Exempel på synkron programmering:
	// Vi hämtar lite data ifrån en databas
	let resultat = HämtaResultat(”select * from database”); // Här ”stannar” körningen tills metoden är klar
	// Här fortsätter sedan programmet, när förra metoden körts klart och all data är hämtad
	BehandlaResultat(resultat);
Källa: (https://webbling.se/index.php/Introduktion_till_asynkron_programmering)

Asynkron programemring
När vi kör vissa funktioner så startas de igång,  medans de jobbar på så kommer koden att gå vidare och kör efterföljande kod. JavaScript är jättebra på asynkron programmering. Utan att invänta den asynkrona metoden går klart eller levererar några resultat. På Grund av olika mekanismer som används på olika plattformar och i olika JavaScript-implementationer och det är en stor chans att koden som du startar kan hamna i en egen tråd. 

Vi behöver specifika stöd för att hjälpa språken i asynkron programmering. Vi kommer behöva något sätt att vi kan ange en metod eller kodsnutt. Men vi kommer behöva mekanismer som kan kolla ifall den metoden som startas asynkront avklarad. Detta hade varit väldigt ineffektivt om programmet hela tiden behövde gå in och kontrollera att den asynkrona metoden körts klart. 

Vi måste börja tänka på ett nytt sätt när vi jobbar med asynkron programmering. Det går inte att bara skriva koden i ett löpande flöde och förvänta sig att saker sker en efter en. Med noggrann planering och ett sätt att hålla reda på vilket koddelar och data som är beroende av varandra. Asynkron programmering kan anses som krånglig men det brukar vara allt mer förtjust i det desto mer asynkron kod. Grunden till att skapa snabba applikationer i JavaScript då kommer vi oftast återkomma tillbaka till asynkron programmering.  

Callbacks
Callback är en metod som körs när den asynkrona koden kört klart. Detta är en gammal lösning som i JavaScript-världen använde sig av. Problemet med callback är att man vill göra flera asynkrona saker på rad. Att vi skickar en förfrågan genom databasen och läser in resultatet. Alla anrop är oftast asynkrona som innebär att vi kommer behöva steg för steg av callback som är svårläst och svårt att underhålla. 


## JS 1.12 OAuth från frontend
Beskriv rubriken här

## JS 1.13 Websockets
Beskriv rubriken här

