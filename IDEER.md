# Ideer for barnehagekassa.no
_Notat laget 21. mars 2026 — sist oppdatert 25. mars 2026 (automatisk analyse)_

---

## 🛠️ Nye interaktive verktøy

- ✅ **Observasjonsskjema-bygger** — støtter 6 metoder (løpende protokoll, praksisfortelling, sosiogram, tidssampling m.m.), utskriftsvennlig _(23. mars)_
- ✅ **Navnetrekkhjul** — legg inn navn, trykk spin, hjulet trekker hvem som er hjelpebarn eller starter sangen. Klar for TikTok/Reels _(laget)_
- ✅ **Avviksskjema** → laget som **Skademeldingsskjema** (skademelding.html) — dekker §18-plikten _(laget)_
- ✅ **Opptaksplanlegger** — drag-og-slipp-fordeling av barn og ansatte på avdelinger, fargekoder for alder/stilling, skriv ut ferdig oversikt _(laget, ikke i ideelisten opprinnelig)_

**Gjenstår:**
- ✅ **Sesongkalender for aktiviteter** — aktivitetsideer for alle 12 måneder, filtrerbar på kategori, knyttet til rammeplanen _(26. mars)_
- **Dagsrapportbygger** — fyll inn dato, gruppe og barnenavn, velg fra kategorier (mat/søvn/humør/aktivitet), skriv ut ferdig ark
- ✅ **Turplanlegger og risikovurderingsskjema** — sjekkliste for risiko, utstyr, medisin, ansvarsfordeling og varsling. Klar til utskrift _(26. mars)_
- **Allergioversikt-bygger** — registrer barna og allergiene, skriv ut laminert A4 til kjøkkenet
- **Aktivitetstimer** — forhåndsinnstilte tider (3 min ryddetid, 5 min pause, 20 min frilek) med lydsignal
- **Foreldresamtale-guide** — interaktiv sjekkliste/struktur for utviklingssamtaler
- **Progresjonstracker** — knytt observasjoner til rammeplanen fagområder per barn
- **Refleksjonsrunde-verktøy** — velg modell (LØFT, styrkebasert osv.), få strukturert guide til personalmøtet

---

## 📄 Nye maler (utskriftsvennlige)

- **Dagsrapport-mal** — mat, søvn, humør, aktivitet. Enkel å fylle ut, pen å skrive ut
- **Månedsplan-bygger** — som periodeplan men med kalenderoversikt for hele måneden
- ✅ **Foreldresamtale-skjema** — ferdig strukturert skjema med punktliste til utviklingssamtaler _(23. mars)_

---

## ⚠️ Teknisk gjeld

- ✅ ~~Bytt ut base64-logoen~~ — alle HTML-filer bruker nå `logo_cropped.png` som ekstern fil.
- **SEO: tittel-tags og meta-descriptions** — ikke konsistente på tvers av alle sider. Bør gjøres når siden har litt mer innhold og trafikk.
- ✅ ~~Ekvivalentkalkulator ikke pushet~~ — er deployet og ligger på forsiden.

---

## 🎨 Design og brukeropplevelse

- ✅ **Søk/filter på forsiden** — søkeboks finnes og er utvidet: kortene søkes nå på utvidede nøkkelord fra undersider (f.eks. TRAS, ASK, autisme, PPT). Kortene er også sortert alfabetisk innen hver kategori.
- ✅ **Bedre footer** — strukturert med kategorier: Verktøy / Maler / Ressurser / Om _(23. mars)_
- ✅ **Hover-effekter på kort** — subtile 150–200ms animasjoner for mer polert følelse _(23. mars)_
- _(se Teknisk gjeld over)_

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

## 📣 Markedsføring og outreach

- ✉️ Presentasjonsmail sendt til barnehage.no, barnehageforum.no og andre aktører mandag 23. mars kveld. Venter på svar — gi det til fredag 28. mars før evt. oppfølging.
- Full plan ligger i `marketing-strategi.md`: e-postmal, kontaktliste, Instagram/LinkedIn-opplegg via Buffer, kronikk-idé til barnehage.no.
- Prioritert rekkefølge for outreach: 1) barnehage.no (kronikk), 2) Facebook-grupper for barnehageansatte, 3) Utdanningsforbundet og Fagforbundet nyhetsbrev.

---

## 🔧 Allerede gjort

- ✅ Fikset 404: `maler.html`-lenker i barnevern.html og fagprat-hjulet.html peker nå til `kreativt-arbeid.html` _(21. mars)_
- ✅ Barnevern: skilt tydelig mellom **meldeplikt** (melde på eget initiativ) og **opplysningsplikt** (svare når barnevernet ber om det) på barnevern.html og i alle filer som refererte til dette _(23. mars)_
- ✅ Fikset 404 på TRAS og ASK under spesialpedagogikk: Statped la om URL-strukturen; TRAS peker nå til `tras.infovestforlag.no`, ASK til ny statped.no-adresse _(23. mars)_
- ✅ Søk forbedret: Spesialpedagogikk-kortet søker nå på TRAS, ASK, autisme, IOP, PPT, Statped m.m. _(23. mars)_
- ✅ Alfabetisk sortering av kort innen alle kategorier på forsiden _(23. mars)_
- ✅ **Font på overskrifter byttet til Quicksand** — alle 27 HTML-filer oppdatert fra Plus Jakarta Sans til Quicksand 500 (medium) for å matche logoens vekt og stil _(23. mars)_
- ✅ **Logo konsistent på alle sider** — observasjon.html brukte gammelt logo-illustrasjon.png (laptop-logo); nå er alle sider samkjørt med barnehagekassa-logoen _(23. mars)_
- ✅ **Ekvivalentkalkulator** — deployet og på forsiden _(23. mars)_
- ✅ **ASK-ressursside** (ask.html) — faglig side om Alternativ og supplerende kommunikasjon med lovgrunnlag, ressurser og veiledning _(laget)_
- ✅ **Opptaksplanlegger** (opptak.html) — drag-og-slipp fordeling av barn og ansatte _(laget)_
- ✅ **Fikset 404: maler.html** — peker nå til kreativt-arbeid.html i barnevern.html og fagprat-hjulet.html _(25. mars)_
