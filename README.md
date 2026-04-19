📌 Projekto aprašymas

Šis projektas – tai paprasta internetinė parduotuvė „Prieskonių pasaulis“, sukurta naudojant tik HTML5 ir CSS3. Svetainė leidžia vartotojui peržiūrėti produktus, matyti jų detalią informaciją bei peržiūrėti statinį krepšelį. Projektas orientuotas į aiškią struktūrą, estetišką dizainą ir patogų naršymą.

📁 Projekto struktūra

eshop/
│
├── products.html
├── product.html
├── cart.html
├── style.css
└── images/

📄 HTML failų aprašymas

🔹 products.html
Pagrindinis puslapis su produktų sąrašu
Rodomi visi produktai (nuotrauka, pavadinimas, kaina)
Kiekvienas produktas turi nuorodą į detalų puslapį
Yra navigacija į krepšelį

🔹 product.html
Skirtas produkto informacijos atvaizdavimui
Rodoma:
nuotrauka
pavadinimas
kaina
aprašymas
Yra mygtukas „Pridėti į krepšelį“ (vizualinis)
Naudojamas keliems produktams per :target (CSS)

🔹 cart.html
Statinis krepšelio puslapis
Rodomi keli produktai su:
pavadinimu
kiekiu
kaina
Apskaičiuota bendra suma
Yra mygtukas „Apmokėti“ (vizualinis)

🎨 CSS aprašymas (style.css)

CSS faile aprašytas visas svetainės dizainas:

Bendri stiliai (body, šriftai, spalvos)
Header ir navigacija
Produktų kortelės (cards)
Mygtukai su hover efektais
Krepšelio dizainas
Responsive dizainas (media queries)

Taip pat naudoti efektai:

hover animacijos
šešėliai (box-shadow)
gradientai
transformacijos (scale, translate)

🎯 Projekto uždaviniai
Sukurti e-shop naudojant tik HTML ir CSS
Atvaizduoti produktų sąrašą
Sukurti produkto detalės puslapį
Sukurti krepšelio puslapį
Užtikrinti navigaciją tarp puslapių
Pritaikyti responsive dizainą

⚙️ Projekto įgyvendinimas

Projektas įgyvendintas laikantis paprastos struktūros principų:

Naudoti semantiniai HTML elementai
Sukurtas aiškus puslapių suskirstymas
Navigacija leidžia lengvai pereiti tarp puslapių
Dizainas pritaikytas skirtingiems ekranų dydžiams

Produktų puslapyje panaudotas CSS :target selektorius, leidžiantis parodyti skirtingus produktus viename faile.

🧰 Naudotos technologijos
HTML5
CSS3
🔧 CSS technikos:
Grid – produktų išdėstymui
Flexbox – elementų lygiavimui
Media queries – responsive dizainui
Hover efektai – interaktyvumui
Transitions & transform – animacijoms
