# Ideer for barnehagekassa.no
_Notat laget 21. mars 2026 — sist oppdatert 23. mars 2026_

---

## 🛠️ Nye interaktive verktøy

- ✅ **Observasjonsskjema-bygger** — fyll inn barnets navn, dato, situasjon → ferdig formatert, utskriftsvennlig observasjonsskjema _(23. mars)_
- **Sesongkalender for aktiviteter** — «hva kan vi gjøre i mars?» med ideer knyttet til årstid, høytider og rammeplan-tema
- **Foreldresamtale-guide** — interaktiv sjekkliste / struktur for utviklingssamtaler

### Nye ideer fra dypdykk (23. mars)

**Daglig praksis og dokumentasjon**
- **Dagsrapportbygger** — fyll inn dato, gruppe og barnenavn, velg fra kategorier for mat/søvn/humør/aktivitet, skriv ut ferdig ark
- **Avviksskjema** — for uhell og hendelser (jf. §18 barnehageloven), noe alle barnehager er pliktige å ha men ingen enkel gratis løsning finnes
- **Allergioversikt-bygger** — registrer barna og allergiene deres, skriv ut laminert A4 til kjøkkenet

**Pedagogisk planlegging**
- **Progresjonstracker** — knytt observasjoner til rammeplanen fagområder (kommunikasjon og språk, kropp og bevegelse, natur og miljø osv.) for hvert barn
- **Refleksjonsrunde-verktøy** — velg refleksjonsmodell (LØFT, styrkebasert, or-og-bords-runden) og få en strukturert guide til personalmøtet
- **Sesongkalender** — se over (høy prioritet, mye etterspurt)

**Praktiske hverdagsverktøy**
- **Navnetrekkhjul** — legg inn barna på avdelingen, trekk tilfeldig hvem som er hjelpebarn, starter med sang osv. Enkelt og delbart i sosiale medier
- **Aktivitetstimer** — forhåndsinnstilte tider (3 min ryddetid, 5 min pause, 20 min frilek) med lydsignal
- **Turplanlegger og risikovurderingsskjema** — sjekkliste for utstyr, medisinbehov, sikkerhetsrutiner og ansvarsfordeling ved utflukter (pålagt, men ingen enkel digital løsning finnes)

---

## 📄 Nye maler (utskriftsvennlige)

- **Dagsrapport-mal** — mat, søvn, humør, aktivitet. Enkel å fylle ut, pen å skrive ut
- **Månedsplan-bygger** — som periodeplan men med kalenderoversikt for hele måneden
- ✅ **Foreldresamtale-skjema** — ferdig strukturert skjema med punktliste til utviklingssamtaler _(23. mars)_

---

## 🎨 Design og brukeropplevelse

- ✅ **Søk/filter på forsiden** — søkeboks finnes og er utvidet: kortene søkes nå på utvidede nøkkelord fra undersider (f.eks. TRAS, ASK, autisme, PPT). Kortene er også sortert alfabetisk innen hver kategori.
- ✅ **Bedre footer** — strukturert med kategorier: Verktøy / Maler / Ressurser / Om _(23. mars)_
- ✅ **Hover-effekter på kort** — subtile 150–200ms animasjoner for mer polert følelse _(23. mars)_
- **Ytelse: bytt ut base64-logoen** — logoen er ~330K tegn innbakt i hver HTML-fil; ekstern bildefil ville gjort sidene mye raskere å laste

---

## 🎨 Kreativt arbeid (mer innhold)

- Årstidsbaserte formingsideer (hva lager vi høst/vinter/vår/sommer?)
- Enkle oppskrifter: salt deig, fingermalingsmaling, papirmassé
- Steg-for-steg tegneøvelser for barn

---

## 🔗 Nye ressurskategorier å vurdere

- **Musikk og sang** — kobling til NRK Super-sanger, Alfabia (norsk sang og rim), akkordark for gitarspillende pedagoger
- **Mat og ernæring** — Helsedirektoratets veileder for mat i barnehagen, Matportalen, enkle oppskrifter
- **Overgang barnehage til skole** — Udirs veileder, samarbeidsskjemaer og sjekklister for overgangssamtalen (særlig relevant om våren)
- **Digital kompetanse for barn** — Lær Kidsa Koding og Kodeklubben har gratis opplegg tilpasset barnehagealder
- **HMS og trivsel for ansatte** — Arbeidstilsynets veileder for psykososialt arbeidsmiljø i barnehagen, fagforeningenes HMS-ressurser
- **Flerkulturell kompetanse** — utvide NAFO-lenker under spesialpedagogikk, ressurser for flerspråklige barn

---

## 🔧 Allerede gjort

- ✅ Fikset 404: `maler.html`-lenker i barnevern.html og fagprat-hjulet.html peker nå til `kreativt-arbeid.html` _(21. mars)_
- ✅ Barnevern: skilt tydelig mellom **meldeplikt** (melde på eget initiativ) og **opplysningsplikt** (svare når barnevernet ber om det) på barnevern.html og i alle filer som refererte til dette _(23. mars)_
- ✅ Fikset 404 på TRAS og ASK under spesialpedagogikk: Statped la om URL-strukturen; TRAS peker nå til `tras.infovestforlag.no`, ASK til ny statped.no-adresse _(23. mars)_
- ✅ Søk forbedret: Spesialpedagogikk-kortet søker nå på TRAS, ASK, autisme, IOP, PPT, Statped m.m. _(23. mars)_
- ✅ Alfabetisk sortering av kort innen alle kategorier på forsiden _(23. mars)_
- ✅ **Font på overskrifter byttet til Quicksand** — alle 27 HTML-filer oppdatert fra Plus Jakarta Sans til Quicksand 500 (medium) for å matche logoens vekt og stil _(23. mars)_
- ✅ **Logo konsistent på alle sider** — observasjon.html brukte gammelt logo-illustrasjon.png (laptop-logo); nå er alle sider samkjørt med barnehagekassa-logoen _(23. mars)_
