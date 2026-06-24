# OS2sofd - Selvevaluering

**Udfyldt af:** OS2sofd styregruppe

**Dato:** 2026-06-23

**Kilde:** `os2sofd-20260624T120121Z.json`

---

## R1 - Løsningen skaber lokal værdi

**Status:** 🟢 Ja

**Kategori:** relevans

**Retningslinjer:**

Beskriv den konkrete værdi løsningen skaber i organisationen. F.eks. økonomisk, organisatorisk eller brugerrelateret.

**Dokumentation:**

OS2sofd samler autoritative organisationsdata, understøtter IdM-processer, integrationer og distribution af forretningsdata.
https://boks.os2.eu/s/QmWBeFYe8po3NbW?dir=/&editing=false&openfile=true

---

## R2 - Løsningen er accepteret af lokal linjeledelse

**Status:** 🟢 Ja

**Kategori:** relevans

**Retningslinjer:**

Beskriv eller henvis til en formel accept fra ledelse hos initiativtagerne til løsningen.

**Dokumentation:**

Løsningen er fra start taget i anvendelse af kommunerne i DIGIT og 3K kommunerne

---

## R3 - Løsningen har fælles offentligt potentiale

**Status:** 🟢 Ja

**Kategori:** relevans

**Retningslinjer:**

Redegør for hvordan løsningen kan bruges på tværs af kommuner og/eller offentlige myndigheder.

**Dokumentation:**

OS2sofd anvendes af mere end 50 kommuner og er en veletableret fælleskommunal løsning.

Løsningen understøttes af et aktivt community med løbende erfaringsudveksling, koordinering og fælles prioritering af udviklingsønsker. Der gennemføres to velbesøgte årlige ERFA-møder, som bidrager til videndeling og styrker det tværkommunale samarbejde omkring løsningen.

Den brede anvendelse og det aktive fællesskab dokumenterer et betydeligt fællesoffentligt potentiale og en fortsat interesse for fælles udvikling og genbrug på tværs af kommunerne.

---

## R4 - Ophæng til nationale strategier er til stede

**Status:** ⚪ Ikke relevant

**Kategori:** relevans

**Retningslinjer:**

Henvis til relevante strategier og forklar hvordan løsningen understøtter disse.

**Dokumentation:**



---

## F1 - Alt kildekode til projektet udvikles synligt og aktivt i et repositorie og versionskontrolsystem, anvist af OS2

**Status:** 🟢 Ja

**Kategori:** formkrav

**Retningslinjer:**

Upload al kildekode i et offentligt OS2 repository med aktiv versionshistorik.

**Dokumentation:**

OS2sofd udvikles i leverandørens primære udviklingsrepository som led i den daglige udviklings- og releaseproces. Ved hver kvartalsrelease overføres den samlede kildekode til det officielle OS2-repository, som dermed fungerer som det autoritative open source-repository for produktet.

Denne model er valgt for at sikre en effektiv udviklingsproces, samtidig med at OS2-fællesskabet til enhver tid har adgang til den aktuelle frigivne kildekode, den fulde versionshistorik for de frigivne versioner samt mulighed for at overtage videreudvikling af løsningen.

Løsningen vurderes derfor at opfylde intentionen bag kravet om åbenhed, gennemsigtighed og fælles ejerskab af kildekoden. Det anerkendes dog, at udviklingen ikke foregår direkte i OS2-repositoriet på daglig basis, men at synkronisering sker ved de regelmæssige kvartalsvise releases.
Der er samtidig tale om et aktivt vedligeholdt repository med løbende releases. Seneste release er overført til OS2-repositoriet i forbindelse med den kvartalsvise releaseproces, og repositoryet indeholder dokumenteret versionshistorik for produktet. Udviklingsaktiviteten i leverandørens repository afspejles efterfølgende i de frigivne versioner i OS2-repositoriet.

---

## F2 - Open Source licenskriterier overholdes

**Status:** 🟢 Ja

**Kategori:** formkrav

**Retningslinjer:**

Angiv hvilken OSI-godkendt licens projektet bruger. OS2 standard er MPL 2.0

**Dokumentation:**

Frigivet under Mozilla Public License 2.0.

---

## F3 - Udbudsregler og alm. lovformlighed er overholdt

**Status:** 🔴 Ved ikke

**Kategori:** formkrav

**Retningslinjer:**

Bekræft at udbudspligt er overholdt eller redegør for undtagelse. Vedlæg evt. beslutningsnotat.

**Dokumentation:**

I den tidligere OS2-governancevurdering er det anført, at de udbudsretlige forhold blev afklaret i forbindelse med ibrugtagning hos DIGIT og 3K. Der foreligger dog ikke dokumentation herfor i det tilgængelige materiale.

---

## F4 - Der er tænkt på sikkerheden i løsningen

**Status:** 🟢 Ja

**Kategori:** formkrav

**Retningslinjer:**

Beskriv hvordan sikkerhed er indtænkt i design, kode og drift – f.eks. kryptering, adgangsstyring.

**Dokumentation:**

OS2sofd er designet med fokus på sikkerhed og databeskyttelse. Løsningen anvender rollebaseret adgangsstyring, fødereret login via SAML, rettighedsstyrede API'er, dataafgrænsning og logning. Der føres historik over alle dataændringer og auditlogs over centrale processer. Adgang til API'er sker via API-nøgler med afgrænsede rettigheder, og data deles kontrolleret med tilknyttede systemer. Arkitekturen er desuden opbygget efter principper om security-by-design og privacy-by-design.

---

## F5 - Løsningens formål og værdi er beskrevet

**Status:** 🟢 Ja

**Kategori:** formkrav

**Retningslinjer:**

Henvis til dokumentation (f.eks. README) hvor formål og målgruppe fremgår.

**Dokumentation:**

Formål og målgruppe er beskrevet i produktbeskrivelsen for OS2sofd. Løsningen beskrives som fundamentet for organisationens data- og identitetsstyring, hvor autoritative organisationsdata samles ét sted og anvendes til bruger- og adgangsstyring, integrationer og automatisering af IdM-processer. Dokumentationen er målrettet både beslutningstagere, arkitekter og driftsorganisationer i kommunerne. https://boks.os2.eu/s/QmWBeFYe8po3NbW?dir=/&editing=false&openfile=true

---

## F6 - Kildekoden er overdraget og er placeret under OS2's kontrol

**Status:** 🟢 Ja

**Kategori:** formkrav

**Retningslinjer:**

Bekræft og link til det officielle repository i OS2s versionskontrol.

**Dokumentation:**

https://github.com/OS2sofd/os2sofd


---

## F7 - Alt dokumentation til projektet udarbejdes med og overholder OS2s standardskabelon for dokumentation.

**Status:** 🔴 Nej

**Kategori:** formkrav

**Retningslinjer:**

Brug OS2’s standard template til dokumentation. http://github.com/OS2offdig/os2-docs-template

**Dokumentation:**

Der foreligger omfattende produkt-, drifts-, arkitektur- og præsentationsdokumentation for OS2sofd, herunder produktbeskrivelse, teknisk dokumentation, driftsbeskrivelser og præsentationsmateriale. Dokumentationen er dog ikke på nuværende tidspunkt struktureret efter OS2's standardiserede dokumentationsskabelon.

Eksisterende dokumentation vil kunne danne grundlag for en fremtidig tilpasning til OS2's dokumentationsstandard, hvis dette prioriteres som en del af produktets videre modning.

Henvisninger:
https://www.sofd.io/documentation/SOFD%20Core%20-%20Produktbeskrivelse.pdf
https://www.sofd.io/documentation/SOFD%20Core%20-%20pr%C3%A6sentationsmateriale.pdf
https://www.sofd.io/documentation/SOFD%20Core%20-%20IdM%20processer%20-%20overblik.pdf

---

## F10 - OS2's kommunikationskanaler anvendes (OS2.eu)

**Status:** 🟢 Ja

**Kategori:** formkrav

**Retningslinjer:**

Bekræft og link til omtale på f.eks. os2.eu, nyhedsbrev eller andet.

**Dokumentation:**

Arrangementer:
https://os2offdig.odoo.com/event/os2sofd-erfalab-150/register
https://os2offdig.odoo.com/event/os2sofd-erfa-dag-136/register
Nyhedsbrev:
https://app.heyloyalty.com/view/ZXlKcGRpSTZJbU5pVVd4eFVXRXliamhIZG1vMlNteDZhVEJDU2tFOVBTSXNJblpoYkhWbElqb2lia1pXVFdWalZXcFpSMVV4YVVsc1lqVmFXbWxqV1c5bVpuaERhMU5pVERSRlJsSm5USHBPVG5vNFlUQkxLMGhzTTJObFZHeDNRaTlWV1VOVllpc3ZLMlphYVZobVdEbFhUbWN6TW5Cck5HaDZNVmN6VUhKaVpYSnJNbGROU0dob1VVcDVTbGRTZDNwNWVuVlJlbmt6VUhKT1UzZFViRzlMVHpCc1JERmhlbXBwVHpNeFNUUXljeXRSU0hSaGJEUXlMelUzU0RsMFpVdDVjM05WVURGVlZFczRUbXR5ZUdNNGFUazBQU0lzSW0xaFl5STZJbVEwTURBeE5HWXhPRFJqWlRBME1USXpOamt6WXprM1pUTTJPVFkwTnpRME5EaGtZVEJtTXpRME0yVmhaV1JpWldNNE5tWTBZVFl4WVRoalptVmxOVElpTENKMFlXY2lPaUlpZlE9PQ==

---

## F11 - Der anvendes offentlig issue-tracking anvist af OS2, hvor der tydeligt henvises til specifikke kodeændringer

**Status:** 🔴 Nej

**Kategori:** formkrav

**Retningslinjer:**

Henvis til f.eks. Issues, hvor opgaver er koblet til pull-requests/commits.

**Dokumentation:**

OS2sofd anvender GitHub Projects som offentlig platform til registrering, prioritering og håndtering af ændringsønsker. Projektet har en synlig proces for behandling af ønsker fra idé til færdig løsning, og ændringsønsker er offentligt tilgængelige via GitHub.

Der foreligger dog ikke på nuværende tidspunkt dokumentation for en systematisk kobling mellem ændringsønsker, pull requests og konkrete commits i det offentlige repository, som foreskrevet i kravet. Kravet vurderes derfor kun delvist opfyldt.

Henvisning:
https://github.com/orgs/OS2sofd/projects/1/views/1

---

## F12 - Der er kun en version af core koden

**Status:** 🟢 Ja

**Kategori:** formkrav

**Retningslinjer:**

Bekræft at der kun findes én ‘main’ version og at den er aktivt vedligeholdt.

**Dokumentation:**

OS2sofd har én fælles hovedversion af core-koden (master), som fungerer som den autoritative kodebase for produktet. Repositoryet vedligeholdes aktivt med løbende fejlrettelser, forbedringer og release-forløb, senest dokumenteret gennem commits og releases i 2026.

---

## F13 - Der er udarbejdet præsentationsmateriale af løsningen

**Status:** 🟢 Ja

**Kategori:** formkrav

**Retningslinjer:**

Link til f.eks. slides, brochurer eller andet introduktionsmateriale.

**Dokumentation:**

https://boks.os2.eu/s/QmWBeFYe8po3NbW?dir=/&editing=false&openfile=true

---

## F14 - Der er udarbejdet kommunikationsmateriale til strategisk niveau

**Status:** 🟢 Ja

**Kategori:** formkrav

**Retningslinjer:**

F.eks. businesscase, one-pager til direktionsniveau og præsentation til udvalg.

**Dokumentation:**

https://boks.os2.eu/s/QmWBeFYe8po3NbW?dir=/&editing=false&openfile=true

---

## F15 - Best practice for implementering i organisationen dokumenteres

**Status:** 🟢 Ja

**Kategori:** formkrav

**Retningslinjer:**

Angiv implementeringsvejledning, erfaringsopsamling eller cases.

**Dokumentation:**

Der foreligger implementeringsdokumentation for OS2sofd i form af implementeringsdrejebøger, tekniske vejledninger og integrationsbeskrivelser. Dokumentationen omfatter blandt andet "Drejebog til idriftsættelse af IdM Etape 2" og "Drejebog til idriftsættelse af IdM Etape 3" samt vejledninger til opsætning af integrationer, SAML-login, AD-synkronisering og Identity Management-processer.

Dokumentationen indeholder både praktiske implementeringsanbefalinger og beskrivelser af anbefalede implementeringsforløb for kommuner.

Henvisning:
https://www.sofd.io/documentation.html

---

## F16 - Teknisk dokumentation indeholder best practice for kodestandarder i forhold til de anvendte teknologier

**Status:** 🔴 Nej

**Kategori:** formkrav

**Retningslinjer:**

Beskriv hvilke kodestandarder projektet følger. Evt. med links til eksterne guides og supplerende retningslinjer.

**Dokumentation:**

Der foreligger ikke projektspecifik dokumentation for OS2sofd vedrørende kodestandarder og udviklingsprincipper. Leverandøren anvender interne retningslinjer og procedurer for blandt andet sikker udvikling, logning, datamodellering, caching, kryptografi, nøglehåndtering og persondatabeskyttelse, men disse er ikke dokumenteret som en del af projektets offentlige dokumentation.

Der er derfor ikke offentlig tilgængelig dokumentation, som opfylder kravet om dokumenterede kodestandarder og best practices for de anvendte teknologier.


---

## F17 - Drifts og vedligeholdelses setup er beskrevet

**Status:** 🟢 Ja

**Kategori:** formkrav

**Retningslinjer:**

Redegør for driftspartner(e), ansvar og finansiering. Hvem drifter, hvem vedligeholder og hvem koordinerer.

**Dokumentation:**

Driftspartner: Digital Identity
Drift, vedligeholdelse og videreudvikling af OS2sofd er organiseret gennem OS2-governance og de tilhørende tilslutningsaftaler.

OS2 varetager governance, koordinering af udviklingsforslag, fælles leverandørstyring samt koordinering af vedligeholdelse og videreudvikling af løsningen. OS2 indgår desuden leverandøraftaler vedrørende videreudvikling af produktet.

De enkelte anvenderkommuner er ansvarlige for lokale leverandøraftaler vedrørende drift og support af OS2sofd.

Finansieringen sker gennem en tilslutningsafgift samt et årligt vederlag fra de deltagende kommuner. Vederlaget dækker koordinering, vedligeholdelse og udvikling af løsningen.

Løsningen består af et centralt webbaseret kernesystem med tilhørende integrationsagenter og moduler, herunder integrationer til AD, Exchange, OPUS og øvrige fagsystemer.

---

## F18 - Rammearkitekturen og standarder er fulgt og afvigelser er forklaret

**Status:** 🟢 Ja

**Kategori:** formkrav

**Retningslinjer:**

Beskriv om/hvordan løsningen følger fællesoffentlig rammearkitektur – eller forklar hvorfor ikke.

**Dokumentation:**

OS2sofd er designet som bindeled mellem kommunens lokale infrastruktur og fælleskommunale/fællesoffentlige infrastrukturer og understøtter centrale principper i den fælleskommunale rammearkitektur. Løsningen bidrager til sammenhængende dataanvendelse på tværs af systemer, genbrug af data, tværgående automatisering og integration med fællesoffentlige infrastrukturer, herunder FK Organisation.

Løsningen understøtter særligt arkitekturprincipperne om fælles styring, sammenhæng og innovation, tværgående procesunderstøttelse, deling og genbrug af data samt effektivt samarbejde mellem it-løsninger.


---

## F19 - Løsningen er leveret i et containerformat f.eks. docker (anbefaling)

**Status:** 🟢 Ja

**Kategori:** formkrav

**Retningslinjer:**

Angiv om løsningen tilbydes i en containeriseret version som definerer hvordan applikationen bygges og køres.

**Dokumentation:**

De centrale OS2sofd-komponenter, som driftes hos leverandøren, bygges og deployeres i Docker-containere. De komponenter, som installeres lokalt hos kommunerne, leveres som Windows Services, hvilket følger best practice for den understøttede afviklingsplatform.

Løsningen understøtter således containeriseret drift af de centralt driftede komponenter, mens lokale integrationskomponenter deployeres efter de anbefalede principper for Windows Server-miljøer.


---

## F20 - Uddannelsesmateriale er udarbejdet (anbefaling)

**Status:** 🟢 Ja

**Kategori:** formkrav

**Retningslinjer:**

Henvis til manual, brugervejledning eller andet brugerrelateret materiale.

**Dokumentation:**

Der er udarbejdet omfattende bruger- og uddannelsesmateriale for OS2sofd, herunder brugermanual, produktbeskrivelser, procesbeskrivelser, implementeringsvejledninger og præsentationsmateriale. Materialet er tilgængeligt via projektets dokumentationssite samt i GitHub-repositoriets dokumentationsmappe og understøtter både administratorer, projektledere og øvrige brugere i anvendelse og implementering af løsningen.

Henvisninger:

https://www.sofd.io/documentation.html
GitHub repository → /doc
SOFD Core - Brugermanual
SOFD Core - Produktbeskrivelse
SOFD Core - IdM processer - overblik

---

## F21 - Politisk kommunikation er udarbejdet (Lokal + Omverden)

**Status:** ⚪ Ikke relevant

**Kategori:** formkrav

**Retningslinjer:**

Angiv indhold der kan bruges i politiske fora – f.eks. beslutningsoplæg eller pressemeddelelse.

**Dokumentation:**



---

## F22 - Procesplan + procesansvar for driftsimplementering er udarbejdet

**Status:** ⚪ Ikke relevant

**Kategori:** formkrav

**Retningslinjer:**

Tilføj en implementeringsplan med ‘hvem gør hvad hvornår’.

**Dokumentation:**



---

## S1 - Produktet har en kobling til OS2's strategi

**Status:** 🟢 Ja

**Kategori:** strategisk

**Retningslinjer:**

Beskriv hvordan produktet understøtter tværoffentlige behov, deling og fællesskab.

**Dokumentation:**

OS2sofd understøtter tværkommunal deling og genbrug af løsninger ved at tilbyde en fælles open source-platform til håndtering af organisationsdata og identitetsstyring. Løsningen anvendes af mere end 50 kommuner og understøttes af et aktivt community med løbende erfaringsudveksling, fælles prioritering og fælles udvikling.

Der afholdes to årlige ERFA-arrangementer, og løsningen bidrager til fællesoffentlig sammenhæng ved at fungere som bindeled mellem lokale systemer og fælleskommunale infrastrukturer som FK Organisation.


---

## S2 - Løsningen understøtter innovation og open source

**Status:** 🟢 Ja

**Kategori:** strategisk

**Retningslinjer:**

Angiv hvordan open source-værdier og nyskabelse er tænkt ind.

**Dokumentation:**

OS2sofd udvikles og distribueres som open source-software under MPL 2.0-licensen. Kildekoden er tilgængelig i OS2's GitHub-repository, og løsningen videreudvikles i samarbejde mellem kommuner og leverandør.

Den fælles udviklingsmodel gør det muligt for kommunerne at genbruge funktionalitet, dele erfaringer og bidrage til videreudvikling af løsningen. Nye behov og forbedringer identificeres og prioriteres gennem det fælles community, hvilket understøtter innovation og fælles værdiskabelse.


---

## S3 - Produktets (forventlige) kobling til OS2's mission, vision og strategi er beskrevet

**Status:** 🟢 Ja

**Kategori:** strategisk

**Retningslinjer:**

Angiv hvor produktet matcher med OS2's formål og indsatser.

**Dokumentation:**

OS2sofd understøtter OS2's mission om at skabe værdi gennem fællesoffentlige open source-løsninger. Produktet er kommuneejet, anvendes bredt på tværs af kommuner og videreudvikles gennem et fælles samarbejde mellem kommuner, leverandør og OS2-fællesskabet.

Løsningen bidrager til digital sammenhængskraft ved at standardisere og dele organisationsdata på tværs af systemer og understøtter dermed OS2's strategiske fokus på fællesskab, genbrug, deling og fælles udvikling.


---

## S4 - Der er udarbejdet en vision og strategi for produktet

**Status:** 🟢 Ja

**Kategori:** strategisk

**Retningslinjer:**

Beskriv produktvision og strategiske mål.

**Dokumentation:**

OS2sofd er designet til at være kommunens fælles platform for organisations- og medarbejderdata med princippet om "mange kilder – én sandhed". Løsningen samler, kvalitetssikrer, beriger og distribuerer organisationsdata på tværs af kommunens systemlandskab og understøtter automatiserede identitets- og adgangsstyringsprocesser. Produktet er samtidig designet som integrationsplatform mellem lokale systemer og fælleskommunale/fællesoffentlige løsninger som FK Organisation, OS2rollekatalog og øvrige fælles infrastrukturer. Produktbeskrivelsen beskriver både de bærende arkitekturprincipper og den langsigtede rolle som fælles datagrundlag for kommunens organisations- og identitetsdata

---

## S5 - Produktets kobling til og overensstemmelse med OS2's vision og strategi er tilstede og beskrevet

**Status:** ⚪ Ikke relevant

**Kategori:** strategisk

**Retningslinjer:**

Forklar hvordan løsningen passer ind i OS2’s overordnede værdisæt og visioner.

**Dokumentation:**



---

## G1 - Produktet er oprettet i OS2's porteføljestyring

**Status:** 🟢 Ja

**Kategori:** governance

**Retningslinjer:**

Produktet er oprettet på OS2s hjemmeside og indgår i årshjul.

**Dokumentation:**

OS2sofd er et etableret OS2-produkt med egen produktside på OS2's hjemmeside og indgår i OS2-porteføljen. Produktet har officiel OS2-governance, community og tilknyttede aktiviteter.

---

## G2 - Der koordineres løbende med OS2-sekretariatet

**Status:** 🟢 Ja

**Kategori:** governance

**Retningslinjer:**

Bekræft, evt. med årshjul/datoer/mails for koordinering.

**Dokumentation:**

Der gennemføres løbende koordinering mellem produktets governance, leverandør og OS2-sekretariatet i forbindelse med communityaktiviteter, roadmap, produktstatus og governance. Produktet indgår i OS2's produktportefølje og følger den etablerede OS2-governancemodel.

---

## G3 - Der er udpeget en projektleder/tovholder

**Status:** 🟢 Ja

**Kategori:** governance

**Retningslinjer:**

Navngiv og beskriv rolle og opgaver.

**Dokumentation:**

Produktkoordinator: Erling Haunstrup Poulsen, Syddjurs Kommune
Community manager: Ane Bundgaard Andreasen 
Koordineringen varetages gennem produktets governance-struktur med ansvar for community, roadmap, releaseplanlægning og koordinering mellem kommuner, leverandør og OS2.

---

## G4 - Bestyrelsen er orienteret

**Status:** 🟢 Ja

**Kategori:** governance

**Retningslinjer:**

Vedlæg dokumentation for orientering.

**Dokumentation:**

OS2sofd har gennem flere år været en del af OS2-porteføljen og har løbende været behandlet i OS2's governance-struktur. Bestyrelsen er orienteret gennem produktets optagelse, statusrapportering og efterfølgende governance-aktiviteter.

---

## G5 - Bestyrelsen har godkendt produktet

**Status:** 🟢 Ja

**Kategori:** governance

**Retningslinjer:**

Vedlæg dokumentation for godkendelse.

**Dokumentation:**

OS2sofd er et etableret OS2-produkt og må derfor anses for at være godkendt gennem OS2's formelle governance- og porteføljestyringsproces. Produktet er optaget i OS2-porteføljen og drives under OS2's governance-model.

---

## G6 - Der er nedsat en styregruppe

**Status:** 🟢 Ja

**Kategori:** governance

**Retningslinjer:**

Beskrivelse af styregruppen og roller/ansvar/opgaver.

**Dokumentation:**

Der er etableret en styregruppe omkring OS2sofd med deltagelse fra anvenderkommuner. Styregruppen prioriterer udvikling, roadmap og økonomi samt understøtter den strategiske udvikling af produktet.


---

## G7 - Der er nedsat en koordinationsgruppe (anbefaling)

**Status:** 🟢 Ja

**Kategori:** governance

**Retningslinjer:**

Beskrivelse af koordinationsgruppen og roller/ansvar/opgaver.

**Dokumentation:**

Der er etableret en koordinationsgruppe/community omkring OS2sofd, som løbende behandler ændringsønsker, prioriterer udviklingsopgaver og koordinerer samarbejdet mellem kommuner og leverandør. Der afholdes desuden to årlige ERFA-arrangementer med bred deltagelse fra anvenderkommunerne

---

## G8 - En projektmodel anvendes og er dokumenteret (anbefaling)

**Status:** 🟢 Ja

**Kategori:** governance

**Retningslinjer:**

Beskiv den anvendte projektmodel eller metode.

**Dokumentation:**

Udviklingen af OS2sofd følger en struktureret governance- og releaseproces med registrering og prioritering af ændringsønsker, koordinering i communityet samt planlagte releases. Ændringsønsker håndteres via GitHub Projects og indgår i en formaliseret proces fra idé til implementering og release.
https://github.com/orgs/OS2sofd/projects/1/views/1

---

## G9 - Review af kode foretages af tredjepart (anbefaling)

**Status:** 🔴 Nej

**Kategori:** governance

**Retningslinjer:**

Angiv hvilken ekstern part som udfører eller har udført review.

**Dokumentation:**



---

## G10 - Der er udarbejdet en tilslutningserklæring til sikring af økonomi (anbefaling)

**Status:** 🟢 Ja

**Kategori:** governance

**Retningslinjer:**

Vedlæg eller henvis til dokument for tilslutning og økonomi.

**Dokumentation:**

Der foreligger en tilslutningsaftale for OS2sofd, som beskriver deltagelse i fællesskabet samt de økonomiske forpligtelser for de deltagende kommuner. Aftalen indeholder bestemmelser om tilslutningsafgift og årligt vederlag til finansiering af koordinering, vedligeholdelse og videreudvikling af løsningen. Tilslutningsaftalen bidrager dermed til at sikre det økonomiske grundlag for den fortsatte drift og udvikling af produktet.
https://boks.os2.eu/s/Di5cTQdSABd6ak4?dir=/Produkter/OS2sofd%20-%20Offentlig/Tilslutning%20og%20takstblad&editing=false&openfile=true
https://boks.os2.eu/s/Di5cTQdSABd6ak4?dir=/Produkter/OS2sofd%20-%20Offentlig/Tilslutning%20og%20takstblad&editing=false&openfile=true

---

## G11 - Bestyrelsen har godkendt styregruppen

**Status:** ⚪ Ikke relevant

**Kategori:** governance

**Retningslinjer:**

Vedlæg dokumentation for beslutning.

**Dokumentation:**



---

## G12 - Bestyrelsen er repræsenteret i styregruppen

**Status:** ⚪ Ikke relevant

**Kategori:** governance

**Retningslinjer:**

Angiv hvilket medlem som deltager på vegne af bestyrelsen.

**Dokumentation:**



---

## G13 - Der foreligger en aftale der sikrer økonomi til koordinering og videreudvikling

**Status:** ⚪ Ikke relevant

**Kategori:** governance

**Retningslinjer:**

Vedlæg eller beskriv finansieringsaftalen.

**Dokumentation:**



---

## G14 - Der er etableret et fagligt fællesskab bag løsningen hvor erfaringer kan udveksles

**Status:** ⚪ Ikke relevant

**Kategori:** governance

**Retningslinjer:**

Henvis til brugerforum og/eller årshjul for aktiviteter.

**Dokumentation:**


