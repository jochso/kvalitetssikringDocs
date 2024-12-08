## Organisering af indsats
Det vil være en fordel at få medier kvalitetssikret først, så vi kan tage databasesiderne i en runde. For at undgå at der sker dobbelt-arbejde på mediefilerne, skal vi ikke være flere end 3 til at skrive i medier på samme tid.

Mens kvalitetssikringen af medier er undervejs, kan "Dokumentation" og "Indberetning" ikke kvalitetssikres på databaserne. Kvalitetssikringen af databaserne vil derfor være over to omgange/faser. Når kvalitetssikringen af medier er gennemført, går alle i gang med database-siderne. Det vil blive meldt ud hvornår vi kan begynde på "Dokumentation" og "Indberetning" siderne.

Vi laver status onsdag for at se fremdrift i processen.

Man vil som udgangspunkt blive startet med enten at kvalitetssikre medier, eller database-sider. (Udover Birgitte, som vil tage sig af "Nyheder" først.)

### Tildeling af opgaver

- Nyheder
	- Birgitte Dalgaard
- Medier
	- Johannes Sørensen
	- Anne Hjelm
- Database sider
	- Anne Hjelm
	- Tina Vammen
	- Nanna Vestergaard


### Noter om indhold

Hvis der i teksten står et # med et tal efter, betyder det at noget er fjernet fra teksten automatisk. (fx. **#232**) Efterlad dette i teksten, da vi senere vil se på hvad der blevet fjernet i 2025.

Hvis i finder en fejl som går igen flere gange skal i tage fat i mig. Så vil jeg se om det er noget vi kan automatisere i processen. Hvis det er tilfældet sender jeg en mail ud med at vi holder en pause i kvalitetssikringen, og derefter sender jeg en mail når vi går i gang igen.  En pause vil typisk ikke være mere end en 1 time, men ændringer i indhold vil blive overskrevet hvis de laves mens der er pause. Vi bruger versionsstyring for at undgå at vores arbejde går tabt i denne proces.

## Kvalitetssikring af Medier
Kvalitetssikringen af medier indebærer at organisere filer i mapper og give nye titler til de filer som er importeret fra den gamle RKKP hjemmeside. Ændringerne i et medie går igennem ude på hjemmesiden, og resultere i pæne links til de forskellige filer. Der er omtrent 550-600 filer i medie "galleriet".

Når man starter med at kvalitetssikre medier vælger man en tilfældig fil med et navn i retning af "5def10b6-ea4a-4d3f-a554-c0edef6f5564". Scroll gerne ned ad, men undgå de første 20 filer og sidste 20 filer. Vi regner med at sandsynligheden for at man ender på samme fil er lav i starten.

## Proces
![Proces - Medier|600](assets/Proces%20-%20Medier.png)

- Vælg en fil i højre menuen med et ID-navn (ex. 5def10b6-ea4a-4d3f-a554-c0edef6f5564) 
- Tryk på PDF-filen ved 1-tallet på billedet.
- Se hvad filen "er" og skriv databasen-navnet som filen vedrører, samt et beskrivende navn i feltet ved 2-tallet på billedet.
	- fx: DDID - Variabelliste
- Tryk på "Save" ved 3-tallet på billedet.

Her er en liste af typiske navne som kan copy-pastes fra, hvis det passer ind i dit workflow:

Beregningsregler
Dokumentalistrapport
Evidensrapport
Høringsrapport 20
Indikatorskema
Indikatorer
Kliniske retningslinjer
Officiel dokumentation
Variabelliste
Tillægsdokument
Årsrapport 20



## Kvalitetssikring af Database-sider
Status på kvalitetssikringen af database-siderne indrapporteres her: [Kvalitetssikring database.xlsx](https://regionmidtjylland-my.sharepoint.com/:x:/r/personal/jochso_onerm_dk/Documents/Dokumenter/Projekter/Ny%20Hjemmeside/Kvalitetssikring/Kvalitetssikring%20database.xlsx?d=wad3e4b98f23b4ed79f3e93b0ecde4247&csf=1&web=1&e=GNaS94)

For at undgå dobbeltarbejde er der tildelt 10 databaser pr. person til at starte med - herefter kan man tildele database sider til sig selv af de resterende. 

Hver underside kan markeres med et "x"  efter om de er klar eller afvist:
- "Klar" hentyder til "klar til offentliggørelse".
- Afvist bruges ved fejl i eksporten, og vil blive vægtet på basis til basis om det er en situation hvor vi går til leverandøren for at få det ordnet, eller selv fikser det. Det vil være beskrevet i processen herunder hvornår "afvist" skal bruges. 

Det anbefales at have to skærme, så rkkp.dk kan være på den ene skærm og den nye hjemmeside på den anden.

## Database Forside
![Database - Forside|600](assets/Database%20-%20Forside.png)


### Opgaver
1. Kvalitetssikring:
	1. Er navnet på databasen den samme som på RKKP.dk i titlen (A), PageTitle (B) og PageDisplayTitle (C)?
		1. NEJ: Ret det.
2. Færdig: Save and publish.

## ”Om Databasen”
**Der er tekst om formandskab og et link til oversigt over medlemmer. Lad dette stå i kvalitetssikringen, da det først tilrettes senere.**

### Opgaver
1. Kvalitetssikre "PageSubTitle" ("C" på [Side elementer](#page-elements))
	1. Er der ÅÆØ i teksten?
		1. NEJ: Markér som "Afvist"
	2. Er der HTML elementer som `<p></p>` eller `&nbsp;` i teksten?
		1. JA: Marker som "afvist"
2. Kvalitetssikre Body -> "Text":
	1. Er der tekst om databasens baggrund og/eller formål?
		1. NEJ: 
			1. Er teksten landet oppe i PageSubTitle? Klip det ned i body.
			2. Ellers, kopier teksten fra RKKP.dk. (hvis der ingen er  på RKKP da, markeres den som godkendt.)
	3. Ser teksten fornuftig ud?
		1. NEJ: Lav små rettelser for at gøre det acceptabelt, ellers marker som "afvist" i Excel arket. 
3. Færdig: Save and publish.
	1. Hvis ikke du kan publish er det fordi de øvre noder ikke er published. Rækkefølgen på opgaven burde forhindrer dette. Ellers lav kvalitetssikring på de øvre noder først.

## ”Dokumentation”
**Hvis ikke kvalitetssikringen af Medier er færdig springes dokumentation over og markeres ikke i Excel arket.**

- Kun PDF filer er flyttet automatisk til den nye site. Links til eksterne sider skal tilføjes til ”Resource” manuelt. Hvis der mangler links til PDF'er, som har adressen "https://www.rkkp.dk/siteassets/" skal siden markeres som "Afvist".

- I denne kvalitetssikring vil alle links/filer blive lagt under samme overskrift. Det vil være en opgave i 2025 at splitte indholdet op i mindre sektioner.

### Proces

1. Kvalitetssikre "PageSubTitle"
	1. Slet indholdet i PageSubTitle, hvis der står noget "html kode bras"
2. Kvalitetssikre "Resource"
	1. OBS: Ignorer kassen "Dokumentation" på rkkp.dk, denne tilføjes senere.
	2. Tilføj "ResourceTitle" til Resource:
		1. Samlet dokumentation
	3. Er der samme antal links til indhold på RKKP.dk som der er under "Resources"?
		1. NEJ: Tilføj links til "Resources". Dette bør kun være til eksterne sider, eller PDF'er udenfor "https://www.rkkp.dk/siteassets/".
	4. Er alle "Resources" navngivet? (dvs. titlen ikke er fx. "9a30b2e6-d48b-4689-8a5b-42f0a33c599d")
		1. NEJ: Ret navnet.
3. Færdig: Save and Publish
	1. Hvis ikke du kan publish er det fordi de øvre noder ikke er published. Rækkefølgen på opgaven burde forhindrer dette. Ellers lav kvalitetssikring på de øvre noder først.

Standardiserede navne (til copy paste):

- Kommer når de kendes...

## ”Indberetning”
**Kun PDF filer er flyttet automatisk til den nye site. Links til eksterne sider skal tilføjes til ”Ressource”.**

- Teksten til ”Link title” må gerne være omtrentlig, og behøver ikke være præcis den samme som på RKKP.

- Underoverskriften som "Skemaer", "Registervejledninger" og "Øvrige" ignoreres under kvalitetssikringen. Alt ligges under samme overskrift.

### Proces

1. Kvalitetssikre "PageSubTitle"
	1. Slet indholdet i PageSubTitle, hvis der står noget "html kode bras"
2. Kvalitetssikre "Resource"
	1. OBS: Ignorer kassen "Indberetningssystem" på rkkp.dk, denne tilføjes senere.
	2. Tilføj "ResourceTitle" til Resource:
		1. Hjælp til registrering
	3. Er der samme antal links til indhold på RKKP.dk som der er under "Resources"?
		1. NEJ: Tilføj links til "Resources". Dette bør kun være til eksterne sider, eller PDF'er udenfor "https://www.rkkp.dk/siteassets/".
	4. Er alle "Resources" navngivet? (dvs. titlen ikke er fx. "9a30b2e6-d48b-4689-8a5b-42f0a33c599d")
		1. NEJ: Ret navnet ved at ændre: "Link title"
3. Færdig: Save and Publish.
	1. Hvis ikke du kan publish er det fordi de øvre noder ikke er published. Rækkefølgen på opgaven burde forhindrer dette. Ellers lav kvalitetssikring på de øvre noder først.

## ”Viden”
- Under "viden" findes normalt kun Årsrapporter og Onepagers. Hvis der er andet, indhold markeres det i kommentar feltet i Excel.

### Proces

1. Save and Publish "Viden" oversiden
2. Kvalitetssikre undersider
	1. Kvalitetssikre "ReportTitle"
		1. OBS: Hvis en årsrapport er fra 2024, skal "ShownOnNewKnowledge" være aktiveret.
		2. Tryk på filen for at åbne den i et nyt vindue.
		3. Er det den korrekte ReportTitle, i formatet "Årsrapport 2019" eller "Onepage 2021"?
			1. NEJ: Ret ReportTitle.
		4. Kopier "ReportTitle" til Titlen på siden.
		5. Færdig: Save and Publish
			1. Hvis ikke du kan publish er det fordi de øvre noder ikke er published. Rækkefølgen på opgaven burde forhindrer dette. Ellers lav kvalitetssikring på de øvre noder først.
3. Kvalitetssikre overordnet indhold:
		1. OBS: Ignorer "Tidsplan for næste årsrapport" og "Tidligere Årsrapporter". Disse tilføjes senere.
		2. OBS: Ignorer "Daglige Data"-boksen.
		3. Er der det samme antal undersider på den nye side som der er links til indhold på RKKP.dk?
			1. NEJ: Markér i Excel ark.

## ”Nyheder fra …”
**Husk at "OverrideDate" er den dato som hjemmesiden sorterer efter i front-end. Rækkefølgen i Umbraco har ingen betydning og kan rettes senere.**

### Proces

1. Save and Publish "Nyheder fra ...." oversiden
2. Kvalitetssikre hver nyhed:
	1. Kvalitetssikre dato:
		1. Er "OverrideDate" fra før 2024?
			1. JA: Slet nyheden.
	2. Kvalitetssikre PageTitle
		1. Ser det forkert ud?
			1. JA: Ret det.
	3. Kvalitetssikre PageSubTitle
		1. Er der ÅÆØ i teksten?
			1. JA: Fortsæt.
		2. Er der HTML i teksten?
			1. JA: Slet det.
	4. Kvalitetssikre Text -> Body
		1. Ser det rigtigt ud?
			1. NEJ: Lav små rettelser for at gøre det acceptabelt, ellers marker som "afvist" i Excel arket. 


## Kvalitetssikring af Nyheder



# Opgaver (Efter kvalitetssikring)
Disse opgaver skal løses ved hjælp af Umbraco værktøjer, og skal laves efter kvalitetssikringen/kundetesten er færdig.

Da processen ikke er helt på plads kommer de senere.

## Tilføj "Dokumentation"-boks til "Dokumentation"-side
- Beskrivelse kommer senere.

## Tilføj  "Indberetningssystem"-boks til "Indberetning-side"
- Beskrivelse kommer senere.

## Tilføj "Tidsplan for årsrapporter" til "Viden"-side.
- Beskrivelse kommer senere...

## Tilføj "Ved sammenligning" til "Viden"-side
- Beskrivelse kommer senere...

## Tilføj "Information til..."
- Beskrivelse kommer senere...

## Tilføj "Vil du vide mere?"
- Beskrivelse kommer senere...

# Elementer i Umbraco

<a name="page-element"></a>
## Side elementer

![Page Elements|600](assets/Page%20Elements.png)
### Title (A)
Vises kun i back-end af hjemmeside.
### PageTitle (B)
Den tekst som som bruges til at navngive siden for brugerne i front-end. (Tilsvarende rubrik)
### PageSubTitle (C)
Den indledende tekst (underrubrik) under rubrikken.
## PageDisplayTitle (D)
Alternativ titel. Skal i kvalitetssikring være den samme som PageTitle.
## PageDisplaySubTitle (E)
Alternativ underrubrik. Skal i kvalitetssikring være tom, da den ikke endnu er implementeret.

## Body -> Text elementer
![Body Elements|600](assets/Body%20Elements.png)
## Body -> Text (A)
Hovedteksten. I kvalitetssikringen vil meget indhold blive lagt her, da det er svært at få til at lande mere avanceret.
## Body -> Title (B)
Rubrikken til teksten. Vil i kvalitetssikringen være tom.
## Body -> Subtitle (C)
Underrubrikken. Vil i kvalitetssikringen være tom.

## Resource
- Kommer snart...


# Hvordan gør jeg ....

## Retter en resource

### Tilføje en titel til en resource
1. Åben din "resource"
![Proces - Resource - Open Resource|450](assets/Proces%20-%20Resource%20-%20Open%20Resource.png)
2. Tryk på "Edit"
![Proces - Resource - Edit|450](assets/Proces%20-%20Resource%20-%20Edit.png)
3. Skriv et navn i "Link Title". Dette er teksten som bliver vist på "knappen" på hjemmeside.
![Proces - Resource - Add Title|450](assets/Proces%20-%20Resource%20-%20Add%20Title.png)

## Slet en resource
1. Åben din "resource"
![Proces - Resource - Open Resource|450](assets/Proces%20-%20Resource%20-%20Open%20Resource.png)
2. Tryk på "Remove"
![Proces - Resource - Remove|450](assets/Proces%20-%20Resource%20-%20Remove.png)


## Retter en body -> Text

## Tilføjer en underside.
- Kommer snart...