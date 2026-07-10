# Prompts bouwen voor AI-ondersteund groepswerk

> **Levend document**, continu in ontwikkeling.
> Eerste versie najaar 2025. Publiek gepubliceerd 2026-05-20. Laatste update 2026-05-19.
>
> Onderdeel van [Thoughtful Social AI](../README.md). Licentie: CC-BY-SA 4.0.
> [View raw markdown](https://raw.githubusercontent.com/joostliebregts/thoughtful-social-ai/main/nl/PROMPT-BEST-PRACTICES.md) voor copy-paste naar je AI.

> **Wat dit document noemt.** Tijdens het lezen kom je een aantal specifieke tools, projecten en mensen tegen die in de praktijk van de auteur centraal staan. De principes en technieken zijn algemeen toepasbaar, deze concrete referenties dienen als context, niet als vereiste.
>
> - **Dembrane**: een transcript- en dialoog-platform voor groepswerk waar veel van deze prompts in zijn ontwikkeld
> - **Maarten Essenburg**: facilitator-collega (een van de praktijkvoorbeelden in deze doc)
> - **het Doesburg-traject**: een bottom-up gemeenschapstraject rondom een zorgzame gemeenschap (referentiebron voor frustratie-als-brandstof en eigenaarschap-voorbeelden)
> - **de Veldgids**: Social AI Veldgids op [socialaiveldgids.nl](https://socialaiveldgids.nl) (de praktijk-context waar deze prompts in landen)

> **Wat mensen zeggen is al genoeg. Een goede prompt helpt AI om dat zichtbaar te maken, zonder er iets aan toe te voegen.**

Naslagwerk voor iedereen die prompts ontwerpt voor eigen sessies die deze filosofie volgen. Geen generiek "prompt engineering 101", filosofie vertaald naar concrete ontwerpregels. Hieronder de zeven baseline-richtlijnen voor publieke AI-output staan altijd-actief; verderop verwijzen we naar "richtlijn #N" om dezelfde regel snel terug te roepen.

---

## Zeven baseline-richtlijnen voor publieke AI-output

Deze zeven richtlijnen vormen de altijd-actieve basis onder elke prompt waarvan de output de werkruimte verlaat (deelnemer-output, publieke posts, klant-rapporten, AI-output via een platform naar deelnemers). Verderop in dit document verwijzen we kort als "richtlijn #N".

| # | Richtlijn | Eén-regel |
|---|---|---|
| 1 | Em-dash verbod naar buiten | Geen `—` of ` -- `. Komma, dubbele punt, haakjes, of nieuwe zin. Intern (chat, werkdocumenten) prima. |
| 2 | AI-protagonist verbod (met inferentie-uitzondering) | Geen "AI noticed" / "our analysis" / "the algorithm thinks". Uitzondering: expliciete inferentie als (a) open vraag aan de groep, (b) gemarkeerd zonder eigenaarschap-claim, (c) waardevol. WEL: "In de analyse viel op dat... is dit een gedeelde zorg?". NIET: "Onze analyse wijst uit dat...". |
| 3 | Privacy en namen: simpelste menselijke vorm | Default = simpelste geanonimiseerd: "een deelnemer" / "deelnemer 1". Specificiteit alleen als het waarde toevoegt. Hiërarchie: (1) "een deelnemer", (2) rolomschrijving, (3) workstream- of groep-tag, (4) volledige naam alleen met toestemming. Redaction-placeholders nooit zichtbaar. |
| 4 | Recognition test | Toets na output: "ja, dat zeiden wij" of "klinkt als consultant"? Falen, dan herschrijven. |
| 5 | Verbatim-default en strikt-op-transcript | Output draagt hun woorden. Geen verzinsels, geen parafrases die eigenaarschap weghalen. Bij twijfel: "mogelijk onderbelicht". |
| 6 | Document-stem actief sturen | Non-quote tekst (headings, intro-zinnen, verbindweefsel) actief gestuurd: deelnemer-, facilitator-, of project-register. AI-default-Engels = faal-modus, geen toegestane uitkomst. Default: deelnemer-register. |
| 7 | Zorgvuldigheid met gedeeld materiaal | Patronen op groepsniveau eerst; individuele uitspraken alleen waar de context het draagt. Uit context rukken schaadt vertrouwen, ook bij correct citeren. Toets: "Kan iemand jou aankijken nadat deze output is geland en zeggen 'je bent goed omgegaan met wat ik deelde'?". Volledige werkregels zien in [Principes](./SOCIAL-AI-PRINCIPES.md) principe #2, Laag 2. |

Scope: deelnemer-output, publieke posts, klant-rapporten, AI-output via platforms naar deelnemers. Niet: intern werk, scratch-analyse, code. Bij twijfel: behandel als naar buiten.

---

## De kern in drie zinnen

1. AI voegt niets toe. AI maakt zichtbaar wat er al is.
2. Een prompt is geen instructie aan een machine. Het is een ontwerp voor hoe AI menselijke wijsheid mag spiegelen.
3. Als mensen zichzelf niet herkennen in de output, is de prompt mislukt.

---

## Waarom dit ertoe doet: drie momenten

Regels worden pas zinvol als je voelt waarom ze bestaan. Drie momenten uit de praktijk.

### Het fietshelm-moment

Facilitator Maarten Essenburg faciliteerde online over smartphone-gebruik bij kinderen. Moe, laat online, tegelijk gastheer en technicus. Na afloop vroeg hij AI het gesprek te analyseren. AI haalde een quote boven die hij compleet had gemist:

> "Je kind gaat voor het eerst met de fiets naar school, helm op. Komt thuis en zegt: 'De hele klas heeft geen helm. Doe ik ook niet meer, anders hoor ik er niet bij.'"

Precies de kern waar de hele groep mee worstelde. AI gaf zijn eigen woorden terug, georganiseerd zodat het patroon zichtbaar werd. Zijn woorden, zijn inzicht.

*Daarom: "baseer strikt op transcript." Daarom: "gebruik hun exacte woorden."*

### "Mouths falling open"

Een facilitator faciliteerde sessie over wijktransformatie. Na 45 min intense dialoog drukte hij op echo-knop. AI genereerde binnen 10 sec één vraag die hele gesprek samenvatte. De auteur: "From my vantage point, I saw what I can only describe as mouths falling open."

Niet een briljante analyse. Eén vraag, op het juiste moment.

*Daarom: timing boven perfectie. De echo-prompt is 4 regels. De impact was 45 minuten doorbraak.*

### "Literally what we said"

Tijdens een mental-health transformatiesessie verwerkte AI transcript tot concept-deelplan. Reactie deelnemers: "Whoa, wait, this is literally what we said. And now it's in a concept draft."

Transitie van verbazing naar vertrouwen naar eigenaarschap. Herkenning bouwde vertrouwen, vertrouwen maakte ruimte voor eigenaarschap.

*Daarom: het herkenningscriterium. Als ze zeggen "dat zeiden wij" werkt het. Als het klinkt als een consultant, niet.*

---

## De filosofische basis

### De vier facetten als kompas

Elke prompt dient minstens één facet. Facet bepaalt wat de prompt mag doen en wat niet.

| Facet | Wat AI doet | Wat de prompt moet afdwingen |
|-------|-------------|------------------------------|
| **Vergrootglas** | Zichtbaar maken wat er al is | Strikt op transcript baseren; hun woorden behouden |
| **Verbinder** | Verbinding creëren over verschil heen | Tegenstrijdigheden benoemen, niet oplossen; patronen tonen |
| **Ruimtemaker** | Rompslomp overnemen | Structureren zonder te interpreteren; snel, bruikbaar output |
| **Schaalmaker** | Mogelijk maken wat eerder onmogelijk was | Privacy-bescherming; abstractie zonder verlies van herkenning |

**Toets:** welk facet dient mijn prompt? Niet kunnen benoemen = te vaag.

### De acht principes, vertaald naar prompt-ontwerp

| Principe | Wat het betekent voor je prompt |
|----------|--------------------------------|
| **Eigenaarschap door taal** | Instrueer AI om hun exacte woorden te gebruiken, niet te parafraseren. "Communicatieproblemen" vernietigt eigenaarschap; "je praat tegen een muur" behoudt het. |
| **Timing boven perfectie** | Ontwerp prompts die snel bruikbare output leveren. Simpele echo-vraag op juist moment > uitgebreide analyse achteraf. |
| **Ritueel vs intentie** | Verandert deze prompt het ritueel (veilig) of de intentie (gevaarlijk)? AI mag sticky notes vervangen, maar niet de dialoog die erbij hoort. |
| **Jouw woorden, jouw plan** | AI mag structureren en opties bieden, nooit beslissen. Output = startpunt voor gesprek, geen eindproduct. |
| **Iteratie als dialoog** | Eerste versie is nooit definitief. Bouw feedback-loops in: test, evalueer, verfijn. Goede prompt ontstaat niet, evolueert. |
| **Prompt de mensen eerst** | Ontwerp eerst de menselijke ervaring (welke vraag stel je de groep?), dan pas de AI-prompt. De beste AI-prompt faalt als input-ervaring niet klopt. |
| **Bedachtzaamheid als ontwerp** | Instrueer AI om te kijken met de aandacht die er eerder niet was. AI heeft geen tijdsdruk: gebruik die ruimte. Post-sessie: laat AI patronen traceren die mensen missen omdat ze te druk zijn. Multi-sessie trajecten: laat AI verbinden wat maanden geleden gezegd werd met wat nu speelt. Diepgang die facilitators niet kunnen omdat ze door moeten naar de volgende sessie. |
| **Vertrouwen als voorwaarde** | Wie de prompt ontvangt, hoe het materiaal bij hen komt, telt meer dan hoe goed de prompt zelf is. Output-ontwerp checkt altijd: via welke vertrouwensbrug bereikt AI-output de groep? Wie introduceert, deelt, vertaalt? Zonder brug landt zelfs perfecte output niet. |

---

## Prompt de mensen eerst

Fundamenteel principe dat eigen sectie verdient. Meeste prompt-ontwerpers beginnen bij AI: "wat moet AI doen?" Deze filosofie draait het om: "wat moet de mens eerst ervaren?"

### De drie lagen

1. **Veiligheid:** Mensen delen pas echt als ze zich gezien voelen. Geen prompt compenseert onveilige ruimte.
2. **Verhalen verbinden:** Geleefde ervaring valt niet te betwisten. Rationele samenvattingen wel. Vraag om verhalen, niet om meningen.
3. **Taal stuurt denken:** "Hoe kunnen we..." suggereert dat je al weet dat het kan. "Hoe zouden we..." opent voor mogelijkheden.

### De symbiose: menselijke vraag en AI-prompt

Menselijke vraag en AI-prompt = twee kanten van hetzelfde ontwerp. Ze versterken elkaar:

| De menselijke vraag (aan de groep) | De AI-prompt (op het transcript) |
|------------------------------------|----------------------------------|
| "Wat maakt dat je hier zit vandaag?" | "Spiegel de kernmotivaties in hun eigen woorden" |
| "Waar loop je tegenaan?" | "Structureer de frustraties zonder ze weg te poetsen" |
| "Wat zou je morgen anders willen doen?" | "Extract concrete acties, behoud hun taal" |
| "Wat missen we nog?" | "Identificeer afwezigheden en formuleer als vraag" |

Menselijke vraag bepaalt wat in transcript terechtkomt. AI-prompt bepaalt wat daarmee zichtbaar wordt. Zwakke menselijke vraag (gesloten, abstract, onveilig) = geen AI-prompt compenseert dat.

### Wat dit betekent voor prompt-ontwerp

Begin niet met "hoe instrueer ik AI." Begin met: welke vraag stel ik de groep? Voelen mensen zich veilig genoeg om eerlijk te zijn? Vraag ik om ervaring of mening? Is mijn vraag uitnodigend of beperkend?

Pas dan ontwerp je de AI-prompt. De prompt hoeft dit menselijke ontwerp niet te bevatten, maar de kwaliteit hangt er volledig van af.

---

## Vertrouwen als voorwaarde

**Twee lagen.** Vertrouwen heeft een distributie-laag en een zorgvuldigheidslaag. Hier Laag 1 (distributie: wie deelt, hoe komt het binnen). Laag 2 (zorgvuldigheid in hoe AI met gedeeld materiaal omgaat, patronen versus individuen): zie sectie "De bedachtzaamheids- en vertrouwens-laag" verderop, plus [Principes](./SOCIAL-AI-PRINCIPES.md) principe #2 voor volledige werkregels.

Prompt produceert output, output gaat ergens heen. Wie het ontvangt, en hoe het bij hen komt, bepaalt of het werkt. Niet prompt-kwaliteit alleen.

Participatie groeit uit bestaande relaties. Vertrouwen = distributiekanaal. Mensen lezen, reageren, gebruiken iets omdat iemand die zij vertrouwen het aandraagt. Briljante synthese zonder vertrouwensbrug wordt niet gelezen. Hetzelfde stuk gedeeld door facilitator die de groep al kent: krijgt aandacht.

Voor prompt-ontwerper: ontwerp niet alleen de prompt, ontwerp ook de distributie. Wie deelt AI-output? Welk moment? Welke vorm? Wie introduceert? Echo-prompt op juist moment door juiste facilitator > uitgebreid rapport rechtstreeks naar deelnemers.

### Concrete consequenties voor prompt-ontwerp

- Wie AI-output ontvangt mag soms expliciet in de prompt: "Schrijf voor een groep die [facilitator-naam] vertrouwt en gewend is aan [register]."
- Output naar mensen die AI-laag niet kennen, strenger op AI-protagonist-verbod (richtlijn #2). Onbekende AI in onbekende stem = geen vertrouwensbrug.
- Bij twijfel of output binnenkomt: vraag eerst wie het deelt en hoe, niet of prompt te verfijnen valt.

### Spanning

Externe stakeholders (subsidie-gevers, leadership) willen vaak "hoeveelheid output" als KPI. **Vertrouwen laat zich niet optellen.** Wees expliciet wat AI-output wel kan bereiken (zichtbaarheid binnen bestaand vertrouwensnetwerk) en wat niet (vertrouwensnetwerk zelf vormen).

---

## De gouden regel

> **Prompts in deze bundle moeten bijna letterlijke kopieën zijn van prompts die daadwerkelijk gebruikt zijn.**

### Wat niet mag

- Prompts verzinnen die "goed klinken"
- Voorbeelden fabriceren met fictieve namen
- Generieke templates die niet getest zijn
- Beweren dat iets "uit de praktijk komt" als het niet gedocumenteerd is

### Wat wel mag

- Uitleg schrijven rond echte prompts
- Context toevoegen over wanneer en hoe iets gebruikt werd
- Patronen benoemen die uit meerdere bronnen blijken
- Variaties beschrijven die logisch volgen uit gedocumenteerde praktijk

### Checklist bij schrijven

- [ ] Staat dit letterlijk (of bijna letterlijk) in een bronbestand?
- [ ] Kan ik verwijzen naar waar dit vandaan komt?
- [ ] Is het voorbeeld gebaseerd op een echt gedocumenteerd verhaal?
- [ ] Zou de auteur dit herkennen als iets dat hij daadwerkelijk heeft gedaan?

---

## Drie assen voor prompt-architectuur

Elke prompt valt op drie assen tegelijk. Eén as kiezen zonder de andere twee = impliciete keuzes die output sturen. Maak expliciet.

### De drie assen

| As | Wat het bepaalt | Wie kiest | Vocabulaire |
|---|---|---|---|
| **1. Bedachtzaamheidsniveau** | Kwaliteit-van-aandacht in het ontwerp | Mens-ontwerper, vóór prompt | Snel / Doordacht / Diep |
| **2. Effort tier** | LLM-uitvoeringsdiscipline (ISC + capabilities + budget) | Mens stelt tier, Algorithm dwingt discipline | Instant naar Comprehensive (7 tiers) |
| **3. AI-waardeniveau** | Wat AI doet met de input | Mens-ontwerper, afhankelijk van doel | Spiegel / Synthese / Serendipity |

As 1 en As 3 = ontwerper-keuzes (vóór prompt). As 2 = uitvoeringsdiscipline (tijdens prompt). As 3 = orthogonaal aan As 1+2; elke combinatie mogelijk.

### Volgorde van kiezen

1. **Bedachtzaamheidsniveau eerst.** Wat is intentie? Live signaal, post-sessie verdieping, of multi-sessie trajectmatig kijken?
2. **AI-waardeniveau daarna.** Wat moet AI doen? Hun woorden terugkaatsen (Spiegel), patronen verbinden (Synthese), of vragen openen (Serendipity)?
3. **Effort tier schaalt mee.** Hoe hoog zijn stakes? Live + low-stakes = Instant/Fast. Post-sessie + hoge texture-eis = Extended/Advanced. Multi-sessie + cross-trajectvergelijking = Deep/Comprehensive.

### Crosswalk naar bestaande vocabulaires

Vijf vocabulaires in de praktijk wijzen naar dezelfde onderliggende keuze:

| As 1 + As 2 | PROMPT-BEST-PRACTICES | Platform-verlaten? | 4-laags model | Workflow-split |
|---|---|---|---|---|
| Snel + Instant/Fast | "Echo, live" | Platform WEL (LIVE) | Auto-summary + LIVE plenary | Standaard platform |
| Doordacht + Standard | "Post-sessie intern" | Platform WEL (coaching) | Coaching naar facilitators | Platform + fidelity |
| Doordacht + Extended/Advanced | "Post-sessie deelnemer-output" | Platform NIET (naam erop) | Verslag naar deelnemers | Subagent route |
| Diep + Deep/Comprehensive | "Multi-sessie trajectmatig" | Platform NIET (plateau) | Toekomstig | Subagent + deel-rapporten |

### Toepassings-voorbeelden

- **Live echo (10 sec) tijdens een mental-health sessie:** Snel + Fast + Spiegel. Echo-prompt is 4 regels, bedachtzaamheid in vraagontwerp.
- **Post-sessie deelnemer-document (per workstream):** Doordacht + Advanced + Spiegel. Hoge texture-eis, subagent route via Opus, 24-48 ISC.
- **Cross-sessie eigenaarschap-evolutie rapport (Doesburg-traject, M1-M12):** Diep + Deep + Synthese. Vergelijk transcripten over tijd, volledige domain decomposition, 40+ ISC.
- **Multi-sessie blinde-vlek-analyse:** Diep + Comprehensive + Serendipity. "Wat is nooit gezegd in 12 meetings? Welke afwezigheden zijn betekenisvol?"

### Detail-uitwerking per as

- As 1 (Bedachtzaamheidsniveau): zie sectie "Bedachtzaamheidsniveaus" hieronder.
- As 2 (Effort tier): canoniek in een effort-tier framework met "Effort Levels".
- As 3 (AI-waardeniveau): zie sectie "De drie niveaus van AI-waarde" direct hieronder.

---

## De drie niveaus van AI-waarde

Elke prompt opereert op één van drie niveaus. Kies bewust.

| Niveau | AI doet | Gebruik voor | Prompt-voorbeeld |
|--------|---------|-------------|------------------|
| **Spiegel** | Reflecteert exacte woorden, groepeert per thema | Directe feedback, visie-documenten | "Spiegel: maak thema's zichtbaar in hun woorden" |
| **Synthese** | Verbindt patronen, toont frequentie | Samenvattingen, cross-tafel analyse | "Synthetiseer de rode draden over alle gesprekken" |
| **Serendipity** | Onverwachte verbanden, vragen die niemand stelde | Verdieping, blinde vlekken | "Welke onverwachte verbanden zie je?" |

### Anti-patronen per niveau

| Niveau | Doe dit niet | Doe dit wel |
|--------|-------------|-------------|
| **Spiegel** | "Vat samen in heldere taal" | "Gebruik hun exacte woorden" |
| **Synthese** | "Analyseer de thema's" (te vaag) | "Verbind thema's uit tafel 1 en 2, toon overlap en verschil" |
| **Serendipity** | "Dit betekent dat er een vertrouwensprobleem is" (conclusie) | "Zou het kunnen dat 'tijd' voor beide groepen iets anders betekent?" (vraag) |

**Vuistregel:** Spiegel-niveau prompts = veiligst voor eigenaarschap. Hoe hoger het niveau, hoe explicieter je moet labelen wat van AI komt.

---

## Bedachtzaamheidsniveaus

Naast AI-waardeniveau (Spiegel/Synthese/Serendipity) kies je ook **diepte van aandacht**. Hoeveel ruimte de prompt neemt om echt te kijken, niet alleen sneller, dieper dan een mens kan.

| Niveau | AI-aandacht | Wanneer | Wat de prompt moet doen |
|--------|------------|---------|------------------------|
| **Snel** | Echo, live, 10 seconden | Tijdens een sessie | Bedachtzaamheid in vraagontwerp, niet in AI-processing. Prompt kort en gefocust. |
| **Doordacht** | Post-sessie, neemt de tijd | Na een sessie, voor voorbereiding | Instrueer: "Neem de tijd. Traceer verbanden. Kijk naar wat er NIET gezegd is. Formuleer onzekerheden expliciet." |
| **Diep** | Multi-sessie, trajectmatig | Bij langere trajecten met meerdere sessies | Instrueer: "Vergelijk met eerdere transcripten. Hoe verschuift eigenaarschap over tijd? Welke subsystemen worden zichtbaar? Wat is nieuw, wat keert terug, wat is verdwenen?" |

**De kern:** bedachtzaamheid is niet "gebruik meer tijd." Het is een manier van kijken. AI kan enorme hoeveelheden data met elkaar vergelijken; dat kan een mens nauwelijks. Die capaciteit voor diepgang is precies wat AI toevoegt aan facilitatiewerk.

### Temporele instructies (voor Doordacht/Diep niveau)

Voeg standaard toe aan elke prompt boven "Snel" niveau wanneer eerdere data beschikbaar is:

```
ALS eerdere transcripten of analyses beschikbaar zijn:
- Vergelijk kernthema's met eerdere sessies
- Trace verschuivingen in eigenaarschapstaal over tijd
- Benoem wat nieuw is, wat terugkomt, en wat verdwenen is
- Formuleer als: "In sessie [N] zei [spreker] '[X]', nu zegt [spreker] '[Y]', wat verschoof?"
- Kijk naar eigenaarschapsscores: stijgen ze, dalen ze, of stagneren ze?
```

### Scaffolding per model-intelligentie

Niet elk model pikt filosofische framing op. Pas promptcomplexiteit aan model aan:

| Model-niveau | Filosofische framing | Instructiestijl | Voorbeelden |
|-------------|---------------------|----------------|-------------|
| **Hoog** (Claude Opus/Sonnet, GPT-4o) | Ja, "kijk met de aandacht die er eerder niet was" | Principes + vertrouwen op model | 1-2 voorbeelden als richtlijn |
| **Midden** (Haiku, GPT-4o-mini) | Kort, vertaal principes naar concrete regels | Gedetailleerd, elke stap benoemen | 3-4 voorbeelden per patroon |
| **Basis** (kleinere/lokale modellen) | Skip, te abstract | Algoritmisch, beslisboom-instructies | Uitgewerkte voorbeelden met verwachte output |

**Dezelfde instructie op drie niveaus:**

Hoog: *"Kijk naar wat er niet gezegd is. Welke afwezigheden vallen op?"*

Midden: *"Stap 1: Lees het transcript. Stap 2: Maak lijst van onderwerpen die genoemd werden. Stap 3: Vergelijk met agendapunten. Stap 4: Benoem onderwerpen die op agenda stonden maar niet besproken zijn. Stap 5: Formuleer als vraag: 'Niet besproken: [onderwerp]. Is dit bewust of onbewust?'"*

Basis: *"Vergelijk deze twee lijsten. Lijst A: [agendapunten]. Lijst B: [genoemde onderwerpen in transcript]. Schrijf op welke items in Lijst A staan maar niet in Lijst B. Voor elk item schrijf: 'Niet besproken: [item].'"*

### Frameworks alleen inzetten als ze waarde toevoegen

Frameworks zoals Spiral Dynamics value-frames, andere typologieën, cataloog-stijl labels hebben verleidingskracht: leveren snel een "value frames in play" sectie. In praktijk vaak filler.

Default: OFF. Expliciete ON-conditie vereist. Alle drie waar:
1. Participants gebruiken het framework daadwerkelijk in de sessie (woorden, voorbeelden, distinctions die ernaar verwijzen)
2. Naming the frame voegt iets toe dat zonder framework niet zichtbaar is
3. Doelgroep van de output kan met het framework werken (bv. coaches die op SD getraind zijn (interne mirror); niet ruwe groep)

Anti-patroon: SD-sectie inplakken omdat het "completer" oogt. Template-denken, geen bedachtzaamheid. Empirisch: 4 van 4 workstreams in sessie 1 bij een internationale organisatie, Spiral Dynamics-sectie was filler zonder uitzondering. Verifeerd in iteratie v2 naar v5.

### Eigenaarschap-evolutie in prompts

Wanneer een prompt eigenaarschapsscoring bevat EN er eerdere sessiedata is, voeg toe:

```
ALS eigenaarschapsscores uit eerdere sessies beschikbaar zijn:
- Vergelijk scores per persoon of groep over tijd
- Gebruik longitudinale quotes: "In sessie 1 zei [naam] '[X]' (score 0.4),
  nu zegt [naam] '[Y]' (score 0.7), eigenaarschap groeit"
- Benoem patronen: wie groeit, wie stagneert, wie terugvalt?
- Benoem ook systeemfactoren die eigenaarschap beïnvloeden
```

Zie [Eigenaarschap](./OwnershipPrinciples.md) sectie "Evolutie Over Tijd".

---

## De vier kernbegrenzingen

Wanneer je prompt werkt met transcripten of gespreksverslagen, zijn deze vier begrenzingen je fundament. Strikheid hangt af van prompt-type: spiegel-prompt op letterlijke quotes vereist allemaal; brainstorm-prompt op vrije input misschien niet.

```
1. Baseer output strikt op transcript(en), geen verzinsels
2. Bij twijfel: "mogelijk onderbelicht" in plaats van stellige bewering
3. Gebruik hun eigen woorden en terminologie
4. Benoem openstaande punten en tegenstrijdigheden expliciet
```

### Wanneer alle vier, wanneer niet?

| Type prompt | Welke begrenzingen | Waarom |
|-------------|-------------------|--------|
| **Spiegel** (visie, thema's) | Alle vier | Eigenaarschap hangt af van exactheid |
| **Synthese** (patronen, verbanden) | 1, 2 en 4 | Bij synthese mag AI verbinden, maar niet verzinnen |
| **Serendipity** (vragen, blinde vlekken) | 2 en 4 | AI mag vrij observeren, maar moet eerlijk zijn over onzekerheid |
| **Echo** (live, 10 seconden) | 3 | Snelheid essentieel; kernbegrenzing is hun taal behouden |
| **Brainstorm** (vrije input, geen transcript) | Geen verplicht | Andere context, andere regels |

### Waarom elke begrenzing ertoe doet

**1. Strikt op transcript:** Zonder deze instructie gaat AI "aanvullen" met eigen kennis. Resultaat klinkt overtuigend maar is niet van de deelnemers. Een mede-onderzoeker waarschuwt: "That list reads like, oh, this is very convincing, and I believe it's possible. I believe people have said this. But are they the only outliers? How has it been weighted?"

**2. Bij twijfel, benoem het:** AI dat zeker klinkt terwijl het gist, ondermijnt vertrouwen zodra iemand het controleert. "Mogelijk onderbelicht" geeft ruimte voor correctie zonder gezichtsverlies.

**3. Hun eigen woorden:** "Je praat tegen een muur" draagt eigenaarschap. "Communicatieproblemen" niet. Parafraseren breekt de herkenning.

**4. Tegenstrijdigheden benoemen:** Het oplossen van tegenstrijdigheden is mensenwerk. Als twee groepen iets anders willen, moet de prompt dat tonen, niet wegwerken.

---

## Quote-density als ontwerpkeuze

Bij output die quotes uit transcripten gebruikt: stel quote-cap per output-sectie. Cap voorkomt reading-overload. Te veel quotes = patroon onvindbaar; te weinig = werk in praktijk parafrase.

### Drop-priority bij over-cap

1. **Duplicates**, zelfde punt dat ander quote al maakt
2. **Paraphrasables**, meaning gaat niet verloren bij paraphrase
3. **Stylistic flourish**, geen load-bearing content

### Keep-priority

1. **Contestation-anchors**, quotes die load-bearing disagreement dragen
2. **Specific tensions met ongebruikelijke phrasing**, formuleringen die uniek zijn voor de spreker
3. **Unusual phrasings die de groep zal herkennen**, herkenningscriterium-anker

### Model-specifieke calibration

Cap-getallen verschillen per model. Gemini 2.5 Pro: target 10-12 quotes per WS-section, hard cap 15 (soft caps van 7 worden genegeerd tenzij scratchpad). Opus 4.6 subagents: 4-7 quotes haalbaar zonder scratchpad. Verschil zit in model self-discipline, niet in principe. Voor platform-specifieke calibration-getallen: zie de documentatie van het transcript-platform dat je gebruikt. Principe (cap + drop/keep-priority) is universeel.

---

## Het herkenningscriterium

De ultieme toets voor elke prompt-output:

```
ALS deelnemers denken "ja, dat zeiden wij" → SUCCES
ALS deelnemers denken "dat klinkt als een consultant" → MISLUKT
```

Bouw dit criterium in als instructie in je prompt:

```markdown
SUCCESCRITERIUM: Deelnemers moeten zichzelf herkennen.
Als zij denken "ja, dat zeiden wij" → succes.
Als zij denken "dat klinkt als een consultant" → mislukt.
```

---

## Het labelingsprincipe: wie zei wat

Output moet altijd onderscheid maken tussen wat mensen zeiden en wat AI opmerkt. Niet optioneel.

### Structuur

```markdown
### Wat deelnemers zeiden
[Letterlijke quotes, hun woorden, hun framing, eigenaarschap intact]

### Wat AI opmerkt (ter inspiratie)
[Patronen, verbanden, onverwachte observaties, duidelijk gelabeld als AI]
```

### Waarom dit werkt

- "Wat deelnemers zeiden" = hun eigenaarschap intact, herkenning mogelijk
- "Wat AI opmerkt" = expliciete markering dat dit interpretatie is
- "Ter inspiratie" = signaal dat dit optioneel is, niet prescriptief

Zonder labeling kunnen mensen niet onderscheiden wat van hen is en wat AI toevoegde. Labelingsprincipe maakt "AI als spiegel" mogelijk zonder eigenaarschap te verliezen.

---

## Multi-voice handling

Een groep is geen stem. Toch verleiding voor AI om collectieve-intent te overstaten: *"the group named"*, *"you came to the table to"*, *"you proposed"*. Fraseringen impliceren meer gedeelde intentie dan multi-voice rooms hebben. Drie regels voor multi-voice output.

### Voice texture default

Default-phrasing voor multi-voice gesprekken:
- `voices in the group ranged from [verbatim X] to [verbatim Y]`
- `one voice raised X; another responded Y`
- `several voices echoed [verbatim phrasing], one voice held back`

Wanneer wel collectief noemen: alleen wanneer *genuine consensus emerged*, zelfde positie, meerdere voices, geen counter-position in transcript.

### Anti-pattern list (verbieden in prompt)

| Anti-pattern | Waarom verbieden | Vervang door |
|---|---|---|
| "you came to the table to..." | Impliceert gedeelde intentie + fysieke metafoor | "voices joined the conversation around..." |
| "the group named..." | Impliceert collective speech act | "one voice named X; another responded Y" |
| "you proposed..." | Impliceert collectief voorstel | "[name/voice] put forward..." (met role-attribution, geen naam) |
| "you came in with..." | Impliceert gedeelde houding | "voices entered with a range of openings..." |
| "the group agreed that..." (zonder bewijs van consensus) | Impliceert consensus die er niet was | "no counter-position emerged on..." |

### Load-bearing disagreement pattern

Wanneer twee voices opposite positions namen die niet convergeerden, behandel disagreement als first-class output, niet parenthetical aside. Verbatim pattern in de prompt:

> *"Two distinct positions emerged here that did not converge in the room: one voice argued [verbatim X], another responded [verbatim Y]."*

Detection criteria, alle drie waar:
1. Twee+ voices namen clearly opposite positions op same underlying question
2. Geen voice retracted of softened
3. Group bewoog door zonder reconciling

### Contestation priority: scope beats process

Bij meerdere load-bearing-disagreement-kandidaten: kies degene over **scope / mandate / ownership** boven **process / inclusion / representation**. Open *"should we...?"* vragen zonder actively-held opposing positions tellen NIET als load-bearing; dat is open-vraag-uitnodiging, geen contestatie.

Voorbeeld:
- **Load-bearing (scope):** "Voice A wil dit project op €50K cappen; Voice B vindt dat we minimaal €200K nodig hebben." Twee actively-held opposite positions, dezelfde vraag, geen convergentie.
- **Niet load-bearing (open question):** "Should we expand to a third workshop?", geen voices die expliciet pro/contra positie nemen.

### Waarom dit een eigen sectie verdient

Multi-voice handling = geen detail. Output die collectieve intent overstating bevat = meest voorkomende vorm waarin facilitator-output als consultant-stem leest. Lezers herkennen meteen dat "you came to the table to" niet uit hun mond komt, eigenaarschap weg. Hard regels in prompt, niet best-effort. Empirisch verifeerd via een pilot bij een internationale organisatie (sessie 1, v1 naar v5 iteratie-cyclus): hard rule + (a)/(b) replacement-strategieën reduceren collective-intent-overstatement tot 0 in v4-v5.

---

## DIRECT vs INFERENCE markeren

Prompt-patroon uit een latere prompt-architectuur dat elke analyse-prompt sterker maakt.

```markdown
Wees expliciet over wat je DIRECT uit het transcript haalt
vs. wat je INTERPRETEERT.
Markeer elke claim als:
- [DIRECT], letterlijk citaat of expliciete uitspraak
- [INFERENCE], jouw interpretatie van wat gezegd werd
```

### Waarom dit waardevol is

Maakt verschil zichtbaar tussen "iemand zei letterlijk X" en "ik leid af dat Y." Voorkomt dat AI-interpretaties als feiten worden gepresenteerd. Bouwt vertrouwen: facilitators kunnen precies controleren waar output vandaan komt.

---

## Dubbele zekerheidsscoring

Nog een patroon uit prompt-evolutie: splits "hoe zeker ben ik?" in twee aparte scores.

| Score | Wat het meet | Voorbeeld |
|-------|-------------|-----------|
| **Bewijs_sterkte** (0.00-1.00) | Hoe sterk is het bewijs in het transcript? | 0.9 = meerdere letterlijke quotes; 0.3 = één vage verwijzing |
| **Interpretatie_zekerheid** (0.00-1.00) | Hoe zeker ben ik van mijn lezing? | 0.9 = helder; 0.4 = meerdere lezingen mogelijk |

**Wanneer bruikbaar:** bij analyse-prompts waar je wilt dat AI eerlijk is over basis van claims. Niet nodig bij simpele spiegel-prompts.

---

## Zekerheidsniveaus in taal

Hoe AI onzekerheid moet formuleren, van zeker naar onzeker.

| Niveau | Formulering | Wanneer |
|--------|-------------|---------|
| **1, Direct** | "Deelnemers zeiden letterlijk: '[quote]'" | Letterlijk citaat beschikbaar |
| **2, Patroon** | "Meerdere deelnemers refereerden aan [thema]" | Meerdere uitspraken wijzen dezelfde kant op |
| **3, Interpretatie** | "Mogelijk onderbelicht: [onderwerp]" | Afgeleid uit context, niet letterlijk gezegd |
| **4, Afwezigheid** | "Niet genoemd in dit gesprek: [onderwerp]" | Iets dat je verwacht maar niet terugvindt |
| **5, Open** | "Nog af te stemmen: [tegenstrijdigheid]" | Onopgeloste spanning tussen perspectieven |

**Anti-patroon:**
- Niet: "Dit betekent dat er een vertrouwensprobleem is" (conclusie)
- Wel: "Zou het kunnen dat 'tijd' voor beide groepen iets anders betekent?" (vraag)

---

## Transcript-artifacts handling

Transcripten bevatten artifacts: mishearing, garbled acronyms, names mis-transcribed, audio-drops die woorden afkappen. Verbatim quote met artifact die meaning unintelligible maakt = probleem. Drie opties.

### De drie opties bij mishearing

| Optie | Wanneer | Voorbeeld |
|---|---|---|
| **(a) Flag inline** | Lezer kan met flag verder, artifact is een woord | `"we hadden [likely: ACRONYM] gesprek met..."` (transcript zei misgehoorde variant) |
| **(b) Pick different verbatim segment** | Hetzelfde meaning carries in ander segment van dezelfde voice | Vervang quote door andere quote van zelfde spreker waar artifact niet inzit |
| **(c) Sidestep via paraphrase** | Geen ander verbatim mogelijk; rest van quote toch waardevol | Lift de claim eruit zonder aanhalingstekens, met markering dat het paraphrase is |

**Niet doen:** silent reproduceren van artifact. Lezer ziet een woord dat geen woord is, vertrouwen breekt.

### Bekend-artifact-lijst per project

In prompt expliciet noemen welke artifacts bekend zijn voor dit project. Voorbeelden uit echte projecten:

| Artifact (transcript) | Likely correction | Project |
|---|---|---|
| `class` | `Quass` | (voorbeeld) |
| `EFAD` | `ACRONYM` | (voorbeeld misgehoord acroniem) |
| `co business` | `core business` | (voorbeeld) |

Bekend-artifact-lijst is project-specifiek. Hoort niet in master document, hoort in per-klant pointer-file.

### In de prompt

```markdown
Bij verbatim quote met transcription-artifact (mishearing, garbled term) die meaning unintelligible maakt:
- (a) flag inline: [likely: corrected_term]
- (b) pick different verbatim segment
- (c) sidestep via paraphrase (zonder quotation marks)

Bekend-artifact-lijst voor dit project:
[expliciete lijst per project]

Niet silent reproduceren.
```

### Waarom dit een eigen sectie verdient

Zelfde mechanisme als eigenaarschap-door-taal (principe 4): hun woorden tellen, maar een artifact-woord is niet hun woord, het is een transcriptie-fout. Verbatim-default (kernbegrenzing #3) = geen excuus om artifacts door te laten; hun bedoeling preserveren is regel onder verbatim-regel.

---

## Prompt-anatomie: vormen en variaties

Geen één manier om een prompt te bouwen. Echo-prompt = 4 regels. Thematische synthese-prompt = 30. Wat ze delen is intentie, niet format. Hieronder uitgebreide bouwblok voor complexere prompts, maar onthoud: de krachtigste prompt is de kortste.

```markdown
**Rol**: [Specifieke expertise, wees precies]

**Context**: [Inputbronnen, projectachtergrond, relevante waarden]

**Cruciale randvoorwaarden**:
- Baseer output strikt op transcript(en), geen verzinsels
- Benoem openstaande punten en onzekerheden expliciet
- Gebruik hun eigen woorden en terminologie
- [Aanvullende specifieke begrenzingen]

**Instructies**:
1. [Eerste stap, vaak analyse of data review]
2. [Tweede stap, vaak categorisering of prioritering]
3. [Derde stap, vaak synthese of verbinding leggen]
4. ALS [conditie] DAN [specifieke aanpak]
5. [Laatste stap, vaak formattering en transparantie]

**Output format**:
[Specifieke structuur met koppen, secties, transparantieblokken]
```

### Per sectie

| Sectie | Functie | Veelgemaakte fout |
|--------|---------|-------------------|
| **Rol** | Geeft AI specifieke lens | Te vaag ("je bent een AI-assistent") i.p.v. specifiek ("je bent een nauwkeurige notulist die expliciet genomen besluiten vastlegt") |
| **Context** | Vertelt AI wat het krijgt en waarom | Vergeten te benoemen hoeveel transcripten, welk type sessie, of er eerdere AI-output is |
| **Randvoorwaarden** | Begrenzingen die eigenaarschap beschermen | De vier kernbegrenzingen vergeten |
| **Instructies** | Stappenplan in actieve taal | Te weinig stappen (AI improviseert) of geen conditionele logica |
| **Output format** | Hoe resultaat eruitziet | Geen labeling (wat deelnemers zeiden vs wat AI opmerkt) |

### Wanneer minder genoeg is

Niet elke prompt heeft alle secties nodig. Drie vormen die in praktijk werken:

| Vorm | Wanneer | Voorbeeld |
|------|---------|-----------|
| **Volledig bouwblok** (5-6 secties) | Post-sessie analyse, visie-document, implementatieplan | Thematische synthese, WHY-prompt |
| **Compact** (rol + randvoorwaarden + output) | Specifieke extractie, gerichte analyse | Kernbesluiten capture, energie-analyse |
| **Minimaal** (context + één instructie) | Live interventie, snelle reflectie | Echo-prompt, frisse-blik-vraag |

Echo-prompt bewees dat 4 regels genoeg zijn voor de krachtigste interventie. Complexiteit is geen kwaliteit.

---

## De transparantie-footer

Bij documenten die naar deelnemers gaan = transparantie-footer waardevol. Hoe zwaarder het document (visie, plan, synthese), hoe belangrijker. Bij live echo-vraag van twee zinnen: overkill.

```markdown
> **Over deze output:** Deze [synthese/analyse/visie] is gemaakt door AI
> op basis van jullie gesprek van [datum]. Het is een hulpmiddel om jullie
> eigen ideeën te structureren, niet perfect, maar een startpunt voor
> verder gesprek. Dit blijft jullie verhaal; de AI helpt alleen bij het
> bundelen en verbinden van jullie ideeën.
```

---

## De prompt als architectuur, niet als losse instructie

Een van de belangrijkste meta-lessen uit de verrijkingssessies van februari 2026:

> **De prompt IS de techniek.** Vooral in fase 2 en 3 zijn de meegeleverde prompts geen losse instrumentjes om een theorie uit te voeren; de prompt ís de architectuur van de theorie.

Behandel prompt-ontwerp niet als afterthought. Prompt bepaalt wat AI ziet, hoe het structureert, welke taal het gebruikt, wat het wel/niet mag concluderen. Zwakke prompt met sterke theorie = zwakke output. Sterke prompt met beperkte theorie = verrassend goede output.

### Constraints op één plek (Saint-Exupéry strip principle)

Een prompt is af niet wanneer alles wat nodig is erin staat, maar wanneer alles wat dubbel staat eruit is. Saint-Exupéry's *"perfection is achieved when there is nothing left to take away"* geldt ook voor prompt-architectuur. Toepassing: als een platform een project-context-veld heeft dat één keer geüpload wordt en automatisch bij elke call meegegeven, horen universele constraints daar, niet herhaald per-prompt. Hetzelfde voor de zeven baseline-richtlijnen (em-dash verbod, AI-protagonist verbod, privacy/namen regel, recognition test, verbatim-default, document-stem, zorgvuldigheid): zit altijd-actief in system-layer, niet per-prompt. Per-prompt-instructie draagt alleen wat uniek is voor dat moment.

| Laag | Wat hier hoort | Voorbeeld |
|---|---|---|
| **System / project-context** | Universele constraints die altijd gelden | De zeven baseline-richtlijnen, platform project-context-veld, output-language |
| **Prompt-context (boilerplate)** | Constraints voor dit type prompt | Verbatim-default, kernbegrenzingen, output-format |
| **Per-prompt-instructie** | Unieke instructie voor dit moment | Specifieke vraag, focus-thema, deze-sessie-context |

Dubbel staande constraints, strippen niet stapelen. Iedere extra herhaling = risico op afwijking-tussen-versies, niet op stevigheid.

---

## Frustratie als brandstof, niet wegwerken

Een prompt mag frustratie niet wegpoetsen. Een van de belangrijkste lessen uit het Doesburg-traject.

```
Niet: "Formuleer uitdagingen constructief"
Wel:  "Frustraties mogen er zijn zoals ze zijn uitgesproken"
```

**Waarom:** Toen in het Doesburg-traject de financiering wegviel, ontstond hoogste niveau eigenaarschap in de hele dataset. Community besefte: "we moeten zelf de regie pakken." Was AI ingezet om het verlies te "herkaderen tot nieuwe kansen," dan was deze vitale rebellie in de kiem gesmoord.

**Regel:** Gebruik AI om de complexiteit van frustratie te structureren. Gebruik AI nooit om het ongemak weg te poetsen.

---

## Prompt-evolutie: van v2 naar v3

Rode lijn in hoe prompts beter worden, op 16 maanden ervaring.

| Wat veranderde | v2 (vroeger) | v3 (nu) |
|----------------|-------------|--------------|
| **Zekerheid** | Één confidence-getal | Twee scores: bewijs_sterkte + interpretatie_zekerheid |
| **Updates** | Elke analyse stond op zichzelf | Vergelijking met vorige run (change logs, diffs) |
| **Privacy** | Niet benoemd | Expliciete regels (rolomschrijvingen, nooit namen, drempels) |
| **Ruis** | Geen concept van ruis | Ruis-indicatoren, patroonstabiliteit, anomaliedetectie |
| **Reflectie** | Geen | Verplichte zelfreflectie ("Wat heb ik mogelijk gemist?") |

**Overkoepelende beweging:** van single-pass analyse naar lerend systeem. Prompts worden beter als ze ingebouwde eerlijkheid hebben over onzekerheid, vergelijking met eerdere runs, en zelfreflectie.

---

## Serendipity: de ongestelde vraag

De krachtigste prompt-output is vaak niet het antwoord op de vraag, maar de vraag die niemand stelde.

### Gestructureerde serendipity

```markdown
Rol: Je bent een nieuwsgierige, intelligente luisteraar die het
onzichtbare zichtbaar maakt, niet door te concluderen, maar door
vragen te stellen.

Instructies:
1. Lees alle transcripten en eerdere samenvattingen
2. Identificeer spanningen, afwezigheden, onverwachte verbanden
3. Formuleer als vragen, niet als conclusies
4. Label expliciet dat dit AI-observaties zijn

Output:
### Wat AI opmerkt (ter inspiratie)

**Spanningen die opvallen:**
[Observatie + vraag voor de groep]

**Afwezigheden die opvallen:**
[Wat niet gezegd werd + vraag waarom dat zou kunnen zijn]

**Onverwachte verbanden:**
[Verband + vraag of dit klopt]

→ Dit zijn observaties en vragen, geen conclusies.
  De groep bepaalt wat hiermee te doen.
```

**Essentieel:** Serendipity werkt alleen als het als vraag wordt geformuleerd, niet als conclusie. "Niemand noemde mantelzorg. Is dit bewust of onbewust?" opent een deur. "Er is een blinde vlek rond mantelzorg" sluit er een.

---

## De zelftest voor prompt-ontwerp

Voor je een prompt finaliseert, loop deze checks door. Drie lagen: ontwerper-toets (9 vragen), bedachtzaamheids- en vertrouwens-laag (attitude waarmee je de toetsen doet), technische zelftest (9 checks).

### De ontwerper-toets voor prompts

| # | Vraag | Wat het bewaakt |
|---|-------|-----------------|
| 1 | **Staat AI centraal, of de mens?** AI mag instrument zijn, nooit subject. | De prompt instrueert AI om te spiegelen, niet om te beslissen |
| 2 | **Klinkt dit als ervaring, of als theorie?** | De prompt vraagt om concrete taal, niet om abstracties |
| 3 | **Claim ik credit die niet van mij is?** | De prompt labelt wat van deelnemers komt vs wat AI toevoegt |
| 4 | **Is dit Engels in vermomming?** Toets: zou een facilitator dit woord gebruiken? | De prompt gebruikt Nederlands waar mogelijk (betrokkenen, niet stakeholders) |
| 5 | **Schrijf ik voor, of nodig ik uit?** Spanningen zijn geen fouten. | De prompt presenteert tegenstrijdigheden als keuzemomenten, niet als problemen |
| 6 | **Heb ik iets verzonnen om het mooier te maken?** | De prompt dwingt strikt-op-transcript af |
| 7 | **Zou dit de hoofdvraag beantwoorden?** Helpt dit mensen om gehoord te worden? | De prompt dient uiteindelijk de toetssteen |
| 8 | **Kan deze output iemand persoonlijk raken in plaats van een patroon zichtbaar maken?** Niet als verbod, als afweging. Soms is de persoon raken precies wat nodig is; vaker niet. | De prompt vraagt focus op patronen in de groep, niet op uitvergroting van wat één voice zei |
| 9 | **Heb ik nagedacht over wie dit ontvangt, waartoe het bijdraagt, en hoe het past in het grotere proces?** | De prompt is bewust over context: wie krijgt het te zien, in welke positie staan ze, wat hebben ze nodig om het goed te kunnen ontvangen |

### De bedachtzaamheids- en vertrouwens-laag

Tussen ontwerper-toets en technische check ligt iets dat in geen van beide volledig zit: de **attitude waarmee je de toetsen doet**. Sneller doorlopen = vinkjes; bedachtzamer = betere prompts.

**Bedachtzaamheid, stop en denk na.**

Wat is intentie hier? Wat probeer ik te bereiken? AI is razendsnel met patronen, maar patroon-match = hypothese, geen conclusie. Twee modes mogelijk: patroon-gretigheid (signaal zien, matchen, presenteren als waarheid) of bedachtzame herkenning (signaal zien, checken tegen werkelijkheid, presenteren als hypothese met bewijs). Alleen de tweede telt.

Drie zelfvragen bij bedachtzaamheid:
- *Wat heb ik nog niet gezien? Wat zou ik missen als ik te snel concludeer?*
- *Wat is de intentie hier, waartoe draagt deze output bij in het grotere proces?*
- *Heb ik mezelf de ruimte gegeven om dieper te kijken, ook al voelt sneller productiever?*

**Vertrouwen, gaan we hier zorgvuldig om met wat mensen delen?**

Vertrouwen = geen abstracte voorwaarde. Operationeel: kan iemand jou aankijken nadat deze output is geland en zeggen "je bent goed omgegaan met wat ik deelde"? AI moet die vertrouwens-relatie vertalen naar prompt-regels. Concreet: focus op patronen in de groep, niet op uitvergroting van wat één persoon zei. Persoonlijk raken zonder reden schaadt vertrouwen, niet alleen tussen AI en deelnemer, ook tussen facilitator en deelnemer.

Vier zelfvragen bij vertrouwen:
- *Focust de output op groep-patronen, of vergroot het uit wat één voice zei?*
- *Wie ontvangt dit, en in welke positie staan ze om het goed te kunnen brengen?*
- *Wat zou nodig zijn om deze output goed te laten landen? Vertrouwensbrug, timing, framing?*
- *Gaan we hier goed om met wat ze hebben gedeeld? Kunnen ze ons aankijken nadat dit landt?*

Deze laag staat boven de andere toetsen, niet als extra regel maar als grondhouding. Een prompt die de ontwerper-toetsvragen passeert maar deze laag overslaat = technisch correct werk dat vertrouwen kan beschadigen.

### De technische zelftest (9 checks)

- [ ] Is het AI-waardeniveau (Spiegel/Synthese/Serendipity) passend voor de taak?
- [ ] Bewaren de instructies de taal van deelnemers op spiegel-niveau?
- [ ] Zijn AI-observaties expliciet gelabeld als zodanig?
- [ ] Zit er een herkenningscriterium in de succescriteria?
- [ ] Dient het output-format de dialoog, niet de documentatie?
- [ ] Mogen emoties en frustraties bestaan zoals ze zijn?
- [ ] Zijn serendipity-elementen geformuleerd als vragen, niet als conclusies?
- [ ] Focust de output op patronen in de groep, niet op uitvergroting van individuele uitspraken?
- [ ] Is de vertrouwens-distributie bedacht: via wie komt deze output binnen, wat heeft die persoon nodig om het goed in te brengen?

---

## Pre-output checklist: model-self-verification ingebed in prompt

Zelftest hierboven = voor ontwerper, vóór sessie. Pre-flight (volgende sectie) = ook voor ontwerper, vóór live. Deze sectie = wat AI zelf controleert vóór output: checklist ingebed in de prompt.

Reden: sommige modellen (Gemini 2.5 Pro empirisch geverifieerd via een v1-naar-v5 cyclus bij een internationale organisatie) vergeten of conflateren regels die los in de prompt-body verspreid staan. Expliciete 5-7 item checklist aan einde van prompt, expliciet als *"Voer voor submit deze gates uit"*, werkt beter dan rules in body. Opus-class modellen doen dit impliciet; voor hen vaak overbodig.

### Template voor pre-output checklist (in de prompt zelf)

```
Voer voor je output submit:

1. Quote count binnen target range? (specifieer cap)
2. Zero proper first names in output?
3. Disagreement pattern toegepast op scope/mandate contestation (waar mogelijk)?
4. Alle headings sentence case (geen Title Case)?
5. Geen mishearings unflagged (transcript-artifacts gemarkeerd of weggelaten)?
6. Geen physical-presence metaphors in digital-session output?
7. AI-protagonist-taal vermeden (geen "we noticed", "our analysis")?

Indien een gate faalt: stop, herzie, dan submit.
```

### Wanneer gebruiken

- Voor high-stakes participant-output via model dat self-discipline-issues heeft (Gemini 2.5 Pro era).
- Bij prompts die meerdere regels combineren die anders in body verspreid zouden staan.
- Voor lange outputs (>500 woorden) waar drift waarschijnlijk is.

Voor Opus-class modellen vaak overbodig. Voor Gemini-class modellen: standaard inbouwen.

### Niet verwarren met de zelftest voor de ontwerper

| Vergelijking | Wie test | Wanneer |
|---|---|---|
| Ontwerper-toets (9 vragen, incl. bedachtzaamheid + vertrouwen) | Mens-ontwerper | Vóór prompt finaliseren |
| Bedachtzaamheids- en vertrouwens-laag (attitude-check) | Mens-ontwerper | Tussen ontwerper-toets en technische check |
| Technische zelftest (9 checks) | Mens-ontwerper | Vóór prompt finaliseren |
| Pre-flight checks | Mens-ontwerper | Vóór live sessie, na finaliseren |
| **Pre-output checklist** | **AI-model** | **Tijdens elke prompt-uitvoering, vóór submit** |

Voor model-specifieke calibratie (welke checklist-items op welk model nodig zijn): raadpleeg de documentatie van het transcript-platform dat je gebruikt voor model-specifieke caveats.

---

## Pre-flight: de laatste check voor je live gaat

> **Eén minuut die voorkomt dat je prompt live faalt.**

Prompt die er goed uitziet ≠ prompt die werkt. Pre-flight = vangnet, vijf checks per sessie-type, 30 seconden. NADAT prompt geschreven, VOORDAT live.

### Per sessie-type

**Live echo (real-time, <30 seconden output)**
- [ ] Draai prompt op **echte model** dat in sessie draait (niet ontwikkelmodel)
- [ ] Output max 2 zinnen, test met rommelig transcript, niet je mooiste voorbeeld
- [ ] Geen consultant-taal in output, check herkenningscriterium
- [ ] Echo werkt ook als transcript maar 3 min bevat (korte groep)
- [ ] Fallback als echo niks oplevert (zie escape-prompt hieronder)

**Subgroep-dialoog (parallel groepen, kruisbestuiving)**
- [ ] Test met input van twee groepen die tegenstrijdige dingen zeggen
- [ ] Kruisbestuiving toont overeenkomsten EN verschillen, niet alleen overlap
- [ ] Deelnemerswoorden behouden, geen parafrase, geen "thema's"
- [ ] Output past op één scherm (facilitator moet live kunnen voorlezen)
- [ ] Privacy: geen namen, alleen rolomschrijvingen

**Post-sessie analyse (na afloop, diepere verwerking)**
- [ ] Prompt werkt op volledige transcriptlengte (check token-limiet)
- [ ] Labeling intact: "Wat deelnemers zeiden" gescheiden van "Wat AI opmerkt"
- [ ] Transparantie-footer aanwezig bij output naar deelnemers
- [ ] Frustraties en tegenstrijdigheden blijven staan, niet weggepoetst
- [ ] Bij meerdere transcripten: bronverwijzing per claim

**Thema-clustering (AI als spiegel naast handmatige clustering)**
- [ ] AI-clustering = suggestie, niet conclusie, formulering check
- [ ] Output bevat originele woorden per cluster, niet alleen themalabels
- [ ] Vergelijkbaar met handmatige clustering, test: zou facilitator dit herkennen?
- [ ] Bij twijfel: "mogelijk onderbelicht" in plaats van stellige bewering
- [ ] Output visueel scanbaar (bullets/structuur, geen lap tekst)

### Hoe je test

1. Pak oud transcript (welk dan ook)
2. Draai prompt op model dat je in sessie gaat gebruiken
3. Lees output hardop voor, klinkt het als iets dat de facilitator zou zeggen?
4. Laat iemand anders output lezen zonder context, herkennen ze de deelnemers?

Inhoud van test-transcript doet er niet toe. Je test het **gedrag** van de prompt: volgt regels? Gebruikt hun woorden? Breekt bij rommelige input?

---

## De escape-prompt: als alles faalt

> **Eén prompt die altijd werkt, op elk model, in elke situatie.**

Live zit en prompt hapert, output onzin, of je vertrouwt niet meer wat eruit komt, druk op deze knop. Noodrem.

```markdown
Vat samen wat er gezegd is in de afgelopen 10 minuten.
Gebruik uitsluitend de woorden van de sprekers zelf.
Geen interpretatie, geen thema's, geen analyse.
Geef maximaal 5 bullets van elk één zin.
Begin elke bullet met een letterlijk citaat.
```

**Waarom dit altijd werkt:**
- Geen interpretatie = geen kans op foute conclusies
- Deelnemerswoorden = eigenaarschap intact
- 5 bullets = scanbaar, voorleesbaar, niet overweldigend
- Werkt op GPT 3.5 tot Opus, geen intelligentie vereist

**Wanneer gebruiken:**
- De echte prompt geeft output die niet klopt
- Je hebt twijfel of de output de groep goed representeert
- Technisch probleem en je moet SNEL iets leveren
- Eerste keer werken met een nieuw model

---

## Model-bewustzijn: test op je doelmodel

> **Een prompt gebouwd op Opus die je draait op GPT 4.1 is een ongeteste prompt.**
>
> Zie ook: **Scaffolding per model-intelligentie** (sectie Bedachtzaamheidsniveaus) voor hoe je promptcomplexiteit aanpast per model.

Belangrijkste regel = simpel: **test je prompt op het model waarop hij gaat draaien.** Niet je favoriete model. Niet het slimste model. Het exacte model dat in sessie actief is.

### Waarom dit ertoe doet

Modellen verschillen in hoe ze instructies opvolgen. Prompt die op Opus prachtig werkt, kan op ander model:
- Instructies over "gebruik hun woorden" negeren en toch parafraseren
- Langere output geven dan gevraagd (token-limieten werken anders)
- Minder goed omgaan met conditionele logica ("ALS... DAN...")
- Zekerder klinken dan bewijs rechtvaardigt

### Praktische vuistregels

| Wat je checkt | Waarom |
|---------------|--------|
| **Volgt het model "hun exacte woorden"?** | Sommige modellen parafraseren standaard, je moet het afdwingen |
| **Houdt het zich aan lengtebeperkingen?** | "Max 2 zinnen" werkt op Opus; andere modellen negeren het soms |
| **Hoe gaat het om met tegenstrijdigheden?** | Sommige modellen lossen tegenstrijdigheden op i.p.v. ze te tonen |
| **Klinkt het als consultant of als spiegel?** | Grotere modellen zijn vaak "behulpzamer", wat hier juist ongewenst is |
| **Werkt de conditionele logica?** | "ALS consensus DAN benoem, ALS verdeeld DAN bewaar beide", test dit |

### Als het model wisselt

Wanneer een platform overgaat naar een nieuw model: draai actieve prompts opnieuw door pre-flight. Eén middag werk voorkomt live verrassingen.

### High-stakes output vereist model-kwaliteit boven prompt-richness

Output naar mensen (deelnemers, leadership) met praktitionersnaam erop, waar texture > speed: kies model-kwaliteit boven prompt-richness. Plateau-effecten van mindere modellen op multi-voice differentiation, contestation-depth, specific-anchor retention, meta-frame (wat NIET is gezegd) = niet via prompt-tightening te dichten. Bewezen via 5-iteratie cyclus (v1 naar v5) tegen subagent-baseline bij een internationale organisatie.

Beslissingsregel:

| Output-type | Model-pad |
|---|---|
| Live plenary, internal coaching, throwaway analyses | Elk model dat de taak aankan; Gemini-class voldoende |
| Coaching mirrors voor facilitators (intern) | Gemini-class voldoende, texture-tolerantie hoger |
| **High-stakes participant-output (naam erop, externe distributie)** | **Opus-class via subagent-route tegen transcripten direct**; platform-Gemini-pad verlaten |
| Cross-WS parallellen openings, Custom Reports naar leadership | Opus-class subagent-route |

Pre-flight test op doel-model = verplicht: prompt die op Opus prachtig werkt kan op Gemini stil falen op exact de criteria die deelnemer-output dragen.

Voor model-specifieke plateau-effecten + workflow-split tabel: raadpleeg de documentatie van het transcript-platform dat je gebruikt voor model-specifieke caveats.

---

## Spanningen in prompt-ontwerp

Spanningen zijn geen fouten. Het zijn keuzemomenten. Geldt ook voor prompt-ontwerp. Hieronder terugkerende spanningen, met de keuze die je steeds opnieuw maakt.

### Spanning 1: Letterlijk citeren vs begrijpelijk maken

Neiging: "vat samen in heldere taal." Gevaarlijk: parafraseren vernietigt eigenaarschap. "Je praat tegen een muur" draagt energie; "communicatieproblemen" niet.

**Maar:** soms is letterlijk citeren niet genoeg. Als zes mensen hetzelfde zeggen in andere woorden, moet je kiezen: citeer alle zes, of laat AI het patroon benoemen? Hangt af van niveau: spiegel-niveau citeer letterlijk, synthese-niveau mag patronen benoemen mits originele woorden ernaast.

### Spanning 2: Structuur geven vs overbegrenzen

Neiging: prompt zo strak begrenzen dat AI alleen kan spiegelen. Nuttig: begrenzingen beschermen eigenaarschap.

**Maar:** te veel begrenzingen doden serendipity. De krachtigste momenten ("mouths falling open") kwamen van prompts die AI ruimte gaven om onverwachte verbanden te leggen. Echo-prompt = 4 regels. Keuze: hoe meer output naar deelnemers, hoe strakker begrenzingen. Hoe meer voor facilitator (voorbereiding, reflectie), hoe meer ruimte.

### Spanning 3: Frustratie laten staan vs structureren

Neiging: "formuleer uitdagingen constructief." Gevaarlijk: frustratie = brandstof voor eigenaarschap.

**Maar:** ongestructureerde frustratie kan ook verlammen. Keuze is niet "wegpoetsen of laten staan" maar: structureer complexiteit zonder ongemak te neutraliseren. Toon dat drie groepen dezelfde frustratie anders verwoorden, zonder te concluderen dat het "opgelost" moet worden.

### Spanning 4: Snelheid vs diepgang

Neiging: alles grondig analyseren. Verleidelijk: diepere analyse voelt waardevoller.

**Maar:** echo-knop bewees tegenovergestelde. 10 seconden, één vraag, meer impact dan rapport van 10 pagina's. Keuze: live-prompts optimaliseren voor snelheid + trefzekerheid; post-sessie-prompts mogen dieper.

### Spanning 5: Transparantie vs leesbaarheid

Neiging: elke output voorzien van volledige bronvermelding, DIRECT/INFERENCE markers, confidence scores. Waardevol: bouwt vertrouwen.

**Maar:** transparantie-footer van 5 regels onder echo-vraag van 2 zinnen = absurd. Keuze: hoe directer output naar deelnemers, hoe lichter transparantie. Visie-document verdient volledige bronvermelding; live echo-vraag niet.

### Vuistregels bij de spanningen

| Richting | Wanneer strakker | Wanneer losser |
|----------|-----------------|----------------|
| **Letterlijk citeren** | Output gaat naar deelnemers | Output is voor facilitator als voorbereiding |
| **Begrenzingen** | Spiegel-niveau; hoge eigenaarschapsgevoeligheid | Serendipity-niveau; facilitator-tool |
| **Transparantie** | Documenten die worden gedeeld | Live interventies van 10 seconden |
| **Diepgang** | Post-sessie analyse | Live-sessie ondersteuning |

### Referentie: concrete formuleringen

Voor wanneer je prompt schrijft en snel betere formulering wilt vinden:

| In plaats van... | Overweeg... | Waarom |
|-----------------|-------------|--------|
| "Vat samen in heldere taal" | "Gebruik hun exacte woorden" | Eigenaarschap behouden |
| "Analyseer de thema's" | "Spiegel: maak thema's zichtbaar in hun woorden" | Niveau expliciet maken |
| "Maak een definitieve samenvatting" | "Maak output die de groep helpt verder te praten" | Dialoog is het doel |
| Stakeholders, reframen, tracken | Betrokkenen, herkaderen, bijhouden | Doesburg-toets: zou een facilitator dit woord gebruiken? |
| Conclusies trekken | Vragen stellen | Vragen openen; conclusies sluiten |

---

## Gevaarlijke momenten herkennen

### Bij prompt-ontwerp

- [ ] Is de prompt kort zonder begrenzingen? → AI krijgt te veel vrijheid
- [ ] Ontbreekt "baseer strikt op transcript"? → AI gaat aanvullen uit eigen kennis
- [ ] Ontbreekt "bij twijfel expliciet benoemen"? → AI klinkt zekerder dan het is
- [ ] Vraag je niet om deelnemerstaal te gebruiken? → Output klinkt als consultant
- [ ] Is er geen transparantie-instructie? → Mensen weten niet wat van hen is

### Bij output

- [ ] Geen bronverwijzingen of quotes? → Niet controleerbaar
- [ ] Klinkt het als "consultant-speak"? → Eigenaarschap weg
- [ ] Zijn tegenstrijdigheden opgelost? → Mensenwerk overgeslagen
- [ ] Ontbreekt transparantie over AI-rol? → Vertrouwen fragiel
- [ ] Stellige conclusies zonder bewijs? → AI beslist in plaats van spiegelt

### Het substitutie-moment

Het gevaarlijkste moment: iemand vraagt "kan de AI niet gewoon het plan invullen?"

**Herkennen:** "Kan de AI niet gewoon...?", enthousiasme zonder kritische vragen, vertrouwen op "confident AI" zonder verificatie.

**Interventie:** "Jullie zijn de ziel hiervan. Het feit dat jullie erover praten, zorgt ervoor dat jullie het waarschijnlijk zullen steunen. AI kan helpen structureren, maar het plan moet van jullie komen."

---

## Output-naar-buiten conventies

Voor elke output bedoeld om werkruimte te verlaten (deelnemer-output, publieke posts, klant-rapporten, AI-output via een platform naar deelnemers): twee schrijfconventies die als anti-AI-signature werken. Horen in prompt expliciet genoemd, niet als impliciete hoop op model-discipline.

### Sentence case in alle headings

Title Case in headings = AI-signatuur, herkenbaar als zodanig door lezers. Default: sentence case (alleen eerste woord + eigennamen capitalised). In prompt expliciet verbieden met right/wrong voorbeelden.

| WRONG (Title Case) | RIGHT (sentence case) |
|---|---|
| "Radical Ideas for a New Way" | "Radical ideas for a new way" |
| "Key Insights From This Session" | "Key insights from this session" |
| "Multi-Stakeholder Alignment Challenges" | "Multi-stakeholder alignment challenges" |

Geldt voor H2, H3, H4. Geen H1 in body-output (H1 is document-titel, hoort apart geregeld).

### No physical-presence metaphors voor digital sessions

Voor digitale sessies (Teams, Zoom, hybride): geen `walked in`, `stepped into`, `at the table` (voor attendance). Vervang door `joined`, `came in` (metaforisch), `was present`, `was represented`. Verbatim quotes met fysieke metaforen blijven verbatim.

Reden: fysieke metafoor doet werkelijkheid geweld aan en is eigenaarschap-precisie-issue. Eigenaarschap door taal geldt ook voor framing-laag rond quotes, niet alleen voor quotes zelf. Wie nooit `at the table` zat, herkent zich niet als zodanig.

| WRONG (digital sessie) | RIGHT |
|---|---|
| "Five colleagues walked in for the workshop." | "Five colleagues joined the workshop." |
| "A participant stepped into the breakout room." | "A participant came into the breakout room." |
| "Everyone at the table agreed." | "Everyone present agreed." |

### Verwante conventies elders in dit document

- **Em-dashes naar buiten**: niet hier; geldt voor de auteur's persoonlijke output (zie aparte voice-richtlijn). Voor algemene AI-output naar deelnemers: em-dashes acceptabel mits niet over-gebruikt.
- **Hard name rule**: zie "Privacy als ontwerpprincipe" sectie. Zero proper first names + replacement-strategieën.
- **AI-protagonist verbod**: zie richtlijn #2 hierboven. Geen "our analysis", "we noticed".

---

## Prompt-patronen uit de praktijk

### Patroon 1: Echo-interventie (live, 10 seconden)

```markdown
Rol: Je bent een ervaren dialoogcoach die krachtige,
niet-oordelende vragen stelt.

Context: De laatste 5-10 minuten van een sessie.

Randvoorwaarden:
- Maximum 2 zinnen voor de vraag
- Geen samenvatting of analyse, alleen de vraag
- Focus op de laatste 10-15 minuten

Instructies:
1. Analyseer de laatste minuten van het gesprek
2. Identificeer de onderliggende spanning, keuze of kans
3. Formuleer één krachtige vraag
4. Kies tactiek: Verdiepend / Concretiserend / Reflecterend
```


### Patroon 2: Thematische synthese (post-sessie)

```markdown
Rol: Je bent een strategisch redacteur die complexe dialogen omzet
in heldere, verhaalende syntheses zonder nuance te verliezen.

Randvoorwaarden:
- Baseer strikt op transcripten, geen verzinsels
- Behoud participantentaal en nuances
- Benoem verschillen in perspectief expliciet

Instructies:
1. Identificeer hoofdthema's per gesprek
2. Zoek patronen en spanningen tussen gesprekken
3. Cluster gerelateerde thema's met transparante rationale
4. Schrijf narratieve synthese per cluster
5. Benoem openstaande vragen en controverses
```


### Patroon 3: Eigenaarschap-bewarende visie

```markdown
Kernprincipes:
- Gebruik hun eigen woorden en terminologie
- Behoud de kracht van hun individuele visies
- Maak het specifiek voor [context], niet generiek
- Gebruik NIET [jargon] tenzij zij dat expliciet zeggen

Output moet bevatten:
### Totstandkoming
- Aantal stemmen, datum, context

### Hun waarom (in hun woorden)
[3-5 kernmotivaties met letterlijke quotes]

### Nog af te stemmen
[Tegenstrijdigheden expliciet benoemd]

### Over deze output
[Transparantie-footer]
```


---

## Sessie-flow: hoe prompts samenwerken

Prompts werken zelden in isolatie. In een sessie vormen ze een keten waarbij elke prompt voortbouwt op de vorige. Dit begrijpen = minstens zo belangrijk als de individuele prompt goed krijgen.

### De standaard workflow


```
WHY-prompt          →  Visie/motivatie vastleggen in hun woorden
    ↓
ECHO-prompt         →  Live reflectie, de vraag die de groep helpt dieper te gaan
    ↓
TIJDLIJN-prompt     →  Concrete stappen en planning extracten
    ↓
VERFIJNING-prompt   →  Feedback integreren, versie 2 maken
```

Elke prompt in keten heeft ander doel en ander niveau (Spiegel → Synthese → Spiegel → Synthese). Flow wisselt bewust tussen spiegelen en verbinden.

### Staged loading: context tussen prompts

Cruciale les: wanneer prompts na elkaar komen, wordt output van vorige prompt context voor volgende. Zo ontworpen, maar er zijn spelregels.

**De regel:** Gebruik eerdere AI-output als context, NIET als bron. Transcript blijft primaire bron. Eerdere AI-output helpt volgende prompt om niet dezelfde grond te bewerken, maar mag niet plek innemen van wat mensen daadwerkelijk zeiden.

**In de prompt:**
```markdown
Je werkt mogelijk in een sessie waar al eerdere AI-output is geweest.
Focus op het originele transcript. Gebruik eerdere AI-output alleen
als context, niet als bron. Bij referenties aan "wat we zien" kan
dit eerdere AI-output zijn.
```

### Multi-groep varianten

| Variant | Hoe het werkt | Kernregel |
|---------|---------------|-----------|
| **Parallel** | Meerdere groepen tegelijk, synthese achteraf | Elke groep apart analyseren, dan vergelijken |
| **Na elkaar** | Groepen na elkaar, AI-output getoond maar niet iteratief verwerkt | Losse analyses per ronde, synthese aan het eind |
| **Doordraaien** | AI verwerkt tussen rondes, bouwt voort in doorlopend document | Meest recente feedback is leidend |

Bij "doordraaien" = snelheid het geheim: Groep 2 start 10 min na Groep 1 en ziet direct AI-verwerkte resultaat. Die snelheid elimineert "leeg vel"-probleem en dwingt respect af voor wat vorige groep heeft ingebracht.

---

## Privacy als ontwerpprincipe

Privacy = geen checkbox aan het eind. Ontwerpbeslissing bij eerste woord van je prompt.

### De basisregels

- **Rolomschrijvingen, nooit namen:** "een zorgverlener" i.p.v. een eigennaam. Tenzij expliciete toestemming voor naam-vermelding.
- **Abstractie met behoud van herkenning:** "een deelnemer die frustratie uitte over financiering" laat patroon intact zonder persoon bloot te leggen.
- **Validatiedrempels voor cross-project:** Patroon is pas deelbaar als het in 3+ onafhankelijke bronnen verschijnt. Gevoelige onderwerpen: 2x die drempel.
- **Zero proper first names rule:** géén proper first names in output naar deelnemers of buiten. Quote met naam? Drie opties: (a) pick different verbatim segment dat dezelfde meaning carries zonder naam, OF (b) replace naam met `[a colleague]` / `[an earlier voice]`, OF (c) strip de naam uit quoted text en vervang met `[participant]` / `[speaker]`. Stakeholder lists by role only ("de IT-lead", "de GIS-specialist").
- **Neutrale speaker-labels als rol onbekend is:** wanneer voices onderscheiden moeten worden maar rol niet bekend (multi-voice transcript zonder rol-context), gebruik `Speaker A`, `Speaker B`, `Speaker C`, NOOIT namen. Beter dan namen waar rol-attribution ontbreekt.
- **Redaction-placeholders nooit in output:** strings zoals `<redacted_name>`, `[NAAM]`, `<participant>` mogen NOOIT in eindversie verschijnen. Als ze opduiken: model heeft (a)/(b)/(c) niet toegepast. Pre-output checklist moet dit afvangen.
- **Anonimisering geldt voor hele pipeline, niet alleen output:** namen mogen NIET verschijnen in body, headers, metadata, tags, kop-attributies, footers, of welk veld dan ook. Tijdens analyse zelf, niet alleen bij final output, refereert AI alleen aan voices via rol of label. Voorkomt dat AI namen "onthoudt" en later per ongeluk reproduceert.

### In de prompt

```markdown
Gebruik rolomschrijvingen, nooit namen.
Zero proper first names in output. Wanneer een verbatim quote een naam bevat:
- (a) pick een ander verbatim segment dat dezelfde meaning carries zonder naam, OR
- (b) replace de naam met "[a colleague]" of "[an earlier voice]".
Stakeholder lists by role only ("de IT-lead", "de GIS-specialist"), nooit names.
Beschrijf patronen abstract genoeg dat geen individu herkenbaar is.
Bij citaten: gebruik zonder speaker-attributie of met role-attribution.
Redaction-placeholders ("<redacted_name>", "[NAAM]") mogen NOOIT in output verschijnen.
```

### Waarom hard rule en niet best-effort

Empirisch: Gemini 2.5 Pro lekt names als rule soft is (v3-test bij een internationale organisatie had meerdere deelnemer-namen in de output). Met hard rule + (a)/(b)/(c) replacement-strategieën: zero leakage in v4-v5. Rule moet expliciet als gate worden geformuleerd, niet impliciet via "wees voorzichtig met namen".

### Het absolute-anonymity blok: wanneer platform-anonimisatie niet aan kan

Sommige sessies kun je niet via platform-anonimisatie (transcript-platform anonymize-feature, auto-anonymize in chat) afdwingen omdat **andere named entities behouden moeten blijven**: gebiedsontwikkeling waar straatnamen, buurtnamen, gebouwnamen wel in output moeten staan; sessies waar organisatie-namen of project-namen functioneel zijn; analyses waar specifieke locaties dragend zijn voor patroon.

In die gevallen: platform-laag-anonimisering uitzetten (anders zou alles weg gaan) en namen-anonimisering uitsluitend via prompt-laag afdwingen. Vereist harder gate-formuleren dan default, een **absolute-anonymity blok** in de prompt zelf.

**Template (bron: praktijk met het Dembrane-platform, mei 2026):**

```
=== ABSOLUTE ANONYMITY RULE ===
UNDER NO CIRCUMSTANCE may you, during analysis, refer directly to any
person by name. NO NAMES should appear in any analysis output, not
participant names, not facilitator names, not expert names, not
observer names.

This applies even if names appear in the transcript. During analysis:
- Replace all names with role-based descriptors: "a participant",
  "one speaker", "a resident", "a facilitator", "the expert presenter"
- If you need to distinguish between speakers, use neutral labels:
  "Speaker A", "Speaker B", or descriptive roles, but NEVER names.
- When quoting, strip any names from the quoted text and replace with
  [participant] or [speaker].
- Do NOT include names in metadata, headers, tags, or any other field.
- This rule is non-negotiable and overrides any other instruction. It
  exists to protect participants' privacy and independence, in line
  with the OECD deliberative principles on privacy and GDPR
  requirements.
```

**Wat dit blok extra doet dat de standaard zero-name regel niet doet:**

| Element in blok | Wat het toevoegt |
|---|---|
| `UNDER NO CIRCUMSTANCE` + `non-negotiable` | Extreme stelligheid als prompt-techniek, modellen pakken hard-phrased gates beter op dan soft guidance |
| `overrides any other instruction` | Override-clausule, voorkomt dat andere instructies de regel onbedoeld verzwakken |
| `during analysis` | Hele-pipeline-coverage, niet alleen output |
| `Speaker A/B als optie` | Differentiatie als rol niet bekend is |
| `strip from quoted text` | Derde optie expliciet naast (a) ander segment en (b) replace |
| `metadata, headers, tags` | Coverage buiten body-tekst |
| OECD + GDPR rationale | Externe juridische frame, bruikbaar voor klant-vragen "waarom zo streng?" |

**Wanneer dit blok inzetten:** platform-anonimisatie uitstaat omdat entity-namen behouden moeten blijven (straten, gebouwen, organisaties); high-stakes participant-output waar één naam-lek schadelijk is voor vertrouwen; klant-projecten met expliciete privacy-anchors (OECD-deliberative-frame, GDPR-compliance-vereisten); gevoelige onderwerpen waar persoonlijke uitspraken anders herleidbaar worden.

**Wanneer dit blok NIET nodig is:** platform-anonimisatie staat aan (zoals de anonymize-feature in Dembrane), die doet het werk al; output is intern (coaching mirror, scratch analyse), soft zero-name regel volstaat; sessie heeft expliciete naam-vermelding-toestemming met named role-attribution.

### Wanneer privacy extra aandacht verdient

- Cross-project analyse (patronen over meerdere groepen)
- Output die naar externe stakeholders gaat
- **Gebiedsontwikkeling of sessies waar entity-namen wel behouden moeten blijven**, platform-anonimisatie kan niet, prompt-laag moet het werk doen via absolute-anonymity blok hierboven
- Gevoelige onderwerpen (zorg, financiën, interpersoonlijke spanning)
- Kleine groepen waar anonimisering moeilijker is

---

## Iteratie: hoe een prompt evolueert

Prompt ontstaat niet in één keer. Een 12-rondes transformatieplan-journey laat zien hoe.

1. Beschrijf wat je wilt → 2. AI stelt aanpak voor → 3. Jij voegt context toe (draaiboek, sessie-flow) → 4. AI past aan → 5. **Cruciale correctie:** "De AI heeft geen toegang tot het voorbeeldplan, dus neem de schrijfstijl mee IN de prompt" → 6. AI verwerkt correctie → 7. Test met echt materiaal → 8. Verfijn op basis van output-kwaliteit.

**Vier concrete correcties die prompts transformeren:**
- "De AI heeft geen toegang tot het voorbeeldplan, dus neem de schrijfstijl mee in de prompt"
- "Maak de prompts universeel, de AI kan zelf het thema detecteren"
- "De prompt moet vooral vragen genereren voor de volgende groep"
- "De AI heeft toegang tot volledige transcripten, niet fragmenten"

**Meta-les:** Waarde zit niet in ronde 1, maar in accumulatie van verfijningen door feedback. Elke correctie maakt aanname expliciet die de prompt van theoretisch naar praktisch transformeert.

---

## Tool-agnostisch ontwerpen

Alle prompts in deze bundle werken met elke LLM. Vermijd: platform-specifieke instructies ("gebruik GPT-4 turbo"), API-specifieke formatting ("geef output als JSON"), tool-specifieke features ("gebruik internet search"). Gebruik in plaats daarvan: duidelijke rolverdeling, expliciete instructies in gewone taal, output-formats die in elk platform werken (markdown, platte tekst).

---

## Patterns learned: case-study verwijzingen

*Case-study pointer.* Universele patronen die deze sectie ooit als één blok dekte zijn per 2026-05-12 PAI-brede consolidatie geïntegreerd in hoofd-secties hierboven. Wat rest = pointer-laag: waar komen regels vandaan, hoe te traceren.

| Patroon | Nieuwe locatie in dit document | Bron-iteratie |
|---|---|---|
| Sentence case + No physical metaphors | "Output-naar-buiten conventies" sectie | pilot bij een internationale organisatie, v1 naar v5 |
| Voice texture + Load-bearing disagreement + Contestation priority | "Multi-voice handling" sectie | pilot bij een internationale organisatie, v1 naar v5 |
| Hard name rule + redaction-placeholder | "Privacy als ontwerpprincipe" → "Zero proper first names rule" | pilot bij een internationale organisatie, v3 naar v4 |
| Mishearing escalation | "Transcript-artifacts handling" sectie | pilot bij een internationale organisatie, v3 naar v5 |
| Saint-Exupéry strip principle | "Prompt als architectuur" → "Constraints op één plek" sub-sectie | pilot bij een internationale organisatie, v1 naar v5 |
| Pre-output checklist | "Pre-output checklist: model-self-verification ingebed in prompt" sectie | pilot bij een internationale organisatie, v3 naar v5 (Gemini-specifieke noodzaak) |
| Wanneer platform verlaten / high-stakes model-keuze | "Model-bewustzijn" → "High-stakes output vereist model-kwaliteit boven prompt-richness" | pilot bij een internationale organisatie, v2 naar v5 |
| Vertrouwen als voorwaarde (later toegevoegd) | "Vertrouwen als voorwaarde" sectie | bottom-up wiki-praktijk principe #2, cross-bron 2026-05-12 |
| Drie assen voor prompt-architectuur | "Drie assen voor prompt-architectuur" sectie | 2026-05-12 |

Iteratie-bron + decision-rationale per regel: per-klant werkdoc (bv. `werkdocs/prompt-changes-tracker.md`). Subagent-playbook voor high-stakes participant-output: per-klant werkdoc als template voor andere clients.

Voor platform-specifieke caveats (quote density getallen, model-specific gates, plateau-effecten): raadpleeg de documentatie van het transcript-platform dat je gebruikt.

---

## Wie spreekt buiten de quotes? Oftewel: van wie maakt dit document, en aan wie is het gericht?

Best practices regelen quote-stem (verbatim, hun woorden) goed. Document-stem, wie spreekt in headings, intro-zinnen, verbindweefsel tussen quotes, framing-uitspraken, = aparte laag. Deze laag moet actief gestuurd worden. Zonder sturing treedt AI-default-Engels op als faal-modus: klinkt als consultant of generic facilitator. In social-AI werk geen toegestane uitkomst.

### Twee stem-niveaus

| Stem-niveau | Wat het regelt | Gewenste default in social-AI werk |
|---|---|---|
| **Quote-stem** | Wat tussen aanhalingstekens of in *italic* staat, verbatim uit deelnemers | Strak geregeld door verbatim-default + anonimisering-regels |
| **Document-stem** | Headings, intro-zinnen, verbindweefsel, framing-uitspraken | **Actief gestuurd** richting deelnemer-register / facilitator-register / project-register. Zonder sturing valt AI terug op AI-default-Engels, faal-modus, niet toegestaan. |

### Wanneer dit ertoe doet

Output die naar deelnemers gaat. Output die in iemand anders' naam de wereld in gaat (facilitator, klant). Output waar herkenning op heel-document-niveau telt, niet alleen op quote-niveau. Niet kritiek voor: interne analyse, scratch-werk, output puur voor jezelf.

### Twee aspecten samen: uitbreiding én eigen gewicht

Document-stem = **uitbreiding van Eigenaarschap door taal** (principe 4 in [Principes](./SOCIAL-AI-PRINCIPES.md)): hun woorden tellen niet alleen in quotes maar in elke laag van een document dat over hen gaat. Tegelijk staat het op zichzelf als **tool-agnostisch ontwerp**: ook wanneer eigenaarschap-door-taal niet de hoofdvraag is (bv. didactische uitleg, theoretisch frame, value-framing), bepaalt gekozen stem of document landt of voelt als opgelegd.

Niet of/of. Beide.

### Niet alleen mirror, ook facilitator-keuzes

Document-stem ≠ alleen deelnemer-mirror. Ook kans voor facilitatoren om bewust andere verwoordingen te kiezen die deelnemers zelf niet gebruiken, bv. value-framings die de groep niet uitspreekt maar het project nodig heeft, theoretische framing voor leadership-rapportage, didactische uitleg om patronen toegankelijk te maken voor breder publiek. Wel: keuze is expliciet, niet AI-default. Facilitator beslist welk register past bij doel + doelgroep. AI volgt die keuze.

| Document-stem keuze | Wanneer passend |
|---|---|
| Deelnemer-register | Output naar deelnemers zelf, mirror-niveau, eigenaarschap-bewaring |
| Facilitator-register | Output naar facilitatoren-team (coaching mirrors), naar klant-leadership, didactische context |
| Project-register | Output binnen specifieke project-taal (bv. organisatie-vocabulaire), theoretische framing, value-framing van de pilot |
| AI-default-Engels | **Nooit als bewuste keuze.** Faal-modus die optreedt zonder sturing. |

### Hoe afdwingen in prompt

Drie manieren, ideaal gecombineerd:

1. **Voorbeeld-zin meegeven.** *"Schrijf in deze stijl: [concrete voorbeeld-zin van facilitator, deelnemer, of project-register]."* Eén goede voorbeeld-zin doet meer dan abstracte register-instructie.

2. **Register-instructie expliciet.** *"Schrijf in de stem van een nieuwsgierige collega, niet een consultant."* Of: *"Een specifiek register: directe vragen, korte zinnen, geen abstracte synthese-woorden."* Of: *"In de groep's eigen stem: zoals zij het aan een collega zouden vertellen, niet zoals een rapport het zou schrijven."* Of: *"Project-register: gebruik de project-specifieke vocabulaire voor leadership-momenten."*

3. **Anti-pattern lijst van AI-default-fraseringen.** Veelvoorkomende AI-default-zinnen die vermeden moeten worden:
   - "The analysis suggests"
   - "Key insights include"
   - "Stakeholders mentioned"
   - "It is worth noting that"
   - "This highlights the importance of"
   - "Several participants raised"
   - "The conversation revealed"

   Anti-patterns expliciet noemen in prompt = model vermijdt ze actief.

### Uitgebreide recognition-test

Standaard recognition-test toetst quote-niveau: *"zouden zij zeggen 'ja, dat zeiden wij'"*. Uitbreiding: zouden zij OOK de headings, intro-zinnen, verbindweefsel herkennen als hun stijl (bij deelnemer-register), of als geschreven door de facilitator die hen begeleidt (bij facilitator-register), of als passend in het project-frame (bij project-register)? Beide-lagen-pass = output klaar voor naar buiten.

### Anti-pattern in prompt-ontwerp

Veelgemaakte fout: alleen quote-regels specificeren, document-stem ongedefinieerd laten. Resultaat: output met perfecte verbatim quotes in AI-default-Engels frame. Lezer voelt mismatch zonder te kunnen benoemen wat er mis is, quotes kloppen, maar "stem die de pagina draagt" klopt niet.

Tegenremedie: bij elke prompt voor output-naar-buiten, beantwoord eerst expliciet twee titel-vragen:
- Van wie is dit document? (welke register hoort daar bij?)
- Aan wie is het gericht? (wat herkennen zij als hun stem?)

### Cross-references

- Eigenaarschap door taal (principe 4 in [Principes](./SOCIAL-AI-PRINCIPES.md)), quote-stem is daar geregeld; document-stem is de uitbreiding daarvan op framing-niveau
- Richtlijn #6 hierboven, document-stem actief sturen als altijd-actieve regel
- Tool-agnostisch ontwerpen (sectie hierboven), document-stem heeft eigen gewicht naast tool-agnostiek

---

## XML-tags als volumeknop: loudness in prompts

**Bron:** Matt Pocock's bug-fix op `/grill-with-docs` ([mattpocock/skills](https://github.com/mattpocock/skills/tree/main/skills/engineering/grill-with-docs), mei 2026). Aanleiding: zijn skill was "te eager om te implementeren". Diagnose: supporting-info onderaan skill-doc had visueel gewicht en concurreerde met eigenlijke instructie bovenaan. Fix: supporting-info in `<supporting-info>` XML-tags wrappen. Effect: model gaf instructie boven duidelijke voorrang, supporting-info werd referentie i.p.v. mede-instructie.

Matt's verwoording: **"Sommige delen van prompts concurreren met elkaar qua volume en impact op de output."** Hij noemt dit *loudness in prompts*.

### Het principe

Een prompt = geen platte lijst regels die het model gelijkwaardig leest. Audio-mix: sommige delen klinken harder dan andere. Wat "luid" is, wordt bepaald door:

- **Lengte**, 30-regelige supporting-block onderaan klinkt harder dan 3-regelige instructie bovenaan
- **Positie**, wat laatst staat klinkt vaak harder dan wat eerst staat (recency bias bij sommige modellen, niet alle)
- **Detail-dichtheid**, concrete voorbeelden met specifieke namen klinken harder dan abstracte principes
- **Visueel gewicht**, code-blokken, tabellen, headers trekken aandacht weg van proza

Zonder volume-discipline gaat model voorzichtige instructies negeren ten gunste van detailrijke voorbeelden. Of het volgt expliciete instructies, maar legt klemtoon verkeerd omdat supporting-info dominantere signalen geeft.

### XML-tags zijn de volumeknop

Anthropic-modellen (Claude) reageren expliciet goed op XML-tag-hiërarchie om volume te sturen. Niet omdat XML magisch is, wel omdat tags het model dwingen om sectie-rol te onderscheiden. `<instructions>` is iets anders dan `<supporting-info>`, ook al staat inhoud in dezelfde prompt.

Concrete patterns die werken:

```xml
<instructions>
Doe X. Stop daarna. Wacht op feedback.
</instructions>

<supporting-info>
Achtergrond, voorbeelden, edge cases, referentie-materiaal,
niet mede-instructie.
</supporting-info>

<context>
Wat de gebruiker eerder zei, wat het project is, welke conventies gelden.
</context>

<examples>
Twee tot vier voorbeelden van gewenste output. Niet meer.
Te veel voorbeelden = volume-overflow, model imiteert in plaats van begrijpt.
</examples>

<output-format>
Exacte structuur die de output moet hebben.
Geen proza hier, alleen structuur.
</output-format>
```

Optioneel voor expliciete hiërarchie:

```xml
<instructions priority="high">
Dit moet áltijd. Geen interpretatie.
</instructions>

<supporting-info priority="low">
Mag genegeerd worden als het botst met instructions.
</supporting-info>
```

Het `priority`-attribuut is niet gestandaardiseerd in modellen, maar maakt voor mens-lezer (én als hint voor model) hiërarchie expliciet.

### Wanneer dit ertoe doet

XML-tag-volume = **niet altijd nodig**. Korte prompts (echo-prompt: 4 regels) hebben geen volume-probleem. Tag-overhead daar contraproductief.

Volume-discipline wordt kritisch wanneer:

| Conditie | Voorbeeld |
|---|---|
| **Prompt > 500 woorden** | Transcript-analyzers, methode-prompts, multi-step instructies |
| **Supporting-info is langer dan instructie** | Skill-files, multi-section prompts met referentie-materiaal |
| **Het model output produceert die niet matcht met je intentie** | "Te eager", "vergeet stap 2", "doet wat in de voorbeelden stond i.p.v. wat in de instructie stond" |
| **Voorbeelden, edge cases of data-definities staan in dezelfde prompt** | Analyse-prompts met JSON-schema's, transcript-prompts met aanwezigen-lijsten |

### Concreet voorbeeld: before/after

Fictief "te eager" prompt-fragment:

**Before** (alles platte tekst, supporting-info dwingt zich op):

```markdown
Maak een ADR voor deze beslissing.

Hier zijn 8 voorbeelden van ADRs uit ons archief:
[8 lange ADRs, totaal 2000 woorden]

Format: number-slug.md in docs/adr/.

Hier zijn 5 templates die we eerder hebben gebruikt:
[5 templates, totaal 800 woorden]

Belangrijke beslissing-criteria:
- hard to reverse
- surprising without context
- result of real trade-off
```

Probleem: model leest 2800 woorden voorbeelden en 50 woorden criteria. Bouwt ADR die op voorbeelden lijkt, ongeacht of huidige beslissing criteria haalt. Te eager.

**After** (XML-tags geven volume-hiërarchie):

```markdown
<instructions priority="high">
Beoordeel eerst: voldoet deze beslissing aan ALLE DRIE criteria?
- hard to reverse
- surprising without context
- result of real trade-off

Als één criterium ontbreekt: geen ADR. Antwoord met "Skip ADR, reden: [criterium]".

Als alle drie waar zijn: schrijf ADR met minimum-template (titel + 1-3 zinnen).
</instructions>

<supporting-info>
Format-referentie: number-slug.md in docs/adr/.

Voorbeelden ter referentie (niet imiteren, alleen formaat-houvast):
[2-3 ADRs, kort]

Eerdere templates (alleen raadplegen bij twijfel):
[1 template]
</supporting-info>
```

Effect: criterium-check krijgt volume dat het verdient. Voorbeelden worden naslagwerk i.p.v. imitatie-doel.

### Volume-design-regels

1. **Instructie eerst, kort, in `<instructions>`.** Wat moet het model doen? Eén handeling per regel.
2. **Supporting-info apart in `<supporting-info>` of `<context>`.** Lange achtergrond, voorbeelden, edge cases. Model weet nu: referentie, niet mede-instructie.
3. **Voorbeelden in `<examples>`, max 4.** Te veel voorbeelden = volume-overflow.
4. **Output-format in eigen tag.** Niet vermengen met instructies of voorbeelden. Model leest hem als laatste, weet wat eindvorm is.
5. **Bij twijfel: minder voorbeelden, krachtigere instructie.** Voorbeelden zijn duurder qua aandacht dan ze lijken.

### Wat dit NIET is

De zeven baseline-richtlijnen (em-dash, AI-protagonist, naam-attributie, recognition test, verbatim, document-stem, zorgvuldigheid) blijven onveranderd. XML-tags = prompt-engineering-tool om die richtlijnen beter te laten werken in lange prompts, geen vervanging.

Onderliggend principe (opdracht eerst, randvoorwaarden in eigen sectie daarna) is **universeel** in moderne transformer-modellen. Elk model profiteert van expliciete volume-hiërarchie. XML-tags = één manier om die scheiding hard te maken; markdown-headers met duidelijke labels (`## Core instruction` versus `## Background, reference only`) zijn een andere.

Anthropic raadt XML-tag-hiërarchie expliciet aan in hun prompt-engineering docs. Voor Gemini en GPT-4 geen vergelijkbare publieke training-claim, maar Matt Pocock's productie-evidence (na XML-tag fix in `/grill-with-docs` kwamen er geen klachten meer over "te eager implementeren") sterk genoeg om syntax breed in te zetten, niet alleen bij Claude.

**Vuistregel:** gebruik XML-tags zodra prompt lang is en supporting-info qua volume met instructie concurreert, onafhankelijk van doelmodel. Vervolgens observeren: als output op specifiek model afwijkend reageert, val terug op markdown-headers met expliciete labels, structurele principe blijft hetzelfde.

### Cross-references

- `Tool-agnostisch ontwerpen` sectie, het principe (opdracht-eerst, randvoorwaarden-apart) is universeel. XML-syntax is één implementatie naast markdown-headers. Bij twijfel over doelmodel: behoud markdown-fallback met expliciete labels naast XML-tags.
- `Prompt-anatomie: vormen en variaties` sectie, bouwblok-template kan in XML-tags worden gewrapped voor Claude-doelmodellen
- `Pre-output checklist` sectie, XML-tags helpen ook bij self-verification: model leest `<verification-checklist>` als aparte instructie
- De zeven baseline-richtlijnen #1-7 hierboven, blijven van toepassing, XML-tags maken ze beter zichtbaar

### Log

- 2026-05-14: XML-tag-volume sectie toegevoegd (Matt Pocock bug-fix principe, "loudness in prompts"). Bron: analyse van [mattpocock/skills changelog](https://github.com/mattpocock/skills/tree/main/skills/engineering/grill-with-docs).
- 2026-05-14 (later): "Wat dit NIET is" herzien. Eerdere formulering ("XML-tag-volume is model-specifiek voor Anthropic-modellen") was een telefoon-spel-overstatement zonder primaire bron, ontstaan in de ketting inbox-analyse → agent-prompt → uitwerking. Nieuwe formulering: principe is universeel (opdracht-eerst, randvoorwaarden-apart), XML-syntax is één implementatie met Anthropic-aanbeveling én Matt's productie-evidence (n=1: geen klachten meer na fix). Markdown-headers blijven valide fallback. Correctie tijdens sparring rond transcript-platform-prompts.

---

## Bulletproof-points in multi-step analyse-flows

Wanneer prompt-flow meerdere stappen doorloopt over hele sessie of dag (transcript-discovery → quality-check → clustering → analyses → synthese → output), is werkelijkheid altijd rommeliger dan blauwdruk. Telefoons werden niet aangezet, deelnemers hervatten i.p.v. starten, transcripten ontbreken, twee gesprekken vermengen. Rigide prompt-keten valt om bij eerste discrepantie. Bulletproof keten blijft lopen en gebruikt wat er is.

### De vier bulletproof-points

| # | Principe | Wat het oplost |
|---|---|---|
| **A** | **Read-what-exists** | Hardgecodeerde file-lijsten zijn suggesties, geen vereisten. `ls folder/` is ground-truth. Missing file = noteer + ga door, niet falen. |
| **B** | **Archief-pre-check** | Bij multi-stap-keten: eerdere stappen kunnen al uitgevoerd zijn op een eerdere run. Check of de output van vorige stap bestaat vóór je opnieuw spawnt. |
| **C** | **Completeness-verify** | Bij sanity-bekend aantal werkmomenten/groepen/inputs: match gevonden tegen verwacht. Mismatch = waarschuwing aan gebruiker, niet stilzwijgend door. Een gemiste werkgroep is een groter probleem dan een traag proces. |
| **D** | **Confidence-degradation** | Bij lage zekerheid in clustering, quality-check of inferentie: markeer + vraag, niet plausibel invullen. Lege blokken > verzonnen blokken. |

### Hoe het in elke stap landt

**Discovery-stap:** begin altijd met `ls` + lees-wat-er-staat, niet met "hier zijn N verwachte bestanden, laad ze". Discovery = observatie, niet aanname.

**Clustering-stap:** als gevonden clusters niet matchen met verwacht aantal werkmomenten → STOP en vraag. Hypothesen aanbieden helpt: "ik zie M clusters maar verwacht N, mogelijke oorzaken: (a) niet alle telefoons hebben opgenomen, (b) twee groepen zijn ten onrechte gemerged op thematische overlap, (c) één opname werd als ruis gezien. Wat is jouw inschatting?"

**Quality-check-stap:** voer alleen uit als meer dan één transcript per cluster. Bij één bestand: automatisch de primary. Geen wasted compute.

**Analyse-stap:** input-bestand-lijst = suggestie. Lees wat er staat. Vermeld in output-recap als bestanden ontbraken: "Verwerkt op basis van N van M verwachte transcripten, [X, Y] ontbraken."

**Synthese-stap:** als upstream-stappen ongeauthoriseerd waren of caveats hadden, propageer die door naar synthese-output. Geen verborgen kwaliteits-vermindering.

### Wat dit voorkomt

- Wall of Wonder prompt die crasht omdat een verbeelden-transcript ontbreekt
- Werkgroep-recap die stilzwijgend één hele werkgroep mist omdat twee groepen op elkaar leken
- Quality-check die opnieuw draait terwijl het archief al klaarstaat
- Synthese-document dat doet alsof alle input compleet was

### Auto-aftrap principe

Bulletproof flow moet vanuit natuurlijke trigger ("doe nu Wall of Wonder") zonder hand-holding starten:

1. **Stap 0 (pre-flow check):** kijk wat op disk staat. Upstream-werk al gedaan? (`archief/` bestaat → quality-check al uitgevoerd). Match tegen verwacht aantal.
2. **Skip wat al klaar is.** Hergebruik primaries als die er zijn.
3. **Spawn alleen wat nog moet.** Quality-check subagents voor clusters met 2+ bestanden. Niet voor singletons.
4. **Verifieer completeness.** Klopt beeld met wat we verwachten te hebben gehoord? Zo niet: meld + vraag.
5. **Voer analyse-stap uit op gevalideerde input.**
6. **Hand-off met caveats.** Vermeld in output wat ontbrak of onzeker was.

### Log

- 2026-05-19: Bulletproof-points sectie toegevoegd na praktijk-incident tijdens een tweedaagse verbeeldings-sessie: één werkgroep nam niet op, andere hervatte bestaande conversation, prompt was te rigide ingericht op vooraf-vastgelegde file-lijst. Sparring-bron: *"we moeten allerlei bulletproof-points inbouwen dat de flow wel blijft lopen en gebruik maakt van wat er is. En verifieer dat je geen transcripten mist, dat je geen gesprek daadwerkelijk mist."*

---

## Multi-prompt validation voor wiki-fundament

Wiki-entries die als fundament dienen voor coaching, sessie-design en director-deliverables vragen meer dan één prompt-pass. Wat één prompt vindt kan signaal zijn van het materiaal of artefact van de formulering, zonder vergelijking niet te onderscheiden.

Wij noemen dit **verdedigbare facilitator-stof**: niet wetenschappelijk bewijs, wel onderbouwde claim met bron, multi-prompt gevalideerd via overlap, "ongeveer-klopt + sample-checkable", tot op zekere hoogte houdbaar bij pushback ("ja dat zat in WS3 breakout-2 op deze plek met deze drie prompts").

### Belicht-beide-kanten als prompting-default

Best-practice voor pattern-extraction prompts: vraag expliciet naar zowel wat werkt als wat schuurt. Niet alleen *"waar zijn de spanningen?"* maar *"waar zijn de spanningen EN waar werkte iets goed?"*. Balance-target in output 40-60% per kant. Voorkomt dat prompt-formulering zelf naar problem-naming trekt.

**Niet forceren.** Wanneer een facilitator expliciet zegt "ik wil alleen de spanningen", geef alleen spanningen. Best-practice is kennis voor default-keuzes, niet een regel die de prompt automatisch tegen-stuurt wanneer de gebruiker iets anders vraagt.

### 3-pass setup voor wiki-fundament-werk

Boven op belicht-beide-kanten-default: voor wiki-fundament-werk is één pass niet genoeg. 3-pass verplicht:

| Pass | Type | Wat verschuift |
|---|---|---|
| 1 | Gemengde baseline | Faithful aan lens-definitie. Object + sub-vragen + signal-types + scaffold uit lens-file. Geen aanpassingen aan vocabulair. |
| 2 | Gemengde vocab-shift | Vakjargon vervangen door concreet gedrag of fysiek-ruimtelijke taal. "Walking-away" i.p.v. "topic-flight". "Ideas that landed but no one picked up" i.p.v. "idea-fading". Zoekt zelfde fenomenen met andere woorden, vangt unieke catches. |
| 3 | Positive-only-exclusive | Filter: alleen positieve/affirmatieve momenten. *"Find ONLY moments where the group did something well, co-construction, real dialogue, generative tension."* Vangt stille positieven die de gemengde passes missen. |

**Constraint per variant:** alle drie zoeken hetzelfde fundamentele ding (de lens). Verschillen zitten in formulering, niet in scope. Anders test je niet robuustheid maar vergelijk je verschillende lenzen.

### Comparison-rule (kritiek)

**Overlap = verbatim-overlap OF moment-overlap, NIET label-overlap.**

Twee outputs overlappen alleen als ze hetzelfde citaat aanhalen of hetzelfde moment markeren (zelfde speaker, zelfde sequence-positie). Twee variants die hetzelfde citaat verschillend labelen = overlap. Hetzelfde label op verschillende citaten = GEEN overlap.

Waarom: varianten gebruiken expliciet ander vocabulair. Label-overlap zou false-positive robuustheid suggereren.

**Bewijs uit Test 1:** L1-comparison-agent moest 5 initial "robust 4/4" candidates downgraden bij strict toepassing van deze regel.

### 4-laags tag-schema

Voor wiki-entries uit 3-pass:

| Tag | Wanneer |
|---|---|
| **CROSS-FRAME VALIDATED** | In gemengde passes EN positive-only-pass. Sterkste claim. |
| **PAIRED-VALIDATED** | In 2 gemengde passes, niet in positive-only. |
| **EXCLUSIVE-ONLY** | Alleen in positive-only-pass. Geldig maar één-pass. |
| **SINGLE-FRAME CATCH** | Eén variant alleen. Artifact-kandidaat OF diep signaal, contextueel. |

### Naming-conventie voor findings met meerdere readings

Wanneer twee of meer variants hetzelfde citaat oppakken maar verschillend lezen:

| Naming | Wanneer | Wat ermee doen |
|---|---|---|
| **Complementary readings** | Beide lezingen kloppen naast elkaar, samen rijker | Bewaar beide in wiki-entry, geen synthese-druk |
| **Competing readings** | Lezingen sluiten elkaar uit | Bewaar beide, interview-kandidaat voor menselijke afweging |
| **Multiple readings** | Overhaast niet bepaalbaar welke van bovenstaande | Bewaar beide, classificeer later |

Dual-readings zijn FEATURE niet bug. Bewijs dat werkelijkheid plaatselijk ambigu is. Geen synthese-druk om ze te verzoenen. Voor 1-op-1-prep rijker dan gesynthetiseerde enkelvoudige lezing.

### Waarom positive-only blijft nodig

Gemengde prompts (passes 1+2) vangen duidelijk uitgesproken positieve momenten betrouwbaar. Stille positieven niet. Drie vormen van het patroon "stille positieven in dichte context": zie [Principes](./SOCIAL-AI-PRINCIPES.md) § Positive-first als anti-default-pull voor uitleg en voorbeelden. Pass 3 (positive-only) is wat deze stille positieven vangt.

### Lens-niveau: micro vs macro prompt-gevoeligheid

Empirisch uit Test 1 (L1+L2 op WS3):

- **Micro-niveau lenzen** (taal-mechanismen, woordkeuzes, grammaticale moves) zijn HOOG prompt-gevoelig. Counts per variant spreidden 19-40. Marker zit in één woord, ander vocabulair → mist hem.
- **Macro-niveau lenzen** (groeps-patronen, dialoog vs broadcast) zijn LAGER prompt-gevoelig. Counts 9-20. Patroon heeft meerdere signalen waar agent het aan kan ophangen.

Implicatie: micro-lenzen verdienen mogelijk extra validatie. Macro-lenzen kunnen mogelijk met minder. Te bevestigen bij verdere uitrol.

### Wanneer 3-pass verplicht vs 1-pass acceptabel

| Verplicht (3-pass) | Optioneel (1-pass acceptabel) |
|---|---|
| Nieuwe SM-entries in lens-pagina's | Lens-definition-revisies waar de auteur-gate vergelijking doet |
| Lens-uitrol op nieuwe bron (WS-transcript, meeting) | Verbatim-only werk (L5), verbatim is verbatim, lage prompt-gevoeligheid |
| Syntheses voor 1-op-1 / director-deliverables | Reflecties / project-resource-notities niet als evidence |
| Revalidation van single-prompt-origin entries | Quick scans / niet-evidence-werk |

### Validatie ≠ attribution-discipline

Twee verschillende disciplines die makkelijk verward worden:

| Dimensie | Wat het fixt | Voorbeeld |
|---|---|---|
| **Attribution-discipline** | WIE zei wat | Radical rebuild 19 mei fixte naam-attributies |
| **Multi-prompt validation** | HOEVEEL prompts hetzelfde signaal vonden | Test 1 valideert robuustheid |

Entries die alleen attribution-discipline hebben gekregen zijn nog steeds single-prompt origin. Krijgen Robustness-tag "single-prompt origin, kandidaat voor revalidation". Beide disciplines nodig, niet inwisselbaar.

### Schaal-economie

```
Per lens-bron-combo, 3-pass setup:
  3 parallel agents + 1 comparison + 1 wiki-integration = 5 runs
  Wall-clock parallel:  ~5-7 min
  Tokens (Opus):        ~650K
  Kost per combo:       ~$10

Hele wiki "verdedigbare facilitator-stof":
  ~17 combos × 5 runs = ~85 runs
  Wall-clock: ~5-6 uur over 3-4 sessies
  Totaal:     ~$165
```

Per facilitator-claim onderbouwbaar met "drie verschillende prompts vonden dit": ~$2.

### Log

- 2026-05-20: Methode + naming-conventie vastgelegd na Test 1 op WS3 voor L1 + L2. Key bevindingen: (1) micro-niveau lenzen prompt-gevoeliger dan macro, (2) positive-only-variant vond asymmetrische blindspot van neutrale variants (geen valence-filter), (3) strict overlap-rule downgrade-de 5 false-positive "robust" candidates.
- 2026-05-20 (later, na pad-C-revised): 3-pass als verplichte default. 4-laags tag-schema. Patroon "stille positieven in dichte context" met drie vormen vastgelegd. Belicht-beide-kanten-default toegevoegd met niet-forceren-clausule. Pending-observation-cross-ref naar Principes verwijderd, Positive-first is nu volwaardig vastgelegd onder `### Positive-first als anti-default-pull`.

---

## Bronnen

| Bron | Wat het bevat |
|------|---------------|
| **Social AI Principes** ([Principes](./SOCIAL-AI-PRINCIPES.md)) | Canonical bundle 15 principes, referentie voor prompt-vertaling |

---

*Samengesteld uit jaren facilitatie-praktijk en interne brondocumenten, maart 2026*

---

## Verder lezen in deze bundle

- [Principes](./SOCIAL-AI-PRINCIPES.md), 15 principes voor AI met groepswerk
- [Eigenaarschap](./OwnershipPrinciples.md), waar eigenaarschap vandaan komt
- [Bottom-up](./BottomUpPrinciples.md), hoe verandering bottom-up ontstaat
- [Leesgids](../README.md), overzicht en hoe deze docs samenhangen

---

*Onderdeel van [Thoughtful Social AI](../README.md). CC-BY-SA 4.0.*
