# Notater – barnehagekassa.no

---

## Hosting og finansiering

**Hosting**
- Bruk **Cloudflare Pages** (gratis, global CDN, skalerer uten kostnad)
- Domenet `.no` koster ~100–200 kr/år (f.eks. domeneshop.no eller one.com)
- Eneste reelle kostnad er domenet – kan selvfinansieres i starten

**Finansiering – konklusjon**
- Siden skal alltid være gratis for brukerne
- **Ikke ads** – for påtrengende, ødelegger det rene designet, og inntjeningen er uansett minimal med nisjetrafikk
- Foretrukket løsning: **Ko-fi**-knapp i footer (ko-fi.com)
  - Frivillig donasjon, ingen forpliktelse for brukerne
  - Usynlig i designet – en liten knapp i bunnen holder
  - Folk som bruker siden på jobb jevnlig er villige til å gi ~30–50 kr
  - Mer lønnsomt enn ads for en norsk nisjesite
- Alternativ ved vekst: ett enkelt sponsorpanel i footer fra relevant aktør (ikke display-ads)

**Om ads generelt (for referanse)**
- Google AdSense er standardløsningen
- Tjener penger per visning (CPM) eller per klikk (CPC)
- Minst påtrengende plassering: én statisk annonse i bunnen eller i sidemargen
- Unngå: pop-ups, auto-play video, annonser midt i innhold
- Inntjeningen skalerer med trafikk – ikke lønnsomt i liten skala

---

## Nyttige ressurser for barnehageansatte – kartlagt

*Sortert etter type. Verifisert mars 2026.*

---

### 📋 Maler og skjemaer

| Nettside | Hva de tilbyr | URL |
|---|---|---|
| **Malimo Idebank** | Aktivitetsark, maler, posters, begrepslæring, sesongaktiviteter – kategorisert for barnehage | https://idebank.malimo.no/barnehage/ |
| **Udir – Tiltaksplanmal** | Offisiell mal for skriftlig tiltaksplan (aktivitetsplikten) | https://www.udir.no/regelverk-og-tilsyn/barnehage/mal-for-tiltaksplan-barnehage/ |
| **Udir – Rammeplan** | Rammeplanen for barnehagen – fulltekst og veiledere | https://www.udir.no/laring-og-trivsel/rammeplan/ |

---

### 🧠 Spesialpedagogikk

| Nettside | Hva de tilbyr | URL |
|---|---|---|
| **Statped** | Faglig støtte ved språkvansker, ASK, syn/hørsel – ressurser til barnehage og skole | https://www.statped.no |
| **Udir – Barnehage (spesialpedagogikk)** | Oversikt over spesialpedagogisk hjelp og tilrettelegging i barnehagen | https://www.udir.no/barnehage/ |
| **Snakk med barn** | Samtaletrening med avatar-simulator for ansatte – vold, overgrep og vanskelige temaer | https://www.snakkemedbarn.no |
| **Jeg vet** | Gratis læringsopplegg (Redd Barna/Salaby) om kropp, grenser, følelser, rettigheter | https://www.jegvet.no |
| **NAFO** | Ressurser for flerspråklige barn – kartlegging, kompetanseheving, morsmålsstøtte | https://nafo.oslomet.no |

---

### 🎨 Kreativt og aktiviteter

| Nettside | Hva de tilbyr | URL |
|---|---|---|
| **Supercoloring.com** | 100 000+ gratis fargeleggingsark – dyr, eventyr, natur, mat, transport m.m. | https://www.supercoloring.com |
| **Coloringpages.net** | Gratis fargeleggingsark sortert på tema | https://www.coloringpages.net |
| **Barnehageforum** | Lekedatabase, aktivitetsideer, refleksjonsopplegg, temabaserte moduler | https://www.barnehageforum.no |
| **Malimo Idebank** | Kreative prosjekter, håndverk, estetiske aktiviteter tilpasset barnehagealder | https://idebank.malimo.no/barnehage/ |
| **Grønt Flagg** | Miljøpedagogikk – prosjektbasert arbeid med natur, bærekraft og gjenbruk | https://grontflagg.fee.no |
| **Hama** | Offisielle perlemønstre og inspirasjon | https://www.hama.dk |

---

### 🌐 Nettressurser og fagstoff

| Nettside | Hva de tilbyr | URL |
|---|---|---|
| **Barnehage.no** | Nyheter, debatt og fagartikler fra barnehage-Norge | https://www.barnehage.no |
| **Barnehageforum** | Fagartikler, verktøy, veiledere og nyheter for barnehageansatte (2000+ barnehager) | https://www.barnehageforum.no |
| **Utdanningsnytt** | Faglig fordypning og debatt – utgis av Utdanningsforbundet | https://www.utdanningsnytt.no |
| **Udir – Barnehage** | Alt av regelverk, rammeplan, veiledere og støttemateriell | https://www.udir.no/barnehage/ |
| **Redd Barna – Skole og barnehage** | Gratis undervisningsmateriell om barns rettigheter og trygghet | https://www.reddbarna.no/skole-og-barnehage/ |

---

### ❤️ Helse, trivsel og barnevern

| Nettside | Hva de tilbyr | URL |
|---|---|---|
| **Snakk med barn** | Gratis simulator for å øve på samtaler om vold og overgrep med barn | https://www.snakkemedbarn.no |
| **Jeg vet** | Læringsopplegg om trygghet, kropp og grenser – laget for barnehage/skole | https://www.jegvet.no |
| **Bufdir** | Fagstøtte til barnevern, oppvekst og familievern | https://www.bufdir.no |

---

## Lenker som er bekreftet å ikke fungere (fjernet fra siden)

- aktivitetsark.no – ECONNREFUSED (nede/stengt)
- logopedforeningen.no – ECONNREFUSED (nede)
- bufdir.no/Familie/nedsatt_funksjonsevne/Tidlig_innsats/ – 404 (siden er flyttet)
- udir.no/laring-og-trivsel/spesialundervisning/ (alle underlenker) – 404 (Udir har restrukturert URL-er)

---

## GitHub-push regler (viktig – unngå overskriving)

**index.html skal ALLTID hentes fra GitHub før endringer gjøres.**
Den lokale filen kan ligge bak GitHub-versjonen og overskrive kritiske funksjoner
(sticky filter-bar, søk, kortoversikt).

Fremgangsmåte når index.html skal oppdateres:
1. Hent gjeldende versjon fra GitHub via API (`GET /repos/mappypants/barnehagekassa/contents/index.html`)
2. Dekode og gjør endringer på den hentede strengen
3. Push resultatet tilbake — aldri bruk lokal fil som utgangspunkt

**Versjonsnummer ved push:**
1. Hent `VERSION`-fila fra GitHub, les nummeret (f.eks. `0.9`)
2. Øk patch-nummeret (`0.9` → `0.10`, `0.10` → `0.11` osv.)
3. Erstatt gammelt versjonsnummer med nytt i alle endrede HTML-filer:
   søk etter `<span style="opacity:0.45">vX.X</span>` og bytt til nytt nummer
4. Push `VERSION`-fila sammen med de andre filene

---

## Stilregler (aldri bryt disse)

- **Ingen emojis** – noensinne. Ikke i tekst, ikke i knapper, ikke som ikoner. Bruk SVG-ikoner eller ren tekst.
- **Ingen hyphens som skilletegn** i løpende tekst eller overskrifter. Omskriv heller setningen. Sammensatte ord på norsk (f.eks. "periodeplan-mal") er OK grammatisk, men unngå hyphens som tankestrek eller separator.
- **Rent, moderne design** – minimal visuell støy, romslig whitespace, subtile skygger.
