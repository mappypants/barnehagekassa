# Ideer for barnehagekassa.no
_Notat laget 21. mars 2026 — sist oppdatert 23. mars 2026_

---

## 🛠️ Nye interaktive verktøy

- **Observasjonsskjema-bygger** — fyll inn barnets navn, dato, situasjon → ferdig formatert, utskriftsvennlig observasjonsskjema
- **Sesongkalender for aktiviteter** — «hva kan vi gjøre i mars?» med ideer knyttet til årstid, høytider og rammeplan-tema
- **Foreldresamtale-guide** — interaktiv sjekkliste / struktur for utviklingssamtaler

---

## 📄 Nye maler (utskriftsvennlige)

- **Dagsrapport-mal** — mat, søvn, humør, aktivitet. Enkel å fylle ut, pen å skrive ut
- **Månedsplan-bygger** — som periodeplan men med kalenderoversikt for hele måneden
- **Foreldresamtale-skjema** — ferdig strukturert skjema med punktliste til utviklingssamtaler

---

## 🎨 Design og brukeropplevelse

- ✅ **Søk/filter på forsiden** — søkeboks finnes og er utvidet: kortene søkes nå på utvidede nøkkelord fra undersider (f.eks. TRAS, ASK, autisme, PPT). Kortene er også sortert alfabetisk innen hver kategori.
- **Bedre footer** — strukturert med kategorier: Verktøy / Maler / Ressurser / Om
- **Hover-effekter på kort** — subtile 150–200ms animasjoner for mer polert følelse
- **Ytelse: bytt ut base64-logoen** — logoen er ~330K tegn innbakt i hver HTML-fil; ekstern bildefil ville gjort sidene mye raskere å laste

---

## 🎨 Kreativt arbeid (mer innhold)

- Årstidsbaserte formingsideer (hva lager vi høst/vinter/vår/sommer?)
- Enkle oppskrifter: salt deig, fingermalingsmaling, papirmassé
- Steg-for-steg tegneøvelser for barn

---

## 🔧 Allerede gjort

- ✅ Fikset 404: `maler.html`-lenker i barnevern.html og fagprat-hjulet.html peker nå til `kreativt-arbeid.html` _(21. mars)_
- ✅ Barnevern: skilt tydelig mellom **meldeplikt** (melde på eget initiativ) og **opplysningsplikt** (svare når barnevernet ber om det) på barnevern.html og i alle filer som refererte til dette _(23. mars)_
- ✅ Fikset 404 på TRAS og ASK under spesialpedagogikk: Statped la om URL-strukturen; TRAS peker nå til `tras.infovestforlag.no`, ASK til ny statped.no-adresse _(23. mars)_
- ✅ Søk forbedret: Spesialpedagogikk-kortet søker nå på TRAS, ASK, autisme, IOP, PPT, Statped m.m. _(23. mars)_
- ✅ Alfabetisk sortering av kort innen alle kategorier på forsiden _(23. mars)_
