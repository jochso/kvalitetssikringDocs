## Organisering af indsats
Det vil være en fordel at få medier kvalitetssikret først, så vi kan tage databasesiderne i en runde. For at undgå at der sker dobbelt-arbejde på mediefilerne, skal vi ikke være flere end 3 til at skrive i medier på samme tid.

Mens kvalitetssikringen af medier er undervejs, kan "Dokumentation" og "Indberetning" ikke kvalitetssikres på databaserne. Kvalitetssikringen af databaserne vil derfor være over to omgange/faser. Når kvalitetssikringen af medier er gennemført, går alle i gang med database-siderne. Det vil blive meldt ud hvornår vi kan begynde på "Dokumentation" og "Indberetning" siderne.

Vi laver status onsdag for at se fremdrift i processen.

Man vil som udgangspunkt blive startet med enten at kvalitetssikre medier, eller database-sider. (Udover Birgitte, som vil tage sig af "Nyheder" først.)

### Tildeling af opgaver

- Nyheder
	- Birgitte Dalgaard
- Medier
	- Anne Hjelm
	- Nanna Vestergaard
- Database sider
	- Anne Hjelm
	- Tina Vammen
	- Nanna Vestergaard
	- Johannes Sørensen


### Noter om indhold

Hvis der i teksten står et # med et tal efter, betyder det at noget er fjernet fra teksten automatisk. (fx. **#232**) Efterlad dette i teksten, da vi senere vil se på hvad der blevet fjernet i 2025.

Hvis i finder en fejl som går igen flere gange skal i tage fat i mig. Så vil jeg se om det er noget vi kan automatisere i processen. Hvis det er tilfældet sender jeg en mail ud med at vi holder en pause i kvalitetssikringen, og derefter sender jeg en mail når vi går i gang igen.  En pause vil typisk ikke være mere end en 1 time, men ændringer i indhold vil blive overskrevet hvis de laves mens der er pause. Vi bruger versionsstyring for at undgå at vores arbejde går tabt i denne proces.

## Kvalitetssikring af Medier
Kvalitetssikringen af medier indebærer at organisere filer i mapper og give nye titler til de filer som er importeret fra den gamle RKKP hjemmeside. Ændringerne i et medie går igennem ude på hjemmesiden, og resultere i pæne links til de forskellige filer. Der er omtrent 550-600 filer i medie "galleriet".

Når man starter med at kvalitetssikre medier vælger man en tilfældig fil med et navn i retning af "5def10b6-ea4a-4d3f-a554-c0edef6f5564". Scroll gerne ned ad, men undgå de første 20 filer og sidste 20 filer. Vi regner med at sandsynligheden for at man ender på samme fil er lav i starten.

## Proces
![Proces - Medier|600](assets/Proces%20-%20Medier.png)

**Jeg har problemer med at åbne nogle filer, som ikke er PDF. Meld gerne tilbage om i oplever det samme. Efterlad filer som ikke kan åbnes med det "grimme" navn.**

- Vælg en fil i højre menuen med et ID-navn (ex. 5def10b6-ea4a-4d3f-a554-c0edef6f5564) 
- Tryk på PDF-filen ved 1-tallet på billedet. *Hvis filen ikke er en PDF, kan den muligvis ikke åbnes. Efterlad den da med det "grimme" navn.*
- Se hvad filen "er" og skriv databasen-navnet som filen vedrører, samt et beskrivende navn i feltet ved 2-tallet på billedet.
	- fx: DDID - Variabelliste
- Tryk på "Save" ved 3-tallet på billedet eller bare tryk enter når du har skrevet titlen. Der kommer en advarsel hvis den ikke gemmer.

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
2. Færdig: Save and publish. (Se [Save and publish](#save-and-publish))

## ”Om Databasen”
**Der er tekst om formandskab og et link til oversigt over medlemmer. Lad dette stå i kvalitetssikringen, da det først tilrettes senere.**

### Opgaver
1. Kvalitetssikre "PageSubTitle" ("C" på [Side elementer](#side-elementer))
	1. Er der ÅÆØ i teksten?
		1. NEJ: Markér som "Afvist"
	2. Er der HTML elementer som `<p></p>` eller `&nbsp;` i teksten?
		1. JA: Marker som "afvist"
2. Kvalitetssikre Body -> "Text": 
	1. Er der tekst om databasens baggrund og/eller formål? ("A" på [Body -> Text elementer](##body---text-elementer))
		1. NEJ: 
			1. Er teksten landet oppe i PageSubTitle? Klip det ned i body.
			2. Ellers, kopier teksten fra RKKP.dk. (hvis der ingen er  på RKKP da, markeres den som godkendt.)
	3. Ser teksten fornuftig ud?
		1. NEJ: Lav små rettelser for at gøre det acceptabelt, ellers marker som "afvist" i Excel arket. 
3. Færdig: Save and publish. (Se [Save and publish](#save-and-publish))
	1. Hvis ikke du kan publish er det fordi de øvre noder ikke er published. Rækkefølgen på opgaven burde forhindrer dette. Ellers lav kvalitetssikring på de øvre noder først.

## ”Dokumentation”
**Hvis ikke kvalitetssikringen af Medier er færdig springes dokumentation over og markeres ikke i Excel arket.**

- Kun PDF filer er flyttet automatisk til den nye site. Links til eksterne sider skal tilføjes til ”Resource” manuelt. Hvis der mangler links til PDF'er, som har adressen "https://www.rkkp.dk/siteassets/" skal siden markeres som "Afvist".

- I denne kvalitetssikring vil alle links/filer blive lagt under samme overskrift. Det vil være en opgave i 2025 at splitte indholdet op i mindre sektioner.

### Proces

1. Kvalitetssikre "PageSubTitle" ("C" på [Side elementer](#side-elementer))
	1. Slet indholdet i PageSubTitle, hvis der står noget "html kode bras"
2. Kvalitetssikre "Resource"
	1. OBS: Ignorer kassen "Dokumentation" på rkkp.dk, denne tilføjes senere.
	2. Tilføj "ResourceTitle" til Resource:
		1. Samlet dokumentation
	3. Er der samme antal links til indhold på RKKP.dk som der er under "Resources"?
		1. NEJ: Tilføj links til "Resources". Dette bør kun være til eksterne sider, eller PDF'er udenfor "https://www.rkkp.dk/siteassets/".
	4. Er alle "Resources" navngivet? (dvs. titlen ikke er fx. "9a30b2e6-d48b-4689-8a5b-42f0a33c599d")
		1. NEJ: Lad dem stå. Vi skal løse dette problem indefra medier.
3. Færdig: Save and Publish (Se [Save and publish](#save-and-publish))
	1. Hvis ikke du kan publish er det fordi de øvre noder ikke er published. Rækkefølgen på opgaven burde forhindrer dette. Ellers lav kvalitetssikring på de øvre noder først.

Standardiserede navne (til copy paste):

- Kommer når de kendes...

## ”Indberetning”
**Kun PDF filer er flyttet automatisk til den nye site. Links til eksterne sider skal tilføjes til ”Ressource”.**

- Teksten til ”Link title” må gerne være omtrentlig, og behøver ikke være præcis den samme som på RKKP.

- Underoverskriften som "Skemaer", "Registervejledninger" og "Øvrige" ignoreres under kvalitetssikringen. Alt ligges under samme overskrift.

### Proces

1. Kvalitetssikre "PageSubTitle" ("C" på [Side elementer](#side-elementer))
	1. Slet indholdet i PageSubTitle, hvis der står noget "html kode bras"
2. Kvalitetssikre "Resource"
	1. OBS: Ignorer kassen "Indberetningssystem" på rkkp.dk, denne tilføjes senere.
	2. Tilføj "ResourceTitle" til Resource:
		1. Hjælp til registrering
	3. Er der samme antal links til indhold på RKKP.dk som der er under "Resources"?
		1. NEJ: Tilføj links til "Resources". Dette bør kun være til eksterne sider, eller PDF'er udenfor "https://www.rkkp.dk/siteassets/".
	4. Er alle "Resources" navngivet? (dvs. titlen ikke er fx. "9a30b2e6-d48b-4689-8a5b-42f0a33c599d")
		1. NEJ: Lad dem stå. Vi skal løse dette problem indefra medier.
3. Færdig: Save and Publish. (Se [Save and publish](#save-and-publish))
	1. Hvis ikke du kan publish er det fordi de øvre noder ikke er published. Rækkefølgen på opgaven burde forhindrer dette. Ellers lav kvalitetssikring på de øvre noder først.

## ”Viden”
- Under "viden" findes normalt kun Årsrapporter og Onepagers. Hvis der er andet, indhold markeres det i kommentar feltet i Excel.

### Proces

1. Save and Publish "Viden" oversiden (Se [Save and publish](#save-and-publish))
2. Er der lige så mange undersider med GUID ("9a30b2e6-d48b-4689-8a5b-42f0a33c599d") navne som med rigtige navne?
	1. JA: Slet alle de undersider som har en GUID.
	2. NEJ: Slet de undersider som har en tilsvarende underside med rigtigt navn.
3. Kvalitetssikre undersider
	1. Kvalitetssikre "ReportTitle"
		1. ~~OBS: Hvis en årsrapport er fra 2024, skal "ShownOnNewKnowledge" være aktiveret.~~
		2. Tryk på filen for at åbne den i et nyt vindue.
		3. Er det den korrekte ReportTitle, i formatet "Årsrapport 2019" eller "Onepage 2021"?
			1. NEJ: Ret ReportTitle.
		4. Kopier "ReportTitle" til Titlen på siden.
		5. Færdig: Save and Publish (Se [Save and publish](#save-and-publish))
			1. Hvis ikke du kan publish er det fordi de øvre noder ikke er published. Rækkefølgen på opgaven burde forhindrer dette. Ellers lav kvalitetssikring på de øvre noder først.
4. Kvalitetssikre overordnet indhold:
		1. OBS: Ignorer "Tidsplan for næste årsrapport" og "Tidligere Årsrapporter". Disse tilføjes senere.
		2. OBS: Ignorer "Daglige Data"-boksen.
		3. Er der det samme antal undersider på den nye side som der er links til indhold på RKKP.dk?
			1. NEJ: Markér i Excel ark.

## ”Nyheder fra …”
**Husk at "OverrideDate" er den dato som hjemmesiden sorterer efter i front-end. Rækkefølgen i Umbraco har ingen betydning og kan rettes senere.**

**Der er blevet kørt en aggressiv oprydning i nyheder for at fjerne links som ikke længere virker. Det betyder at hele sætninger, som knytter sig til filer/links der ikke længere eksisterer er blevet fjernet. Derfor vil noget tekst ende "blindt" hvis en sætning er blevet fjernet. Lav eventuelt små rettelser til dette, men ikke brug for meget tid på det.**

### Proces

1. Save and Publish "Nyheder fra ...." oversiden (Se [Save and publish](#save-and-publish))
2. Kvalitetssikre hver nyhed:
	1. Kvalitetssikre dato:
		1. Er "OverrideDate" fra før 2024?
			1. JA: Slet nyheden.
	2. Kvalitetssikre PageTitle ("B" på [Side elementer](#side-elementer))
		1. Ser det forkert ud?
			1. JA: Ret det.
	3. Kvalitetssikre PageSubTitle ("C" på [Side elementer](#side-elementer))
		1. Er der ÅÆØ i teksten?
			1. JA: Fortsæt.
		2. Er der HTML i teksten?
			1. JA: Slet det.
	4. Kvalitetssikre Text -> Body ("A" på [Body -> Text elementer](##body---text-elementer))
		2. Ser det rigtigt ud?
			1. NEJ: Lav små rettelser for at gøre det acceptabelt, ellers marker som "afvist" i Excel arket. 
	5. Færdig: Save and Publish (Se [Save and publish](#save-and-publish))


## Kvalitetssikring af Nyheder



# Opgaver (Efter kvalitetssikring)
Disse opgaver skal løses ved hjælp af Umbraco værktøjer, og skal laves efter kvalitetssikringen/kundetesten er færdig. Eventuelt i 2025.

Da processen ikke er helt på plads kommer mange af dem senere.

## Rette "Viden"
### Formål / Problematik
Et "underobjekt" i "Viden" bliver af systemet ses som en Årsrapport. Den tager "underobjekter" og tilføjer under en overskrift som hedder "Årsrapporter". Den automatiske flytning har også lagt "Onepagers" ind under viden - og derfor står de nu forkert:

![Rette Viden - Problematik|600](assets/Rette%20Viden%20-%20Problematik.png)

### Proces
1. Tryk på "Viden", og fold den ud for at se om der er en "Onepager".
2. Hvis der er en onepager, kan du på "Viden" se om der en tom "Resources" du kan bruge, ellers tryk på "Add ArticleResourceSection" knappen.
4. Skriv "Onepagers" i "ResourceTitle"
5. Tryk på "Add" ud for "Resources"
6. Tryk på "Select Media".
	1. Her bliver det lidt svært, da vi skal finde PDF filen i media. Heldigvis har vi navngivet medier.
	2. Prøv at søge på databasens forkortelse, fx. DDD
	3. Prøv at søge på databasens fuldenavn, fx. Dansk Depressions Database
	4. Hvis ikke der kommer en onepager frem som du kan genkende - markér det som "Afvist" i Excel og gå videre til næste database.
7. Hvis du har fundet filen, tryk på den og tryk på "Select" nede i bunden.
8. Skriv titlen i "Link title", f.eks. "Onepager 2022". Jeg tror ikke at vi kan have de fulde titler på Onepagers i links kasserne - da de har det med at være meget, **meget** lange.
9. Tryk på "Submit", og på "Submit", og på "Save and Publish".
10. Højreklik på underobjektet "Onepager XXXX" og tryk "Delete".

Resultat:

![Rette Viden - Problematik løst|600](assets/Rette%20Viden%20-%20Problematik%20løst.png)

## Opdele "Dokumentation"
### Formål / Problematik
"Dokumentation"-siden er oftest opdelt i to: "Evidensgrundlag" og "Dokumentation". Indholdet er oftest "det samme". Den automatiske import har lagt det hele under samme overskrift. Formålet er at opdele dem igen. Da det meste indhold er "Dokumentation", er det bedst at tilføje "Evidensgrundlag" og omdøbe den nuværende til "Dokumentation".

![Opdele Dokumentation - Problematik|600](assets/Opdele%20Dokumentation%20-%20Problematik.png)

1. Åben en "Dokumentation"-side.
2. Tryk på den "Resources" som allerede er der.
3. Skriv "Dokumentation" til "ResourceTitle".
4. Omdøb de relevante Resourcer til standariserede navne:
	1. Databasens indikatorer
	2. Beregningsregler
	3. Variabelliste
5. Tryk på "Submit".
6. Tryk på "Add ArticleResourceSection".
7. Skriv "Evidensgrundlag" i "ResourceTitle".
8. Tryk på "Create".
9. Tryk på "Add" ud for "Resources"
10. Tryk på "Select Media".
	1. Her bliver det lidt svært, da vi skal finde PDF filen i media. Heldigvis har vi navngivet medier.
	2. Prøv at søge på databasens forkortelse, fx. DDD
	3. Prøv at søge på databasens fuldenavn, fx. Dansk Depressions Database
	4. Hvis ikke der kommer et dokument frem som du kan genkende - markér det som "Afvist" i Excel og gå videre til næste database.
11. Hvis du har fundet filen, tryk på den og tryk på "Select" nede i bunden.
12. Tryk på "Submit" og "Submit".
13. Flyt den nederste "Resources" i toppen af listen ved at "drag and drop" den, så "Evidensgrundlag" er øverst.
14. Tryk på den nederste ("Dokumentation"-Resource) og tryk på "Remove" ud fra den Resource du lige har tilføjet.

![Opdele Dokumentation - Problematik Løst|600](assets/Opdele%20Dokumentation%20-%20Problematik%20Løst.png)

## Tilføj  "Indberetningssystem"-boks til "Indberetning-side"
- Krav:
	- KIP side oprettet.
	- Support side oprettet.

## Tilføj "Tidsplan for årsrapporter" til "Viden"-side.
- Lav en resource og kopier den til alle Viden sider:
	- Titel:
	- Links:
		- Tidsplan for næste årsrapport
			- https://rkkp-databaseoversigt.dk/reportspublic/annualreports
## Tilføj "Daglige data" boks til "Viden"-side

## Tilføj "Ved sammenligning" til "Viden"-side
- Beskrivelse kommer senere...

## Tilføj "Information til..."
- Beskrivelse kommer senere...


## Tilføj "Variabelliste"
- Beskrivelse kommer senere...



## Sortér bokse under database sider
- Beskrivelse kommer senere...

## Opdatér PageDisplaySubTitle

# Elementer i Umbraco

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



# Hvordan gør jeg ....

## "Save and Publish"
1. På alle sider, er "Save and Publish" nede i hjørnet.
![Proces - Save and Publish|500](assets/Proces%20-%20Save%20and%20Publish.png)

## Retter en resource

### Tilføje en titel til en resource
1. Åben din "resource"
![Proces - Resource - Open Resource|500](assets/Proces%20-%20Resource%20-%20Open%20Resource.png)
2. Tryk på "Edit"
![Proces - Resource - Edit|500](assets/Proces%20-%20Resource%20-%20Edit.png)
3. Skriv et navn i "Link Title". Dette er teksten som bliver vist på "knappen" på hjemmeside.
![Proces - Resource - Add Title|500](assets/Proces%20-%20Resource%20-%20Add%20Title.png)

## Slet en resource
1. Åben din "resource"
![Proces - Resource - Open Resource|500](assets/Proces%20-%20Resource%20-%20Open%20Resource.png)
2. Tryk på "Remove"
![Proces - Resource - Remove|500](assets/Proces%20-%20Resource%20-%20Remove.png)


## Tilføj en ny adresse


## Retter en body -> Text

## Tilføjer en underside.
- Kommer snart...