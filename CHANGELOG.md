# Changelog — oudere versies

Versies vanaf 2026.08.1 staan in de toolkit zelf ("Wat is nieuw" → "Alle versies").

## v2026.07.21 · 20-07-2026

- Opgelost: de schrijfkast-grafiek op het startscherm kon hetzelfde weeknummer twee keer tonen als een week per ongeluk twee keer werd gearchiveerd (bijv. na het corrigeren en opnieuw versturen van een weekmail) — de grafiek dedupt nu op weeknummer, net als de grafiek op Werkvoorraad, en toont de meest recente waarde

## v2026.07.20 · 13-07-2026

- Ook het ⚠️ op het Team-tabblad volgt nu de ingestelde belastingmarge (zelfde criterium als de ranglijst en de rechterkeuzelijst) — elk scherm geeft daarmee hetzelfde oordeel over wie te hoog zit
- Overlappende afwezigheidsperiodes (bijv. een cursus die in een vakantie valt) telden dubbel, waardoor de beschikbaarheid — en dus het eerlijke aandeel in de verdeling — te laag uitviel; overlappende dagen tellen nu één keer

## v2026.07.19 · 13-07-2026

- Het ⚠-symbool in de rechterkeuzelijst volgt nu exact de ingestelde belastingmarge: het staat alleen bij rechters die in de ranglijst rood kleuren (boven de marge), en weegt daarbij ook afwezigheid mee — voorheen gebruikte de keuzelijst een eigen, afwijkende berekening
- De volgorde van de rechterkeuzelijst is nu identiek aan de ranglijst (meest achterlopend bovenaan, gewogen naar beschikbaarheid)

## v2026.07.18 · 13-07-2026

- Opgelost: een rechter met alleen kanton aangevinkt kon in de rechterkeuzelijst en het advies van de hándelsverdeling verschijnen (bovenaan, want nul handelspunten) — het advies gebruikt nu hetzelfde handel-filter als de ranglijst
- Nieuw: puntenspecificatie in de ranglijst — klap een rechter uit en zie boven de zakenlijst precies waar de punten vandaan komen (enkelvoudig / MK-voorzitter incl. bonus / MK-lid), mét waarschuwing als er zaken zijn met een ontbrekende of ongeldige zwaarte: die tellen elk maar 1 punt en verklaren vaak "veel zaken, weinig punten"
- Advies bij gelijke stand (bijv. nog geen zaken): de rechter met de meeste beschikbare eFTE wordt aanbevolen, niet meer de eerste uit de lijst
- De inhoud verspringt niet meer bij het wisselen van onderdeel: alle onderdelen gebruiken nu dezelfde uitlijnbreedte en de browser reserveert vaste ruimte voor de scrollbalk

## v2026.07.17 · 12-07-2026

- Nieuw: 🏛 Kanton-module (optioneel, standaard uit) — aparte werklastverdeling voor kantonzaken met een eigen puntenbalans naast handel. Aanzetten via Werklastverdeling → Instellingen; de keuze wordt per databestand bewaard, dus collega's met een eigen databestand merken er niets van
- Kantonzaken registreren met eigen zwaartes (eenvoudig / normaal / complex, gewichten instelbaar) en een gebied-schakelaar ⚖️ Handel | 🏛 Kanton op Verdelen en Inzicht
- Aardzaken (bijv. arbeidsrecht, huurrecht): instelbare categorieën met per rechter vinkjes wie ze mag doen — de keuzelijst en het advies tonen alleen bevoegde rechters
- Zittingspakketten (zoals de O&O-zitting): registreer wie de zitting had; die telt voor een instelbaar aantal punten mee in de kanton-balans. Pakket-types zelf toe te voegen
- Eigen kanton-ranglijst gewogen naar kanton-eFTE (effectieve FTE × kanton-percentage uit de personeelskaart), met uitklapbare zaken en zittingen per rechter
- Kantonzaak voor een handelsrechter (bijv. erfrecht, letselschade): vink "🏛 Afkomstig uit kanton" aan bij het registreren als handelszaak — telt mee in de handel-balans, met herkenbaar herkomstlabel
- Dashboard-widget "Handel & kanton per rechter": beide balansen naast elkaar in één oogopslag

## v2026.07.16 · 06-07-2026

- Verdelen: onder de rechterkeuze staat nu waaróm die rechter wordt aanbevolen (bijv. "loopt 3,2 pt achter op de evenredige verdeling") — de ranglijst erbij pakken hoeft niet meer
- Waarschuwing bij een openstaande verdeelweek: is een gestarte verdeling niet afgerond terwijl de kalenderweek al verder is, dan zie je dat op het startscherm én bovenaan Inzicht (geen melding als er simpelweg niets gestart is)
- Herinnering voor de uitstroomronde: is de laatste CSV-batch ruim 5 weken geleden, dan verschijnt een zacht hintje op het startscherm en Inzicht
- Ranglijst: zaken direct in de uitklaprij bewerken — ✏️ opent nu ter plekke zwaarte wijzigen en ✓ afsluiten (volledig bewerken kan nog steeds); de uitgeklapte rechters blijven bovendien openstaan na elke wijziging of registratie

## v2026.07.15 · 06-07-2026

- Zaken → Afsluiten: elke afsluiting wordt nu geregistreerd met datum — het nieuwe kader "Archiveermomenten" toont per datum hoeveel zaken zijn afgesloten en of dat via een CSV-batch of los gebeurde (handig bij maandelijkse uitstroomverwerking)

## v2026.07.14 · 05-07-2026

- Weekpost: het emoji-aanbod is flink uitgebreid — de "meer"-knop opent nu een scrollbare kiezer met ruim 700 emoji in elf categorieën (smileys, gebaren, harten, feest, dieren & natuur, eten & drinken, sport, reizen, kantoor, symbolen), vergelijkbaar met WhatsApp

## v2026.07.13 · 05-07-2026

- Weekpost: linkjes naar websites direct in de mail — selecteer tekst in een tekstveld, klik op de nieuwe 🔗-knop in het zijpaneel en vul het webadres in; in de preview en de verstuurde mail wordt dat een klikbaar linkje (achteraf plakken in het .eml-bestand is niet meer nodig)
- Weekpost: losse webadressen in de tekst (zoals www.rechtspraak.nl) worden automatisch klikbaar in de mail

## v2026.07.12 · 03-07-2026

- Rustiger eerste kennismaking, met het oog op delen met collega’s: het startscherm voor de bestandskeuze legt nu in gewone taal uit wat er gebeurt en zet "Nieuw databestand aanmaken" bovenaan als aanbevolen keuze bij eerste gebruik
- Bij een geheel verse start verschijnt de "Wat is er nieuw?"-popup niet meer (voor een nieuwe gebruiker is alles nieuw) en blijft het backup-bolletje uit zolang er nog niets te verliezen valt
- Het startscherm toont bij een lege toolkit alleen nog de welkomstroute — het raster met lege widgets verschijnt zodra er gegevens zijn
- Werklastverdeling → Inzicht: de invoer om met terugwerkende kracht een week toe te voegen staat nu achter een knopje "+ Eerdere week toevoegen" (die leek onbedoeld een verplicht formulier) en het voorbeeldweeknummer is nu het huidige weeknummer
- Kleine verduidelijkingen: navigatieknop heet nu Overzicht (zoals de paginatitel), "Heel team naar WV" heet voluit "Heel team naar werklastverdeling", de lege overleggen-pagina geeft voorbeelden van overlegtypen, en dubbele titel in de "Wat is er nieuw?"-popup verwijderd

## v2026.07.11 · 03-07-2026

- Twee nieuwe widgets op het startscherm: 🏖 Afwezigheden (wie is nu afwezig en wie de komende 4 weken — klik om naar Team te gaan) en ☑️ Taken — deadlines (open taken die verlopen zijn, vandaag aflopen of binnen 7 dagen — klik om naar de takenlijst te gaan)

## v2026.07.10 · 03-07-2026

- Zaken met een ontbrekende of ongeldige zwaarte zijn nu direct herkenbaar aan een geel "?"-label in de zakenlijsten — zulke zaken tellen wel mee in de punten maar ontbreken in de B/C/D-telling; met ✏️ stel je de zwaarte alsnog in
- Weeknummers worden nu overal gecontroleerd (1 t/m 53) — bij de weekpost krijg je een waarschuwing vóór het versturen, bij de werkvoorraad en de verdeelhistorie kan geen ongeldig weeknummer meer worden opgeslagen
- De backup-herinnering is instelbaar: bepaal zelf na hoeveel dagen het bolletje oranje (herinnering) en rood (dringend) wordt — instellen via het bestandsscherm (📁 in de navigatiebalk)
- Het dashboard op het startscherm kan nu worden afgedrukt of als PDF bewaard via de nieuwe knop 🖨 Afdrukken

## v2026.07.9 · 03-07-2026

- Datums kloppen nu ook ’s nachts: de toolkit gebruikte achter de schermen de wereldklok (UTC), waardoor vóór één à twee uur ’s nachts "vandaag" nog gisteren was — taken met een deadline van vandaag kleurden dan onterecht rood
- Gegevens uit oude reservekopieën laden weer zonder foutmelding: rechters uit een backup van vóór de vrijstellingen-functie lieten het teamoverzicht vastlopen
- Backup herstellen zet nu óók de gegevens van Overleggen & Taken terug (die bleven eerder onbedoeld buiten het herstel)
- Als de browseropslag vol raakt, crasht opslaan niet meer en wordt het gekoppelde bestand gewoon bijgewerkt; je krijgt daarvan eenmalig een melding
- Werklastverdeling: in het overzicht toont de kolom B / C / D nu een 0 in plaats van een streepje, consistent met de totaalregel
- Diverse kleine weergavefouten opgelost: geen "NaN" meer bij een ontbrekende FTE-waarde en geen "undefined" meer bij een neventaak waarvan de categorie is verwijderd
- Onderhoud: dubbele hulproutines (Excel-export, downloads, afdrukvensters, datumopmaak, HTML-beveiliging en filters) zijn samengevoegd tot één centrale versie per routine (geen zichtbare wijziging)

## v2026.07.8 · 02-07-2026

- Eigen pictogram (weegschaal) voor het browsertabblad en bladwijzers, in plaats van het standaard wereldbol-icoon

## v2026.07.7 · 01-07-2026

- Evenredige verdeling: knop "⬍ Alles uitklappen/inklappen" om in één keer alle rechters open of dicht te klappen
- Zaken → Actieve zaken: nieuwe knop "⬇ Exporteer zakenlijst" (Excel) met kenmerk, zwaarte, type, betrokken rechters, punten, datum en notitie
- De personeelskaart-popup en de "Wat is er nieuw?"-popup sluiten nu ook met de Escape-toets

## v2026.07.6 · 01-07-2026

- Getallen worden nu overal met een Nederlandse komma weergegeven (bijv. 1,5 en −0,10) in plaats van een punt — in de zaken, personeelskaart, snapshots en exports. De grafieken blijven correct getekend

## v2026.07.5 · 01-07-2026

- Ingebouwde handleiding (📖 Handleiding) volledig bijgewerkt naar de nieuwe indeling — Inzicht / Verdelen / Zaken / Team / Instellingen — inclusief uitleg over uitklappen per rechter, de klikbare personeelskaart, rolnummer-herkenning bij import en het onderscheid "al actief / in archief"
- Verouderde verwijzingen in meldingen bijgewerkt (Team i.p.v. Rechters, Afsluiten i.p.v. Archief)
- Inzicht toont nu een duidelijke uitleg zolang er nog te weinig gegevens zijn voor een evenredige verdeling, in plaats van een leeg scherm

## v2026.07.4 · 01-07-2026

- Overleggen (Rechters): het contextveld groeit nu automatisch mee met de hoeveelheid tekst — geen vaste hoogte of scrollbalkje meer
- Personeelskaart: de detailkaart van een rechter toont nu ook de context & open bespreekpunten uit Overleggen, met een knop "🗓 Openen in Overleggen" om er direct naartoe te springen

## v2026.07.3 · 01-07-2026

- Inzicht opgeschoond: de losse "teamtotaal"-kaart en de aparte "Verdeling per rechter"-tabel zijn weg — die informatie zit nu in de evenredige verdeling zelf (uitklappen per rechter). Snapshot opslaan, exporteren en afdrukken zijn verplaatst naar de snapshots-kaart; exporteren/afdrukken van de verdeling per rechter blijft gewoon werken
- Onderhoud: dode code opgeruimd en het live advies wordt nu ook bij het openen van Verdelen ververst

## v2026.07.2 · 01-07-2026

- Inzicht & Verdelen: klik in de "Evenredige verdeling" op een rechter om zijn/haar actieve zaken uit te klappen (gesorteerd op kenmerk, met rol en punten). Met het ✏️-knopje spring je direct naar die zaak in bewerkmodus — zwaarte aanpassen, omzetten naar MK of leden toevoegen

## v2026.07.1 · 01-07-2026

- Werklastverdeling opnieuw ingedeeld naar je werkstroom, met een nieuw startscherm. De tabbladen zijn nu: 📊 Inzicht (startscherm — de evenredige verdeling, de verdeling per rechter, het verloop per week en de snapshots/trend bij elkaar), ➕ Verdelen (de wekelijkse ritus met live advies), 📋 Zaken (actieve zaken, afsluiten/uitstroom en importeren/instroom bij elkaar), 👥 Team (rechters, eFTE en afwezigheid) en ⚙️ Instellingen
- De bulk-import staat niet meer weggestopt in Instellingen, maar logisch bij Zaken (samen met het afsluiten van zaken)
- Het advies "Evenredige verdeling" is nu zowel op het Inzicht-startscherm als tijdens het verdelen zichtbaar

## v2026.06.18 · 30-06-2026

- Import: de analyse maakt nu onderscheid tussen "al actief" en "in archief". Een zaak die al bestaat maar eerder is afgesloten wordt apart gemarkeerd, met de toelichting dat je hem onder Zaken → Archief terugvindt (en daar kunt heractiveren) — voorheen stond er alleen "al aanwezig", terwijl je de zaak niet bij de actieve zaken kon vinden
- Zaken afsluiten: het vergelijkingsresultaat splitst niet-afsluitbare kenmerken nu in "al gearchiveerd" (eerder afgesloten, geen actie nodig) en "onbekend" (helemaal niet gevonden), zodat duidelijk is waarom iets niet wordt afgesloten

## v2026.06.17 · 30-06-2026

- Personeelskaart: klik op de naam van een teamlid voor een overzichtelijke personeelskaart (alleen-lezen) met alle gegevens op één plek — omvang/FTE, rechtsgebied (handel/kanton), vrijstellingen, neventaken, aandachtsgebieden en de werklastverdeling — zonder meteen in het bewerkscherm te belanden (vanuit de kaart kun je alsnog op Bewerken klikken)
- Personeelskaart: de kolom "Vrijstellingen" toont nu compact de aftrek-cijfers (bijv. −0.10 · −0.40); de bijbehorende omschrijvingen vind je in de personeelskaart

## v2026.06.16 · 30-06-2026

- Personeelskaart: de rechtertabel toont nu per teamlid de geldende vrijstellingen (beweeg over de cel voor de FTE-aftrek per vrijstelling). De kolommen "Kanton FTE" en "WV punten" zijn uit dit overzicht gehaald voor een rustiger beeld — alle gegevens blijven wel in de Excel-export staan
- Taalcorrectie: foutieve meervouden hersteld ("zaaken" → "zaken", "teamliden" → "teamleden") op o.a. het scherm "Zaken afsluiten" en het aandachtsbalk-overzicht

## v2026.06.15 · 30-06-2026

- Werklastverdeling (Rechters): de onterechte ⚠️-markering bij álle rechters is opgelost — het teamgemiddelde telt nu alleen handelrechters mee, zodat niet-handelrechters het gemiddelde niet langer omlaag trekken
- Werklastverdeling: er wordt automatisch één snapshot per kalenderweek vastgelegd, zodat de trendgrafiek zich vanzelf vult (handmatig blijft ook mogelijk)
- Werklastverdeling (MK): ook de voorzitter kan op "Extern (geen teamlid)" worden gezet — handig als je zelf als lid meedraait in een meervoudige kamer van een ander team; alleen jouw eigen rol telt dan mee
- Werklastverdeling: actieve zaken zijn nu ook op kenmerk te sorteren (natuurlijke volgorde, 26-6 vóór 26-123)
- Import: het rolnummer (ná "HA ZA") wordt nu correct uit de zaaksysteem-export gevist, ook als de cel extra tekst bevat (intern nummer, plaats)
- Zaken afsluiten: je kunt nu de volledige uitstroom-CSV integraal plakken óf uploaden — de tool vist zelf de rolnummers eruit en archiveert de overeenkomsten in bulk
- Dashboard: "Spreiding rechters" gebruikt dezelfde (instelbare) kleuren als de werklastverdeling, en "Aanvoer per week" toont hele zaakaantallen i.p.v. decimalen

## v2026.06.14 · 27-06-2026

- Werklastverdeling (tab Rechters): de kolom "Eff. FTE" is nu gewogen naar beschikbaarheid — een rechter met een (toekomstige of gedeeltelijke) afwezigheidsperiode of uitroostering krijgt naar rato een lagere Eff. FTE, gelijk aan wat de evenredige verdeling al rekent
- Werkvoorraad: een week zonder instroom telt nu als 0 in het verloop — een verdeling afronden zonder zaken legt een 0-datapunt vast, en ontbrekende weken tussen twee afgeronde weken worden in de trendgrafiek als 0 ingevuld, zodat een week (of enkele weken) zonder aanvoer zichtbaar wordt als dip
- Werkvoorraad: in "Verdeling per week" kun je met terugwerkende kracht een week handmatig toevoegen of een bestaande week corrigeren (✏️)
- Dashboard: de grafiek "Aanvoer per week" kapt het laatste datapunt niet meer af aan de rechterkant

## v2026.06.13 · 23-06-2026

- Werklastverdeling: de evenredige verdeling houdt nu rekening met ingevoerde afwezigheidsperiodes. Een rechter die de komende periode (deels) afwezig is, krijgt naar rato alvast minder nieuwe zaken toebedeeld — ook als de afwezigheid pas in de toekomst begint. Wie de hele periode weg is, valt uit de verdeling; zonder afwezigheid verandert er niets
- Werklastverdeling: bij het bewerken van een actieve zaak werkt de rechter-keuzelijst nu hetzelfde als bij het verdelen van nieuwe zaken (alleen handelrechters, gesorteerd op achterstand). Een al toegewezen rechter blijft altijd zichtbaar

## v2026.06.12 · 23-06-2026

- Onderhoud: het laden en opslaan van je gegevens (bestand én browser-fallback) verloopt nu via één centrale routine, wat de kans op verschillen tussen beide opslagvormen verkleint (geen zichtbare wijziging; bestaande databestanden blijven gewoon werken)

## v2026.06.11 · 23-06-2026

- Alle meldingen en bevestigingen verschijnen nu in de huisstijl van de toolkit — geen losse browser-pop-ups meer. Bevestigingen voor verwijderen/herstellen gebruiken het vertrouwde dialoogvenster; korte meldingen verschijnen als toast onderin beeld

## v2026.06.10 · 23-06-2026

- Onderhoud: de puntentelling per rechter is samengebracht in één centrale berekening, zodat verdeling, ranglijst en overzicht altijd consistent blijven (geen zichtbare wijziging)

## v2026.06.9 · 23-06-2026

- Werkvoorraad: de grafiek "Verdeling per week" telt nu álle zaken die je tijdens een verdeling registreert, ook als hun datum in een andere kalenderweek valt — afgeronde weken verschijnen voortaan met het juiste totaal
- Werkvoorraad: een verdeling afronden zonder zaken voegt geen leeg nul-punt meer toe aan de grafiek (je krijgt een korte melding)
- Werklastverdeling: een afwezige rechter telt niet meer mee in het teamgemiddelde, waardoor de belastingindicatoren weer kloppen
- Werklastverdeling: het "onvolledig profiel"-symbool (⚠️) verschijnt alleen nog wanneer handel én kanton allebei niet zijn ingevuld — een bewuste kanton-rechter krijgt geen onterechte waarschuwing meer
- Bij opstart verschijnen de bestandskoppeling en de "Wat is er nieuw?"-melding niet meer tegelijk over elkaar heen
- Een verse start begint nu met een lege werklastverdeling (geen voorbeeld-rechters meer) — voeg teamleden toe via de Personeelskaart

## v2026.06.8 · 20-06-2026

- Overleggen & Taken: nieuw tabblad "Rechters" — houd per rechter (uit de Personeelskaart) een vrij contextveld en losse bespreekpunten met datum bij; punten af te vinken als besproken en in te klappen

## v2026.06.7 · 19-06-2026

- Werklastverdeling: een MK-zaak kan nu geregistreerd worden met alleen een voorzitter — leden zijn optioneel en kunnen later worden toegevoegd (de zaak krijgt dan het label "leden onvolledig")
- Personeelskaart: handel en kanton worden nu met vinkjes aangezet; het percentage verschijnt pas als je een vinkje zet (de FTE-splitsing blijft behouden)
- Personeelskaart: voor rechters zonder handel kun je aanvinken dat ze als lid kunnen deelnemen aan een meervoudige handelkamer — zij worden dan kiesbaar als MK-lid
- Werklastverdeling: de keuzelijst voor lid 1 en lid 2 toont nu alleen handelrechters (plus, onder een streep, plaatsvervangers/RIO's en MK-inzetbare kantonrechters)

## v2026.06.6 · 14-06-2026

- Werkvoorraad: schrijfkasthistorie toont per week nog maar één datapunt — bij zowel een handmatig als een weekmail-entry voor dezelfde week wordt het handmatige datapunt gebruikt
- Bugfix: meervoud van "taak" in overleggen-accordion was "taaken" (fout) — nu "taken"

## v2026.06.5 · 02-06-2026

- Werklastverdeling: trendtabel per rechter in de Historie-tab (laatste 8 snapshots, rood/groen op basis van belastingsdrempel)
- Werklastverdeling: optionele notitie per zaak — zichtbaar in de zakenlijst en bewerkbaar
- Weekpost: sjablonen voor mededelingen — sla terugkerende tekst op en voeg in met één klik
- Weekpost archief: volledige mailinhoud bewaard; zoekbalk om door mededelingen en bijzonderheden te zoeken
- Overleggen & Taken: filter reset naar "Alles" bij wisselen van tab

## v2026.06.4 · 01-06-2026

- Taken: "↑ deadline" knop sorteert open taken op deadline (vroegste eerst, taken zonder deadline achteraan)

## v2026.06.3 · 01-06-2026

- Taken: optionele deadline — rood als verlopen, amber als vandaag
- Taken: 📋-knop kopieert open taken (gefilterd) naar klembord
- Bespreekpunten: na afvinken (○) springt focus automatisch naar het volgende punt; tooltip toont sneltoets

## v2026.06.2 · 01-06-2026

- Overleggen: Escape wist het bespreekpunt-invoerveld; druk N om direct naar het invoerveld van de eerste open accordion te springen
- Taken: ▲▼ knoppen en drag-and-drop (via ⠿-icoon) om taken te herordenen
- Taken: open-taken-teller op de navigatieknop
- Vergadering afsluiten-knop verwijderd

## v2026.06.1 · 01-06-2026

- Overleggen & Taken: klik op een bespreekpunt of taak om de tekst (en het overleg-label) inline te bewerken — Enter of klik buiten om op te slaan, Escape of ✕ om te annuleren
- Taken: het actieve filter bepaalt nu ook het label voor een nieuwe taak (filter op overlegtype → nieuwe taak krijgt dat label automatisch)
- Taken: Escape reset het actieve filter terug naar "Alles"

## v2026.05.5 · 30-05-2026

- Overleggen: accordion-layout — overlegtypen zijn inklapbaar; header toont badges met open punten en taken; nieuw overlegtype toevoegen via compact knopje rechtsboven
- Overleggen: open taken per overlegtype zichtbaar onder het uitklapbare item (naast de volledige Taken-tab)
- Werklastverdeling: rechters-dropdown bij verdelen gesorteerd op relatieve achterstand (meest achter bovenaan)
- Weekpost: lege rubrieken (Wel en wee, Vooruitblik weekend, Wist je dat, Mededelingen) worden weggelaten uit de verzonden mail
- Weekpost: na bevestigen "mail verstuurd" springt de tool automatisch terug naar het Invullen-tabblad

## v2026.05.4 · 28-05-2026

- Nieuwe module: Overleggen & Taken — bespreekpunten bijhouden per overlegtype, markeren als besproken, vergadering afsluiten met archief; gecombineerde takenlijst met optioneel label en filter

## v2026.05.3 · 27-05-2026

- Weeknummer toegevoegd rechtsbovenin naast de datum (zichtbaar in alle schermen)
- Bugfix: annuleerknop ontbrak bij zaakimport als er geen zaken herkend werden

## v2026.05.2 · 26-05-2026

- Data-veiligheid: schrijfslot in fileSave() voorkomt gelijktijdige schrijfacties (o.a. bij kleurpicker-drag)
- Data-veiligheid: bestand wordt nooit overschreven met lege data als er eerder data geladen was
- Data-veiligheid: na elke opslag wordt het bestand teruggelezen en gecontroleerd op geldig JSON
- Data-veiligheid: bestand wordt pas gereset nadat het volledig is ingelezen — bij een leesfout blijft huidige data bewaard
- Automatische dagelijkse backup in de browser (IndexedDB) — 7 dagen bewaard, herstelbaar via bestandsbeheer
- Waarschuwing bij meerdere geopende instanties van de toolkit
- Weekpost: knop "↩ Uit werkvoorraad" importeert schrijfkast-aantallen uit werkvoorraad-archief
- Handleiding: knop werkte niet — opgelost
- Evenredige verdeling: gebruikt nu de ingestelde kleuren (groen/oranje/rood) uit de instellingen

## v2026.05.1 · 22-05-2026

- Bugfix: import met ongeldige zwaarte (niet B/C/D) wordt nu expliciet rood gemarkeerd en overgeslagen i.p.v. stilletjes als B geïmporteerd
- Bugfix: "Oudste eerst" sortering plaatste zaken zonder datum bovenaan; nu staan ze onderaan (consistent met "Nieuwste eerst")
- Bugfix: zaaktelling per rechter telde zaken met ongeldige zwaarte als D; nu worden ze niet meegeteld
- Ranglijst toont nu hoeveel geïmporteerde zaken meetellen in de verdeling (met uitleg: niet in weekgrafiek)
- Rechters beschermd tegen verwijdering zolang er zaken in actief of archief aan hen gekoppeld zijn
- Foutmelding bij lege import bijgewerkt: noemt nu ook C/xx/xxxx-formaat naast HA ZA

## v2026.05 · 21-05-2026

- Gebruikshandleiding toegevoegd — te openen via 📖 Handleiding in de navigatiebalk
- CSV-import: herkent kolommen "zaaknummer" en "datum" automatisch; werkt direct met uitdraaien uit het zaaksysteem
- Import per rechter: upload een uitdraai per rechter om zaken direct te koppelen
- Bevestigingsmodals voor alle destructieve acties — geen native browser dialogs meer
- Outlook-flow: .eml opent direct; archiveren en doorrollen in één stap daarna
- Indiensttredingsdatum en FTE-ingangsdatum: evenredige verdeling corrigeert voor partiële periode en contractwijziging
- FTE-wijziging met ingangsdatum: "Was FTE" + "FTE geldig v/a" in PK, automatisch gesynchroniseerd naar WV
- Waarschuwingsbalk: afwezige rechters tellen niet mee in spreidingswaarschuwingen; 8-weken-melding verwijderd
- Bugfixes: prullenbak-bewaargrens, backup-download, snapshot-navigatie, verdeling-verlaten vanuit homescreen

## v2026.03 · 01-03-2026

- E→MK omzetten achteraf in actieve zakenlijst
- Plaatsvervangers & RIO's uitklapbaar in Personeelskaart met inzetstatistieken
- Handel-filter: alleen rechters met handel% in ranglijst en verdeling-selectors
- Belastingsdrempel met configureerbare kleurpickers per zone
- MK-voorzitter bonus configureerbaar in Instellingen
- Sticky tabs in alle views bij scrollen

## v2025.01 · 01-01-2025

- Weekpost: weekmail-generator met schrijfkast, Outlook-export en archief
- Werklastverdeling: zaakregistratie (B/C/D, E/MK) met evenredige verdeling
- Personeelskaart: centraal teamregister met synchronisatie naar WV
- Werkvoorraad: lijngrafieken voor schrijfkast en aanvoer per week
- Gebruikslog voor meting van toolgebruik (max. 5000 entries)
- Bestandsbeheer via File System Access API met automatische backup
