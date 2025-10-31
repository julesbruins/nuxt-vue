# nuxt-vue
first try-outs with Nuxt and Vue, mostly trying and installation

## USER EXPERIENCE
Vue en Nuxt komen erg in de buurt van react en next. Vue is er echt alleen om interactieve componenten te bouwen binnen Nuxt. Nuxt is altijd bovenop op Vue en dit om een volledige webapplicatie te bouwen met m eerdere pagina’s. Je kan als het ware zien dat Vue de LEGO steentjes zijn en Nuxt het complete LEGO-pakket is met instructies om sneller een groot gebouw te krijgen. 

### TOEGANKELIJKHEID
Ook met Vue is de website niet optimaal te gebruiken. Vue is een client-side framework. Dat betekent dat de HTML die je aan de browser levert, vaak een  “lege” <div id="app"></div> is. Vue laadt daarna JavaScript-componenten in die div. Als JavaScript uitstaat, gebeurt dat niet — de gebruiker ziet dan vrijwel niets. 

Wanneer JS uitstaat zal de site niet goed werken. Met JS wordt namelijk de data opgehaald, componenten gerenderd, worden formulieren verzonden etc. Dit zal dus allemaal of niet werken of niet getoond worden waardoor je site niet compleet is. Met alleen Nuxt is het anders want dit is SSR, de server (of buildproces) rendert al HTML voordat het naar de browser gaat. Statische HTML zal zichtbaar worden maar interactieve onderdelen werken niet. 

### PERFORMANCE
- **Slimme links:** Nuxt gebruikt smart prefetching, zodra een link in beeld komt (of bijna), laadt Nuxt alvast de JavaScript van die pagina.
- **Hybride rendering:** Met hybrid rendering kun je per route aangeven hoe die wordt geladen (prerender, state-while-revalidatie, incremental static regeneration, SSR uitzetten).
- **Lazy loading van componenten:** Nuxt laadt dat component pas wanneer het echt nodig is → kleinere bundel, snellere eerste laadtijd.
- **Lazy hydration:** Hydration is het moment waarop je statische HTML interactief maakt met JavaScript. Niet alles hoeft meteen gehydrateerd te worden! Het component wordt pas “actief” (met JS) als hij in beeld komt.


## DEVELOPER EXPERIENCE
### PROS
- **Documentatie:** De documentatie is erg duidelijk en veel te vinden online.
- **Community:** Er is een actieve community op Discord, GitHub en forums.
- **Simpel:** Vue is simpel en gemakkelijk te begrijpen wanneer je als developer ervaring hebt met Javascript. 
- **Reactiviteit:** Een van de beste eigenschappen van VueJS is de reactiviteit. Databinding tussen HTML- en JS-code is erg makkelijk.

### CONS
- **Achterlopen:** Wanneer je gaat vergelijken met React en Angular, loopt Vue nog iets meer achter op punten als ‘testing tools’ ‘ui components libraries’.
- **Te veel flexibiliteit:** Vue biedt veel mogelijkheden en flexibiliteit. Dit kan lastiger werken binnen een team, omdat iedereen andere standpunten kent. 

## CONTENT MANAGEMENT EXPERIENCE
Gekozen CMS Prismic
- Simpeler
- Gebruiksvriendelijker
- Visuele editor (drag & drop idee)
- Iets beperkter
