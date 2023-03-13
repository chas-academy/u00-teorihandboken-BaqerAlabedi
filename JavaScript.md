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
En samling av återanvändbara funktioner som används av dataprogram, detta innebär att den har resurser som man kan återanvända. Detta kallas för ett bibliotek. Resurserna som du kan använda är klasser, för komplicerad kod och under rutiner. Programmeringsspråket har egna standardbibliotek men programmerare kan också skapa egna anpassade bibliotek. Ett stycke kod som kan eller har skrivits av andra utvecklare som kan återanvändas. Med hjälp av ett api kan du få tillgång till funktionalitet som kan integreras smidigt i andra projekt.

Ett stycke kod som dikterar hur projektet ska struktureras och köras är ramverk eller Framework. Arkitekturen i ditt projekt hjälper att definiera designparametrarna för en applikation som hjälper utvecklare att fokusera på specifika egenskaper och betona återanvändningen av design.

skillnader mellan bibliotek och ramverk är b.la

bibliotek är en samling av funktioner som man kan återanvända vilket betyder resurser som används av dataprogram (moduler) lagras i objektformat. Medans en ram är koden som dikterar arkitekturen i självaste projektet. Den som fogar ramar och programmeringsspråk som hjälper till med datorprogram.

inversion of control är den stora och viktigaste som gör så att ramverk skiljer sig från bibliotek. Du har full kontroll när du ringer en metod från bibliotek som har funktioner och rutiner som används av andra program medans kontrollen i ramverk är emellertid inverterad. Det dikterar strukturen på koden och projektet som gör så att du ej kan ringa in i ett ramverk, utan att den kallar dig. " Enkelt uttryckt kan du helt enkelt tänka på biblioteket som en funktion av en applikation och en ram som skelett av applikationen där applikationen definierar sina egna funktioner."

En kod som är skriven av en utvecklare som kan användas av andra utvecklare som kan återanvändas, de införlivas sömlöst i projekt för att lägga till funktionalitet som du kan komma åt med hjälp av ett api medans ramverk ger ett vanligt sätt att bygga och distribuera applikationer som kan användas när ett nytt projekt påbörjas.

jQuery är ett JavaScript bibliotek på flertal plattformar som förenklar Dom-manipulationen tillsammans med många andra komplicerade objekt såsom AJAX-samtal, html-händelse metoder och css-manipulation. Syftet är att den ska kunna förenkla vardags användningen utav J.S på webben. Medans Angularjs är en strukturell ram baserad på arkitekturen som används för att skapa dynamiska webbapplikationer.

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
DOM-manipulation (Document Object Model) hänvisar till processen att programmatiskt ändra innehållet, strukturen eller stilen på en webbsida med hjälp av JavaScript eller andra skriptspråk. Detta kan inkludera saker som att lägga till eller ta bort element, ändra text eller attribut för element och tillämpa CSS-stilar på element. DOM-manipulation är ett kraftfullt verktyg för att skapa dynamiska och interaktiva webbsidor.

För att kunna modifiera html-dokument, lägga till element, redigera och ta bort. Med Dom api kan man ändra dokumenten som ska renderas i webben. Genom att maniupulera Dom kan du skapa applikationer som uppdaterar sidans data utan att behöva uppdatera den, Du kan även flytta element i dokumentet. 

För att manipulera ett element inuti Dom måste du markera och lagra en referens till det i en variabel. När du använder querySelectorAll så är det inte en array utan en nodlista. En nodlista beter sig i vissa aspekter som en array och dessutom ser ut som en array. Alla metoder som gäller för en array gäller inte för en nodlista. QuerySelector är den senaste metoden istället för det man brukade använda innan som var "tag", "id" och "class"

exempel:
// Get the element
var element = document.getElementById("example");

// Change the text of the element
element.
element.

element
innerHTML = "New text";

// Create the new element
var newElement = document.createElement("p");

// Set the text of the new element
newElement.innerHTML = "This is a new paragraph.";

// Add the new element to the page
document.body.appendChild(newElement);

// Get the element
var element = document.getElementById("example");

// Change the CSS of the element
element.style.color = "blue";

Det här är bara några exempel på vad som kan göras med DOM-manipulation. Möjligheterna är oändliga och kan användas för att skapa många dynamiska och interaktiva webbsidor.



## JS 1.6 HTTP-requests
HTTP (Hypertext Transfer Protocol) är ett protokoll för att skicka och ta emot data över internet. Det är grunden för World Wide Web (WWW) och används av webbläsare och servrar för att kommunicera med varandra.
En HTTP-begäran är ett meddelande som skickas av en klient (som en webbläsare) till en server och ber om viss information eller resurs. Begäran Meddelandet inkluderar vanligtvis en metod (som GET eller POST), en URI (Uniform Resource Identifier) ​​och rubriker (som ger ytterligare information om begäran).

URI, även känd som en URL (Uniform Resource Locator), är adressen till den resurs som begärs. Det består vanligtvis av protokollet (http eller https), domännamnet och sökvägen till resursen. Till exempel, i URI:n " http://www.example.com/index.html " är "http" protokollet, " www.example.com " är domännamnet och "/index.html" är vägen till resursen.

Rubrikerna i en HTTP-begäran ger ytterligare information om begäran, såsom typen av innehåll som skickas, storleken på begäran och webbläsaren som används. Några vanliga rubriker inkluderar "Content-Type", "Content-Length" och "User-Agent".

Förfrågnings Metoden används för att indikera den åtgärd som klienten vill utföra på resursen. De vanligaste metoderna är GET, POST, PUT, DELETE och PATCH.
GET: begär en representation av den angivna resursen. Denna metod används för att hämta information från servern.
POST: skickar en entitet till den angivna resursen, vilket ofta orsakar en förändring i tillståndet eller biverkningar på servern. Denna metod används för att skicka data till servern, till exempel när du skickar ett formulär.

PUT: ersätter alla aktuella representationer av mål resurser med begärans nyttolast. Denna metod används för att uppdatera en resurs på servern.
DELETE: tar bort den angivna resursen. Denna metod används för att ta bort en resurs på servern.
PATCH: tillämpar partiella ändringar på en resurs. Denna metod används för att uppdatera en specifik del av en resurs på servern.
När servern tar emot en HTTP-begäran bearbetar den den och skickar tillbaka ett svarsmeddelande, som vanligtvis innehåller en statuskod, en text och rubriker. Statuskoden är ett tresiffrigt nummer som indikerar resultatet av begäran. Några vanliga statuskoder inkluderar 200 OCH, 201 Skapad, 204 Inget innehåll, 400 Bad Request och 404 Not Found.

Svarets brödtext innehåller den begärda informationen eller resursen. Det kan vara i form av HTML, XML, JSON eller vanlig text, beroende på vilken typ av resurs som efterfrågas och innehållstypen som anges i rubrikerna.
Rubrikerna i svaret ger ytterligare information om svaret, såsom typen av innehåll som skickas, storleken på svaret och servern som används. Några vanliga rubriker inkluderar "Content-Type", "Content-Length" och "Server".
Sammanfattningsvis är HTTP ett protokoll för att skicka och ta emot data över internet. HTTP-förfrågningar är meddelanden som skickas av klienter till servrar som ber om viss information eller resurs. Begäran Meddelandet inkluderar vanligtvis en metod, en URI och rubriker. Servern bearbetar begäran och skickar tillbaka ett svarsmeddelande, som vanligtvis innehåller en statuskod, en text och rubriker. Metoden, URI, rubriker och statuskod används för att indikera åtgärder som utförs, resursen som begärs och resultatet av begäran.


## JS 1.7 Lexical scope
Statisk scoping är en konvention som används av många moderna språk (Programmering), I ett programmeringsspråk hänvisar scope till områden där en funktion eller variabel är synlig och kan/ska finnas tillgänglig för annan kod. Den hänvisar även till att ställa in omfattning eller funktionalitetsintervallet för en variabel. Beroende på programmets textuella struktur så bestäms variabelns omfattning, Detta betyder att en variabel kan bara deklareras inom en specifick räckvidd och endast tilgängliga inom den regionen. programmeringsspråk som involverar lexical scoping är JavaScript, R, ML och haskell.

exempel på scope 

// The following variables are defined in the global scope
const num1 = 10;
const num2 = 3;
const name = 'letsGo';

// This function is defined in the global scope
function multiply() {
return num1 * num2;
}
multiply(); // Returns 30

medans nästlat scope 

function getScore() {
const num1 = 13;
const num2 = 10;
function add() {
return `${name} scored ${num1 + num2}`;
}
return add();
}
getScore(); // Returns "letsGo scored 23"



## JS 1.8 Event handling
Event handling i JavaScript innebär att man definierar en funktion som ska köras när ett specifikt händelseinträffar på en HTML-element, till exempel en klick, musrörelse, tangenttryckning eller laddning av en sida. Detta gör det möjligt att skapa interaktiva och responsiva webbsidor.

För att hantera ett event i JavaScript, behöver man först välja det HTML-element som man vill lyssna på eventet för. Detta kan göras med hjälp av metoder som querySelector() eller getElementById(), vilka letar igenom HTML-dokumentet efter element som matchar en specifik CSS-selektor eller ID.

När man har valt elementet kan man lägga till en händelselyssnare med hjälp av addEventListener()-metoden. Denna metod tar två argument: det första är namnet på eventet, och det andra är den funktion som ska köras när eventet inträffar.

En enkel klick-händelselyssnare kan se ut så här:
const myButton = document.querySelector('#myButton');

function handleClick() {
  alert('Knappen har klickats!');
}

myButton.addEventListener('click', handleClick);

I detta exempel har vi valt en knapp med hjälp av querySelector() och sedan definierat en funktion handleClick() som ska köras när knappen klickas på. Funktionen visar en enkel popupruta med texten "Knappen har klickats!".
Vi lägger sedan till händelselyssnaren med addEventListener() och anger att vi vill lyssna på en klick-händelse. När klicket inträffar kommer funktionen handleClick() att köras.
Det är viktigt att inte inkludera parenteserna () efter funktionens namn när man lägger till den som argument i addEventListener(). På så sätt refererar man till funktionen som en variabel snarare än att kalla på den direkt.

Event handling kan användas för att skapa mer interaktiva och responsiva webbsidor. Till exempel kan man använda event handling för att uppdatera en webbsida utan att behöva ladda om sidan, vilket ger en smidigare användarupplevelse.
En annan användning av event handling är att validera formulärdata. Genom att lyssna på en "submit"-händelse på en formulär kan man kalla på en funktion som kontrollerar om all data är korrekt ifylld innan formuläret skickas till servern.

Man kan också använda event handling för att ändra HTML- eller CSS-kod dynamiskt. Till exempel kan man byta ut en bild när man klickar på en knapp, eller visa eller dölja en del av en sida när man klickar på en länk.
Event handling kan också användas tillsammans med API:er för att skapa mer avancerade funktioner på en webbsida. Till exempel kan man använda event handling tillsammans med Google Maps API för att visa olika kartor beroende på vilken knapp som klickas på.

Genom att använda händelselyssnare kan man utföra olika åtgärder när ett event inträffar. Till exempel kan man uppdatera en webbsida utan att behöva ladda om sidan, validera formulärdata och ändra HTML- eller CSS-kod dynamiskt.
Event handling är en viktig del av webbutveckling eftersom det gör det möjligt att skapa mer interaktiva och användarvänliga webbsidor. Genom att använda event handling tillsammans med andra teknologier som API:er kan man skapa mer avancerade funktioner på en webbsida.

Event handling kan verka komplicerat för nybörjare, men det är en viktig färdighet för alla som arbetar med webbutveckling. Genom att förstå hur man hanterar events i JavaScript kan man skapa mer avancerade webbsidor och förbättra användarupplevelsen för besökare.

Sammanfattningsvis är event handling en viktig del av JavaScript och webbutveckling. Genom att lyssna på händelser som inträffar på en webbsida kan man utföra olika åtgärder och skapa mer interaktiva och användarvänliga webbsidor. Genom att lära sig hantera events i JavaScript kan man förbättra sin förmåga som webbutvecklare och skapa mer avancerade funktioner på en webbsida.
## JS 1.9 Prototype inheritance
Prototype inheritance

JavaScript är ett prototyp baserat språk vilket innebär att man kan skriva oop i javascript men fungerar ej som äkta språk utan ett prototyp baserat språk. i ett prototyp objekt så har alla en mall, När nya objekt skapas så ärver de egenskaper och metoderna från den prototypa objektet. Man ärver det ifrån moder objektet som nästan allt är baserat på. 

Den prototypiska arv modellen är mer kraftfull än den klassiska modellen. Ett exempel är att det är ganska trivialt att bygga en klassisk modell ovanpå en prototypisk modell. Det är så klasser kommer att implementeras. 

JavaScript-objekt är “påsar” av egenskaper, objekt har en länk till ett prototyp objekt.
När du försöker komma åt egenskaper för olika objekt kommer egenskapen att söka på objektets prototyp, prototypen och få fortsätter det till prototyp kedjans slut eller tills den hittar en egenskap som matchar. 

JavaScript har inte “metoder” som klassbaserade språk definerar dem. Vilken funktion som helst kan läggas till ett objekt i form av egenskap i JavaScript. Ärvda funktioner fungerar precis som alla andra egenskaper. När en ärvd funktion exekveras pekar värdet this på det ärvda objektet. 

Exempel från 
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
Higher-order functions är en viktig del av funktionell programmering och en grundläggande koncept inom JavaScript. En higher-order function är en funktion som antingen tar en annan funktion som argument eller returnerar en funktion som resultat.

Higher-order functions gör det möjligt att skapa mer dynamisk och flexibel kod eftersom de kan anpassa sig till olika situationer och behov. Genom att använda higher-order functions kan man abstrahera bort komplexitet och skapa återanvändbara kodblock.

En av de vanligaste användningarna av higher-order functions är att använda dem för att manipulera arrayer i JavaScript. Till exempel kan man använda higher-order functions som map(), filter() och reduce() för att bearbeta arrayer på olika sätt.

Följande kodexempel visar hur man kan använda en higher-order function som map() för att dubblera alla tal i en array:

const numbers = [1, 2, 3, 4, 5];

const doubledNumbers = numbers.map((num) => {
  return num * 2;
});

console.log(doubledNumbers); // Output: [2, 4, 6, 8, 10]

I exemplet ovan används higher-order funktionen map() för att skapa en ny array som innehåller dubblerade tal från den ursprungliga arrayen.

En annan vanlig användning av higher-order functions är att skapa closures i JavaScript. En closure är en funktion som kan komma åt variabler utanför dess egen omfattning, vilket gör det möjligt att skapa privata variabler och metoder i JavaScript.

Följande kodexempel visar hur man kan använda en higher-order function för att skapa en closure i JavaScript:

function counter() {
  let count = 0;

  return function() {
    count++;
    console.log(count);
  }
}

const incrementCounter = counter();

incrementCounter(); // Output: 1
incrementCounter(); // Output: 2
incrementCounter(); // Output: 3

I exemplet ovan används en higher-order function för att skapa en closure som räknar upp ett räkneverk varje gång den anropas. Genom att anropa higher-order funktionen counter() och spara resultatet i en variabel kan man skapa en referens till closure-funktionen som räknar upp varje gång den anropas.

Sammanfattningsvis är higher-order functions en viktig del av funktionell programmering och JavaScript. Genom att använda higher-order functions kan man skapa mer dynamisk och flexibel kod och abstrahera bort komplexitet. Higher-order functions används ofta för att manipulera arrayer och skapa closures i JavaScript.

## JS 1.11 Single-thread programming
Asynkrona funktioner
Man jobbar mycket och ofta med något som kallas asynkron programmering, När man skapar webbapplikationer i JavaScript vare sig det är koden som körs på serversidan eller klientsidan. Man är van med att i programmering så sker sakerna synkront, Det sker i en förutsägbar och bestämd ordning. Direkt när en funktion körs så bildas det ett programflöde där instruktionen B följer efter instruktion A och då kan man använda sig av resultatet som skapades i funktionen. De flesta programmeringsspråk i grunden fungerar likadant.
 
Exempel på synkron programmering:
	// Vi hämtar lite data ifrån en databas
	let resultat = HämtaResultat(”select * from database”); // Här ”stannar” körningen tills metoden är klar
	// Här fortsätter sedan programmet, när förra metoden körts klart och all data är hämtad
	BehandlaResultat(resultat);


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



källor:
https://drive.google.com/file/d/1Ykl6rQExfhtvded7CaIBfimgMlO0EBiH/view
https://www.ecma-international.org/publications-and-standards/standards/ecma-262/(https://webbling.se/index.php/Introduktion_till_asynkron_programmering)
https://drive.google.com/file/d/11UJrJ_QjYW-VzpvhJOM1hJ58G9Z0I1p2/view)
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain)
https://webbling.se/index.php/Introduktion_till_asynkron_programmering)
https://sv.differkinome.com/articles/software/unassigned-2395.html
https://medium.com/swlh/what-is-dom-manipulation-dd1f701723e3
https://www.w3schools.com/whatis/whatis_http.asp
https://sv.wikipedia.org/wiki/Hypertext_Transfer_Protocol
https://www.techtarget.com/whatis/definition/lexical-scoping-static-scoping