# Digitālās pārvaldības pašnovērtējums uzņēmuma vadītājam

> Šis projekts vērtē pārvaldības pierādījumus un lēmumu gatavību. Tas nav oficiāls EDIH/EK novērtējums, juridisks atzinums, audits vai sertifikācija.

## Atbilžu stāvokļi

- `UNKNOWN` — Nezināms / nav pierādījumu
- `CLAIMED` — Apgalvots
- `DOCUMENTED` — Dokumentēts
- `IMPLEMENTED` — Ieviests
- `VERIFIED` — Verificēts
- `NOT_APPLICABLE` — Nav attiecināms

## Novērtējums

### Stratēģija un vērtība

#### E01

Kritiskie pakalpojumi, digitālās atkarības un pieļaujamais pārtraukuma laiks ir skaidri definēti.

**Ieteiktā darbība:** Kartē kritiskos pakalpojumus, to digitālās atkarības un maksimāli pieļaujamo pārtraukumu.

**Avoti:** `open_dmat`, `nist_csf20`

#### E02

Digitālās investīcijas ir sasaistītas ar izmērāmiem biznesa rezultātiem un skaidriem riskiem.

**Ieteiktā darbība:** Katram būtiskam ieguldījumam nosaki sagaidāmos rezultātus, riskus un atbildīgo īpašnieku.

**Avoti:** `open_dmat`

#### E03

Pastāv mērķa digitālās attīstības ceļa karte ar īpašniekiem, atkarībām un pārskatīšanas datumiem.

**Ieteiktā darbība:** Izveido datētu ceļa karti, sasaistot nepilnības ar īpašniekiem un atskaites punktiem.

**Avoti:** `open_dmat`

#### E04

Pēc būtiskām digitālām izmaiņām tiek pārskatīti gan ieguvumi, gan riski, ne tikai pirms apstiprināšanas.

**Ieteiktā darbība:** Ievies pēcieviiešanas pārskatu ar ieguvumu pierādījumiem, atteices scenārijiem un atlikušā riska novērtējumu.

**Avoti:** `open_dmat`, `nist_csf20`

### Atbildība un lēmumu tiesības

#### E05

Lēmumu tiesības tehnoloģiju, datu, MI un kiberdrošības jautājumos ir dokumentētas.

**Ieteiktā darbība:** Dokumentē, kurš drīkst lemt, apstiprināt, pieņemt risku un apturēt izmaiņas.

**Avoti:** `nist_csf20`, `nis2`

#### E06

Kritiskām sistēmām un kritiskiem datiem ir nosaukti atbildīgie īpašnieki.

**Ieteiktā darbība:** Piešķir atbildīgos īpašniekus, ietverot dzīves cikla pienākumus.

**Avoti:** `nist_csf20`

#### E07

Ir definēti vadības eskalācijas sliekšņi kiberincidentiem, darbības pārtraukumiem un būtiskām datu kļūmēm.

**Ieteiktā darbība:** Definē objektīvus nosacījumus vadības informēšanai un lēmumiem.

**Avoti:** `nist_csf20`, `nis2`

#### E08

Vadība saņem pierādījumos balstītus digitālā riska pārskatus, ne tikai aktivitāšu metriku.

**Ieteiktā darbība:** Ziņo par ekspozīciju, kontroļu darbību, incidentiem un neatrisinātām nepilnībām.

**Avoti:** `nist_csf20`

### Datu un MI pārvaldība

#### E09

Kritiskiem datiem ir īpašnieki, kvalitātes prasības un apstrādes noteikumi.

**Ieteiktā darbība:** Definē datu īpašniekus, minimālos kvalitātes kritērijus un apstrādes noteikumus.

**Avoti:** `open_dmat`, `nist_csf20`

#### E10

Būtisku lēmumu datos var izsekot izcelsmei un nozīmīgām transformācijām.

**Ieteiktā darbība:** Ievies izcelsmes uzskaiti datiem, kas izmantoti būtiskos lēmumos.

**Avoti:** `open_dmat`

#### E11

Organizācija uztur būtisku MI lietojumu uzskaiti un informāciju par to apstiprinātājiem.

**Ieteiktā darbība:** Izveido MI lietojumu reģistru ar mērķi, īpašnieku, datiem, piegādātāju, ietekmi un apstiprinājumu.

**Avoti:** `nist_ai_rmf`

#### E12

Būtiskiem MI atbalstītiem rezultātiem ir skaidras cilvēka pilnvaras un validācijas robežas.

**Ieteiktā darbība:** Definē, kuri MI atbalstīti rezultāti jāpārbauda un jāapstiprina cilvēkam.

**Avoti:** `nist_ai_rmf`

### Arhitektūra un piegādātāji

#### E13

Kritiskās trešo pušu, mākoņpakalpojumu un platformu atkarības ir uzskaitītas.

**Ieteiktā darbība:** Uzturi atkarību reģistru, sasaistot to ar kritiskajiem pakalpojumiem un datiem.

**Avoti:** `nist_csf20`, `nis2`

#### E14

Pirms stratēģisku platformu ieviešanas tiek izvērtēti koncentrācijas, pārnesamības un iziešanas riski.

**Ieteiktā darbība:** Stratēģiskiem piegādātājiem pieprasi iziešanas un pārnesamības plānu.

**Avoti:** `open_dmat`, `nist_csf20`

#### E15

Dzīves cikla beigu tehnoloģijas un būtisks tehniskais parāds ir redzams vadībai.

**Ieteiktā darbība:** Uzturi vadības līmeņa pārskatu par neatbalstītām tehnoloģijām un tehnisko parādu.

**Avoti:** `open_dmat`, `nist_csf20`

#### E16

Būtiskas arhitektūras izmaiņas tiek pārskatītas no drošības, noturības un savietojamības viedokļa.

**Ieteiktā darbība:** Ievies vieglu arhitektūras pārskata vārteju būtiskām izmaiņām.

**Avoti:** `nist_csf20`

### Noturība un apliecināšana

#### E17

Kritiskiem procesiem ir definētas darbības prasības degradētā režīmā.

**Ieteiktā darbība:** Definē, kam jāturpina darboties, kādā minimālā līmenī un cik ilgi.

**Avoti:** `nist_csf20`

#### E18

Atjaunošanas pierādījumi ietver pārbaudītu atjaunošanu, ne tikai rezerves kopiju esamību.

**Ieteiktā darbība:** Pieprasi periodiskus atjaunošanas testus un saglabā rezultātus.

**Avoti:** `nist_csf20`

#### E19

Mācības ietver vadības lēmumus, komunikāciju un starpfunkcionālās atkarības.

**Ieteiktā darbība:** Veic scenārijus, kas prasa vadības lēmumus un pārbauda piegādātājus un rezerves procesus.

**Avoti:** `nist_csf20`, `nis2`

#### E20

Būtisku kontroļu apgalvojumi periodiski tiek pamatoti ar neatkarīgiem vai reproducējamiem pierādījumiem.

**Ieteiktā darbība:** Izvēlies būtiskās kontroles un pieprasi pārbaudāmus pierādījumus, nevis tikai politiku formulējumus.

**Avoti:** `nist_csf20`

### Cilvēki un pienākumi

#### E21

Vadības un būtisko lomu digitālo kompetenču nepilnības tiek identificētas.

**Ieteiktā darbība:** Novērtē lomu specifiskās kompetenču nepilnības un piesaisti apmācību vai personāla darbības.

**Avoti:** `open_dmat`

#### E22

Piegādātāju pienākumi drošības, datu, nepārtrauktības un incidentu sadarbības jomā ir skaidri.

**Ieteiktā darbība:** Pārskati stratēģiskos līgumus, aptverot drošību, incidentus, atjaunošanu, datus un iziešanu.

**Avoti:** `nist_csf20`, `nis2`

#### E23

Būtiski juridiskie, regulatīvie un līgumiskie digitālie pienākumi ir sasaistīti ar īpašniekiem un kontrolēm.

**Ieteiktā darbība:** Izveido pienākumu–īpašnieku–kontroļu karti.

**Avoti:** `nist_csf20`, `nis2`

#### E24

Novērtējuma secinājumi un mācības tiek pārvērstas atbildīgās darbībās un atkārtoti novērtētas.

**Ieteiktā darbība:** Katru būtisku nepilnību sasaisti ar īpašnieku, termiņu, pierādījumu prasību un atkārtota novērtējuma datumu.

**Avoti:** `open_dmat`, `nist_csf20`
