## Welcome to Algortime101

We gebruiken de  [online editor](http://www.informatica-actief.nl/js/tekenapp2/WebLogoGWT.html) om algoritmes te maken. Let goed op de vereisten die gesteld worden vooraf van deze Praktische Opdracht.

`vooruit(aantal)`
Met deze opdracht beweegt de pen een aantal eenheden (pixels) vooruit. Hiermee wordt dus echt getekend, tenminste als de pen aan staat.

`rechts(hoek)`
Hiermee verandert de tekenrichting van de pen. De tekenrichting van de pen draait zoveel graden naar rechts (met de wijzers van de klok mee) als er tussen haakjes is opgegeven.

`links(hoek)`
Dit is eenzelfde soort opdracht als rechts, maar nu wordt de tekenrichting van de pen naar links gedraaid, weer over het aantal graden dat tussen de haakjes is opgegeven.

`stap(aantalX, aantalY)`
Verplaats de pen aantalX eenheden naar rechts en aantalY eenheden vooruit. Wanneer je negatieve getallen gebruikt gaat de pen naar links, respectievelijk achteruit. De kijkrichting van de pen verandert niet. Als de pen aan staat, wordt er een lijn getekend direct naar het punt van bestemming (dus geen hoek).

`penAan(kleur)`
 Hiermee zet je een denkbeeldige pen aan. Tussen de haakjes kun je aangeven met welke kleur er getekend moet worden. Dat kan op drie manieren:

..* Je tikt niks in, je krijgt dan de default kleur zwart.
..* Je tikt de naam van een kleur in. De kleuren die je kunt gebruiken zijn: rood, groen, blauw, geel, oranje, cyaan, roze, magenta, grijs, lichtgrijs, wit en zwart.
..* Je tikt een RGB-waarde in: drie getallen tussen de 0 en 255, gescheiden door komma's. Bijvoorbeeld '25,120,255'. penUit() Hiermee haal je de denkbeeldige pen weer van het scherm. Je kunt daarna de pen verplaatsen zonder dat er iets getekend wordt.

`vulAan(kleur)` Deze opdracht kun je gebruiken om vlakken in te kleuren. Teken hierna een figuur en gebruik vulUit om de getekende figuur op te vullen. Tussen de haakjes kun je aangeven met welke kleur er getekend moet worden. Dat kan op drie manieren:

Je tikt niks in, je krijgt dan de default kleur zwart.
Je tikt de naam van een kleur in. De kleuren die je kunt gebruiken zijn: rood, groen, blauw, geel, oranje, cyaan, roze, magenta, grijs, lichtgrijs, wit en zwart.
Je tikt een RGB-waarde in: drie getallen tussen de 0 en 255, gescheiden door komma's. Bijvoorbeeld '25,120,255'. vulUit()
Deze opdracht gebruik je eerst vulAan gebruikt hebt. Het gebied dat wordt omsloten door de tekening die je gemaakt hebt na de opdracht vulAan, wordt opgevuld. Zorg ervoor dat je een gesloten figuur tekent (de pen is weer terug op hetzelfde punt als waar je vulAan deed), anders is het resultaat onzeker.

`vulBlad(kleur)` Deze opdracht kun je gebruiken om het tekenblad een achtergrondkleur te geven. Zet deze opdracht vooraan, want wat je eerder getekend hebt, wordt gewist. De kleur kun je op drie manieren aangeven:

Je tikt niks in, je krijgt dan de default kleur zwart.
Je tikt de naam van een kleur in. De kleuren die je kunt gebruiken zijn: rood, groen, blauw, geel, oranje, cyaan, roze, magenta, grijs, lichtgrijs, wit en zwart.
Je tikt een RGB-waarde in: drie getallen tussen de 0 en 255, gescheiden door komma's. Bijvoorbeeld '25,120,255'.
print(tekst) Print tekst op het tekenblad, vanuit de linker bovenhoek (als een normale tekstpagina). Je kunt letterlijke tekst opgeven, zet er dan aanhalingstekens omheen: "tekst". Je kunt ook de naam van een variabele opgeven, zonder aanhalingstekens. Dan wordt de waarde van die variabele geprint.

`println(tekst)` Print tekst op het tekenblad, vanuit de linker bovenhoek (als een normale tekstpagina). Na het printen van de tekst gaat de tekstcursor naar een nieuwe regel. Je kunt letterlijke tekst opgeven, zet er dan aanhalingstekens omheen: "tekst". Je kunt ook de naam van een variabele opgeven, zonder aanhalingstekens. Dan wordt de waarde van die variabele geprint.

Je uitwerking moet zo efficient mogelijk geformuleerd worden.


Voorbeelden <br>

# ![Example 2](https://github.com/Piersoncollege/algorithm101/blob/master/image2.png)
# ![Example 3](https://github.com/Piersoncollege/algorithm101/blob/master/image3.png)
# ![Example 4](https://github.com/Piersoncollege/algorithm101/blob/master/image4.png)

Uitdagingen 
# ![Challenge 1](https://github.com/Piersoncollege/algorithm101/blob/master/challange2017_1.jpg)
# ![Challenge 2](https://github.com/Piersoncollege/algorithm101/blob/master/challange2017_2.jpg)
# ![Challenge 3](https://github.com/Piersoncollege/algorithm101/blob/master/challange2017_3.jpg)
# ![Challenge 4](https://github.com/Piersoncollege/algorithm101/blob/master/challange2017_4.jpg)
