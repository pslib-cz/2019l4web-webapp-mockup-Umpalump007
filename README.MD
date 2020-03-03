# Návrh aplikace - HANG MAN
Upravená verze hry **HANG MAN**
## Struktura / funkce
Hra se skládá z několika obrázků ve stejném poměru stran, které reprezentují jednotlivé části a levely hry.
Hráč si bude moci vybrat kategorie, ze kterých budou vybrána slova.
Hráč bude začínat s 8 životy a pokud přežije 10 kol (uhádne 10 slov), přežije (samostatná stránka), pokud ztratí všech 8 životů - samostatná stránka
Hráč hádá písmenka, která doplní celé slovo, pokud uhodne písmenko, které není ve slovu obsaženo ztácí život (přepne se na další stránku)...
Každá stránka má vlastní pojmenování:
* open screen - desktop.jpg -> Úvodní stránka
* setup screen - desktop.jpg -> Stránka nastavení hry
* game-8-desktop.jpg -> První stránka spuštěné hry, kdy má hráč všech 8 životů
* game-7-desktop.jpg -> Druá stránka supštěné hry, kdy má hráč 7 životů
* game-6-desktop.jpg
* ...
* ...
* ...
* ...
* game-1-desktop.jpg -> Poslední stránka, kdy má hráč pposlední život
* endscreen-win-desktop.jpg -> Poslední stránka, pokud hráč uhádne všech 10 slov
* endscreen-loose-desktop.jpg -> Poslední stránka, pokud hráč ztratí všech 8 životů
## Úvodní obrazovka 
![Úvodní obrazovka](https://github.com/pslib-cz/2019l4web-webapp-mockup-Umpalump007/blob/master/Img/Desktop/Open%20screen%20-%20desktop.jpg "IMG- open screen")
Toto bude první stránka, která se hráči zobrazí, bude stručně popisovat pravidla hry. V pravé dolní části se následně umístí tlačítko, které hráče přesune na další stránku.
## Druhá obrazovka - nastavení
![Nastavení hry](https://github.com/pslib-cz/2019l4web-webapp-mockup-Umpalump007/blob/master/Img/Desktop/Setup%20screen%20-%20desktop.jpg "IMG- setup screen")
Zde si hráč bude moci zvolit jednu ze 4 kategorií, ze kterých budou generovány slova 
**Kategorie:** *Sport, Kultura, Hudba, Filmy*
## Třetí obrazovka - spuštěná hra
![Hra - start](https://github.com/pslib-cz/2019l4web-webapp-mockup-Umpalump007/blob/master/Img/Desktop/Game-8-desktop.jpg "IMG- game")
V této části už je hra spuštěná, přičemž hráč má plné životy (všech 8 a oběšenec není vidět). Objeví se slovo s vynechanými písmenky.
## Ztráta životu
Pokud hráč ztratí život objeví se část HangMana.
#### 7 životů
![Hra](https://github.com/pslib-cz/2019l4web-webapp-mockup-Umpalump007/blob/master/Img/Desktop/Game-7-desktop.jpg "IMG- game")
#### 6 životů
![Hra](https://github.com/pslib-cz/2019l4web-webapp-mockup-Umpalump007/blob/master/Img/Desktop/Game-6-desktop.jpg "IMG- game")
#### 5 životů
![Hra](https://github.com/pslib-cz/2019l4web-webapp-mockup-Umpalump007/blob/master/Img/Desktop/Game-5-desktop.jpg "IMG- game")
#### 4 životů
![Hra](https://github.com/pslib-cz/2019l4web-webapp-mockup-Umpalump007/blob/master/Img/Desktop/Game-4-desktop.jpg "IMG- game")
#### 3 životů
![Hra](https://github.com/pslib-cz/2019l4web-webapp-mockup-Umpalump007/blob/master/Img/Desktop/Game-3-desktop.jpg "IMG- game")
#### 2 životů
![Hra](https://github.com/pslib-cz/2019l4web-webapp-mockup-Umpalump007/blob/master/Img/Desktop/Game-2-desktop.jpg "IMG- game")
####  Poslední život
![Hra](https://github.com/pslib-cz/2019l4web-webapp-mockup-Umpalump007/blob/master/Img/Desktop/Game-1-desktop.jpg "IMG- game")
## Konec hry - poslední obrazovka 
Tato část se načte pokud hráč ztratí poslední život, nebo pokud uhádne poslední (10.) slovo.
Pro každý konec je vytvořený samostatný vzhled stránky:
* Výhra 
![Výherní obrazovka](https://github.com/pslib-cz/2019l4web-webapp-mockup-Umpalump007/blob/master/Img/Desktop/Endscreen-win-desktop.jpg "IMG- game")
* Prohra
![Obrazovka prohry](https://github.com/pslib-cz/2019l4web-webapp-mockup-Umpalump007/blob/master/Img/Desktop/Endscreen-loose-desktop.jpg "IMG- game")












