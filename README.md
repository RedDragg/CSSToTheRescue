# CSSToTheRescue
CSS to the rescue school opdracht

# Week 1:

keuze: Control Panel 
Ideeën: 
Space ship control panel 
Sneeuwbol, maar dan in 4 seizoenen. 
Kawaii cute animal laten animeren.
Tamagotchi

een poppetje die een houten knuppel vasthoudt. Je kan de knuppel langer maken, dikker maken en je kan het poppetje laten swingen, springen en dansen.
De control panel wordt een joystick dat aan en uit gezet kan worden.
Functies: 
1. knuppel langer, dikker: Met een sliders kun je de knuppel langer en dikker maken.
2. springen: met een druk op een knop kan je het poppetje laten springen
3. slaan: met een druk op de knop kan je de poppetje laten slaan. Dan verschijnt er een ander poppetje dat het poppetje kan slaan.
4. dansen: je kan het poppetje laten dansen.

keuze:

Een luchtballon dat kan opstijgen.
Functies:
1.  Opstijgen & dalen: Met een hendel kan je de temperatuurr regelen. De temperatuur krijg je dan te zien. 
2. Bij een hoge temperatuur stijgt de ballon sneller omhoog en een lage temperatuur daalt de ballon.
3. Hoogte meter: Een display waarbij je de hoogte ziet van je ballon
4. Wolken: Wanneer je op een bepaalde hoogte zit zie je geanimeerde wolken. Met een slider kan je de wolken sneller of langzamer laten gaan.
5. Dag- en nachtcyclus: je kan met een druk van een knop de sfeer nacht en dag maken.
6. Brandstof: er is een brandstof meter, wanneer dit op is dan daalt de luchtballon snel.
7. Brandstof powerups: Op een bepaalde hoogte worden er brandstof powerups gevonden. Die worden ook geanimeerd van links naar rechts. Bij een klik erop kan je de brandstof oppakken.
8. weereffecten: Je kan het laten regenen, sneeuwen of het is een zonnige dag.
9. vogels: vogels vliegen heen en weer, je ballon gaat een stukje omlaag wanneer een vogel tegen je ballon aankomt.
10. Verschillende ballonnen: Je kan de stijl van de ballon aanpassen zoals kleuren en grote.
11. Op een bepaalde hoogte heb je een easteregg, wanneer je langer dan een bepaalde tijd op die hoogte blijft, zie je het huis van up voorbij komen.
12. De hoogste hoogte die je hebt bereikt wordt bewaard en displayed.

Degene die het hoogst komt heeft gewonnen.

<img src="readmeimg/afb2.jpg" alt="ballon1" width="200">
<img src="readmeimg/YzgobOJ-800.jpg" width="200" alt="ballon2">
<img src="readmeimg/vogels.jpg" width="200" alt="vogels">
<img src="readmeimg/uphouse.jpg" width="200" alt="uphouse">


https://www.pyxofy.com/css-art-hot-air-balloon/
https://codepen.io/shooft/pen/RNwpNav?editors=0110
https://www.youtube.com/watch?v=e6jnl3iAezM

# Week 2: 

In week 2 heb ik gradients onderzocht en ermee geëxperimenteerd. Het is mij gelukt om de luchtballon met gradients te maken en vervolgens heb ik het mandje en de zakjes gemaakt in aparte li's voor een betere nesting.

<img src="readmeimg/week2.png" alt="week2 ballon" width="200">

# Week 3:
Na het maken van de ballon heb ik mij verdiept in het maken van de controls. Hiervoor heb ik de volgende bron gebruikt: https://codepen.io/jonslater204/pen/LYWQbMa - space invaders. Hier heb ik de controls van bekeken en onderzocht.

<img src="readmeimg/lrtb-css.gif">

Wanneer je klikt op een checkbox gaat gaat de li waarin de labels instaan met een display flex en een gap van de button size. Vervolgens veranderd de ballon van plek met transform translate.

<img src="readmeimg/lrtb-code.png">
<img src="readmeimg/lrtb-code2.png">

Ook wilde ik een daynight circle maken met een mooie animatie. Sterretjes die komen in de nacht en die nog blinken. Wanneer de zon opkomt gaan de sterretjes natuurlijk weg. De gradients heb ik van: https://codepen.io/billyysea/pen/nLroLY?editors=1100 - sky gradients en de animatie inspiratie heb ik van: https://codepen.io/CoryMaklin/pen/wXRRye - rising sun
<img src="readmeimg/daynight-css.gif">    
<img src="readmeimg/daynight-code2.png" alt="">
<img src="readmeimg/daynight-code.png" alt="">

De canvas leek me nog heel erg leeg dus heb ik wat gras, bloemetjes, bomen en konijnen toegevoegd. Hier heb ik de inspiratie voor de bomen en konijn gehaald uit: https://codepen.io/agathaco/pen/rpZoYd?editors=0100 - trees. Ook heb ik voor de bomen en bloemetjes een container gebruikt waardoor er minder bomen zijn bij een kleinere wijdte van de ul waarin de bomen en bloemetjes zitten.
<img src="readmeimg/bomen-css.gif">

De bunny heeft een animation dat het om de 2 seconden omhoog en omlaag gaat.
<img src="readmeimg/bunny-css.gif">

Dit is de css waardoor de bomen een verschillende height krijgen.
```css
  li:nth-of-type(2n + 4) {
    height: clamp(2em, calc(var(--index-stam) * 1vw), var(--tree-1-height));
  }
    > li:nth-of-type(1) {
    --index-stam: 1;
  }
  > li:nth-of-type(2) {
    --index-stam: 2;
  }
  /* etc */
```

De achtergrond nog steeds beetje kalig dus heb ik een berg in gedachte met een animatie. Wanneer er een berg ontstaat, ontstaat dit natuurlijk uit een "aardbeving"/aardverschuiving.

<img src="readmeimg/mountain.gif">

Vervolgens heb ik buttons gemaakt 3 voor de size
<img src="readmeimg/buttons-css.gif"

en 3 voor de kleuren.

# Week#4

In week 4 heb ik nagedacht over het design van de control panel. 


https://cssgradient.io/blog/gradient-patterns/

https://codepen.io/CoryMaklin/pen/wXRRye - rising sun

https://codepen.io/billyysea/pen/nLroLY?editors=1100 - sky gradients

https://codepen.io/agathaco/pen/rpZoYd?editors=0100 - trees

https://codepen.io/jonslater204/pen/LYWQbMa - space invaders

https://codepen.io/nelledejones/pen/gOOPWrK?editors=0100 - cool animations

https://www.w3schools.com/howto/howto_css_hide_scrollbars.asp