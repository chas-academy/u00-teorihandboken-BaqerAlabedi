# Teorihandboken - Programmeringsmetodik (PG)
Studerande: Baqer Al-abedi

## PG 1.1 Versionshantering (Git)
VCS är en enkel databas som innehåller alla de ändringar till filer som hänt under revisionssystemets kontroll. Liten historia om VCS. Det finns 3 generationer inom VCS. Ett system som fanns tidigt blev populärt som heter RCS och utvecklades 80-tal. Denna  första version fungerade genom att man lät varje ändring bli en "patch". Denna ändring sparades i disk som har en väldigt speciellt format.

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
Beskriv rubriken här

## PG 1.3 Testdriven utveckling
Beskriv rubriken här

## PG 1.4 Deploy och staging
Beskriv rubriken här

## PG 1.5 Debugging
Beskriv rubriken här

## PG 1.6 Dokumentation
Beskriv rubriken här

## PG 1.7 Struktur av kod i projekt
Beskriv rubriken här

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



