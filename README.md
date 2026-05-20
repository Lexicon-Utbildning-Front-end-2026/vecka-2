# 📅 Schema Vecka 2: HTML/CSS

---

## 📅 Måndag: CSS reset, variabler, typografi, enheter

CSS reset, varibler, typografi, enheter

### 🎯 Mål för dagen

* Förstå CSS reset
* Kunna välja mellan olika enheter CSS
* Använda variabler i CSS
* Grundläggande om typografi samt google fonts

### 📚 Material
Denna vecka är det mest lite olika förslag på resets. Några av dem nedan har också förklaringar som kan vara bra att läsa om. Se också till att utforska whatunit för att förstå det här med enheter samt läs igenom om variabler, de är väldigt användbara.

#### 💻 E-Learning
* [(YT Kevin Powell) Master CSS Custom Properties](https://www.youtube.com/watch?v=40K1pvxEwlE)
* [(YT Kevin Powell) CSS Units](https://www.youtube.com/watch?v=Utc_uhvTluk)
* Extra - Lite senare tillägg till reset [(YT Kevin Powell)  3 modern CSS properties to add to your reset](https://www.youtube.com/watch?v=qI5rXLJnxco)

#### 📃 Läsning
* [Minimal reset](https://codepen.io/kevinpowell/pen/QWxBgZX)
* [Tailwinds reset](https://tailwindcss.com/docs/preflight)
* [Josh W Comeau Reset](https://www.joshwcomeau.com/css/custom-css-reset/)
* [Om olika enheter - whatunit](https://whatunit.com/)
* [Andy Bell - A (more) Modern CSS Reset](https://piccalil.li/blog/a-more-modern-css-reset/)
* [(w3schools) CSS Variables](https://www.w3schools.com/css/css3_variables.asp)
* [Using CSS custom properties (variables)](https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Cascading_variables/Using_custom_properties)

#### 🛠️ Övningar
* Lägg in en av de ovannämnda resets och se hur det fungerar med den kod ni redan har på receptsidan. Fixa sådant som går sönder efter det. 
* Börja göra om din CSS till att använda variabler. Plocka ut saker som används oftare eller är viktiga, som färger, storlekar eller andra viktiga enheter.
* Ändra till korrekta enheter (ta bort px på font-size framförallt). Se över att ni har lite konsekvent tänk i enheter.
* Testa att lägga in någon fin, men läsbar font på receptsidan.
* Om du är klar med receptsidan, öva vidare på andra sidor till du känner dig bekväm med att använda koncepten från dagen. Fortsätt med detta resten av veckan.

---

## 📅 Tisdag: Clean CSS

Hur vi kan göra vår CSS mer läsbar/hanterbar och mer effektiv.

### 🎯 Mål för dagen

* Nestad CSS
* Namngivningskonventioner i CSS (BEM-CUBE-Tailwind)

### 📚 Material

#### 💻 E-Learning
* [(Pluralsight) Clean Code and Accessibility](https://app.pluralsight.com/ilx/video-courses/clips/06125ef3-cc36-4490-a93d-e7147305a13b)
* [(YT Kevin Powell) Nesting CSS](https://www.youtube.com/watch?v=h4Xp1QgNkhU)

#### 📃 Läsning
* [Tailwind CSS - Styling with Utility Classes](https://tailwindcss.com/docs/styling-with-utility-classes)
* [BEM.info](https://en.bem.info/methodology/css/)
* [CUBE CSS](https://cube.fyi/)

#### 🛠️ Övningar
Testa olika sätt att skriva CSS utifrån det vi pratade om. Antingen till mindre HTML-sidor med samma struktur eller olika delar på samma sida. Viktigt att du får en känsla lite hur skillnaden är. 

När du testat, försök att bestäm dig för vilken typ av CSS-struktur (tisdagens föreläsning) du vill ha och implementera det på din recept-sida. Tänk bara på att om du väljer utility first bör du skriva egna utitily klasser hellre än att använda färdiga för att lära dig bäst. 

---

## 📅 Onsdag: Repetition

Eget arbete och med kod och e-learning

---

## 📅 Torsdag: Selectors, Combinators & Pseudo-classes

Hur använder man tag, id, class, >, *, +, ~, [attr], nth, first, has, is, where, not, hover/active/focus-visiblet?

### 🎯 Mål för dagen

* Förstå skillnaden mellan selectors, combinators och pseudo-classes
* Förstå skillnanden i specificitet mellan de olika och när man kan använda vad
* Kunna använda olika avancerade selectors (som >, *, nth, &, has, is mm)

### 📚 Material

#### 💻 E-Learning
* [(YT Kevin Powell) is(), where(), has() explained](https://www.youtube.com/watch?v=3ncFpP8GP4g)

#### 📃 Läsning
* [CSS Selectors](https://www.w3schools.com/CSSref/css_selectors.php)
* [CSS Combinators](https://www.w3schools.com/CSSref/css_ref_combinators.php)
* [(css-tricks) CSS Selectors](https://css-tricks.com/css-selectors/)
* [(css-tricks) Specifics on CSS Specificity (frivillig)](https://css-tricks.com/specifics-on-css-specificity/)

#### 🛠️ Övningar
* [CSS Diner](https://flukeout.github.io/)

---

## 📅 Fredag: Code review av tillgänglig receptsida

### 🎯 Mål för dagen

* Reflektera över hur ni byggt sidan och hur ni förbättrat den i andra versionen, med fokus på semantik och tillgänglighet.
* Fördjupa förståelsen genom att granska och diskutera kod.

-----------------------------------------------------------

**Code review på receptsidan med tillgänglighetsanpassning och WAVE.**

**Syfte:**  
Reflektera över hur ni byggt sidan och hur ni förbättrat den i andra versionen, med fokus på **semantik** och **tillgänglighet**.

**Förberedelser:**

- Ha er kod redo (gärna med skärmdelning).
- Installera **WAVE Evaluation Tool** om ni inter redan gjort det:  
    https://chromewebstore.google.com/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh

-----------------------------------------------------------

**Genomförande i grupp (4-5 personer)**

Varje student visar sin sidan, testar den i WAVE, och beskriver kort:

1.  **När du byggde första versionen**
    - **När ni gjorde första versionen: hur tänkte ni då kring struktur, HTML‐val och bilder?**  
        Utgick ni mest från att “få det att se rätt ut”, eller hade ni redan tankar om semantik och tillgänglighet?
    - Vad var ni inte medvetna om då, som ni är medvetna om nu?
    - Hur tänkte du kring layout och struktur?
2.  **Vad du ändrade när du förbättrade sidan**
    - Vad gjorde du mer semantiskt?
    - Något du gjorde om helt?
3.  **Semantik i din HTML**  
    Förklara hur du tänkt kring t.ex:
    - &lt;header&gt;, &lt;main&gt;, &lt;section&gt;, &lt;article&gt; — vad representerar vad?
    - Rubriknivåerna (h1, h2, h3) — följer de en logisk struktur?
    - Bilder — använder du alt-texter? Någon bild i &lt;figure&gt; + &lt;figcaption&gt;?
    - Finns kontrastproblem, saknade alt-texter eller rubrikfel?
    - Hur skulle du kunna åtgärda det i så fall?

-----------------------------------------------------------

**Diskussionsfrågor (i grupp)**

Samtala kort om:

- Vad blev förbättrat i era andra versioner?
- Var det svårt att arbeta semantiskt och med clean CSS? Varför/varför inte?
- Vad lärde ni er av WAVE-analysen?
- Hur tänker ni kring när en bild är **informativ** och när den är **dekorativ**?
- Bestäm vem som för gruppens talan vid samlingen och vad den personen ska säga

-----------------------------------------------------------

**Avslut i helklass**

Varje grupp delar:

- Vad var svårast att få till med att uppdatera er receptsida enligt wcag/clean CSS?
- Vad tyckte ni i gruppen var mest användbart/intressant/viktigt som ni lärde de första två veckorna?

---
