# Ukesrapport – barnehagekassa.no
**Uke 13 / 23.–27. mars 2026**

---

## Hva er gjort denne uka

Uka gikk fra v0.1 til v0.9 — en av de mest produktive ukene siden oppstart. 20+ commits, fire nye interaktive verktøy, en ny informasjonsside, og en rekke design- og UX-forbedringer.

### Nye verktøy og sider (23.–26. mars)
- **Observasjonsskjema-bygger** — 6 observasjonsmetoder (løpende protokoll, praksisfortelling, sosiogram m.m.), utskriftsvennlig
- **Navnetrekkhjulet** — legg inn barnenavn, trykk spin — god kandidat for TikTok/Reels
- **Opptaksplanlegger** — drag-og-slipp med ressursbarn-flagg, fargekoder, stillingsprosent, avdelingstype og bemanningsnorm
- **Skademeldingsskjema** — for barn og ansatte, fyll ut digitalt og lagre som PDF
- **Ekvivalentkalkulator** — deployet og på forsiden
- **ASK-ressursside** — faglig side om alternativ og supplerende kommunikasjon
- **Barnesykdommer-side** — 13 vanlige sykdommer med FHI-lenker og filter
- **Turplanlegger og risikovurderingsskjema** — sjekkliste for risiko, utstyr, medisin og ansvarsfordeling (v0.9, 26. mars)
- **Sesongkalender** — 84 aktiviteter for alle 12 måneder, filtrerbar på kategori, koblet til rammeplanen (v0.9, 26. mars)

### Nye maler
- Foreldresamtale-mal (.docx)

### Design og UX
- Font byttet til Quicksand på alle sider (matcher logoen)
- Logo konsistent på tvers av alle sider
- Footer strukturert med kategorier
- Hover-effekter på kort
- Sticky filter-bar på forsiden (sentrert, visuelt forbedret)
- Hero-knapper fjernet
- Kalkulatornavn forkortet

### Teknisk
- **Base64-logo fjernet** — alle HTML-filer bruker nå ekstern bildefil (ca. 330 000 tegn spart per fil)
- Søk utvidet med fagtermer (TRAS, ASK, autisme, IOP, PPT m.m.)
- Alfabetisk sortering av kort innen kategorier
- 404-fiks: TRAS og ASK peker til oppdaterte Statped-adresser
- Versjonsnummer i footer på alle sider, VERSION-fil opprettet

### Utadrettet arbeid
- Presentasjonsmail sendt mandag 23. mars til barnehage.no, barnehageforum.no og andre aktører

---

## E-post og tilbakemeldinger

**Ingen svar på outreach-mailen** — sendt mandag 23. mars kveld, fire virkedager uten respons. Fristen du satte var fredag 28. mars — det er i morgen. Da kan det vurderes om det er verdt en forsiktig oppfølging.

**Ingen nye tilbakemeldinger via Formspree** — de fire innsendingene fra 21. mars (dine egne test-innsendinger: «Sweeeet!», «Enda mer!» m.fl.) er fortsatt de eneste i innboksen.

---

## Status: ideer som gjenstår

**Gjenstår fra IDEER.md:**

- **Dagsrapportbygger** — fyll inn dato, gruppe, barnenavn, velg kategorier (mat/søvn/humør/aktivitet), skriv ut ferdig ark
- **Allergioversikt-bygger** — registrer barn og allergier, skriv ut laminert A4 til kjøkkenet
- **Aktivitetstimer** — forhåndsinnstilte tider med lydsignal
- **Foreldresamtale-guide** — interaktiv sjekkliste/struktur for utviklingssamtaler
- **Progresjonstracker** — knytt observasjoner til rammeplanen per barn
- **Refleksjonsrunde-verktøy** — velg modell (LØFT, styrkebasert osv.)
- **Dagsrapport-mal** — enkel utskriftsvennlig mal
- **Månedsplan-bygger** — kalenderoversikt for hele måneden

**Ressurskategorier som mangler:**
- Musikk og sang (NRK Super, Alfabia, akkordark)
- Mat og ernæring (Helsedirektoratets veileder, Matportalen)
- Overgang barnehage til skole (Udirs veileder, samarbeidsskjemaer)
- Digital kompetanse for barn (Lær Kidsa Koding, Kodeklubben)
- HMS og trivsel for ansatte
- Flerkulturell kompetanse (utvide NAFO-lenker)

**Teknisk gjeld:**
- SEO: tittel-tags og meta-descriptions er ikke konsistente på tvers av alle sider

---

## Forslag videre

**Umiddelbart (denne uka / helga):**

1. **Oppfølging av outreach-mail** — fristen er i morgen, fredag 28. mars. En kort, direkte mail: «Bare ville høre om dere fikk mailen min fra mandag, og om barnehagekassa.no er noe dere kan tenke dere å nevne for leserne deres.» Hold det kort. Ikke unnskyld deg for å sende en ny mail.

2. **Facebook-grupper** — dette er trolig den raskeste veien til faktiske brukere. Grupper som «Barnehagelærere», «Barnehageansatte i Norge» og lignende har tusenvis av medlemmer. Et enkelt innlegg med bilde av navnetrekkhjulet eller opptaksplanleggeren vil fungere bedre enn tekst alene.

3. **Dagsrapportbygger** — dette er det eneste høyprioriterte verktøyet fra lista som ikke er laget ennå. Etterspurt, enkelt å bruke og raskt å bygge. Turplanlegger og sesongkalender er i boks, dette er neste naturlige steg.

**Innen et par uker:**

4. **SEO-gjennomgang** — siden begynner å ha nok innhold til at det er verdt å sette konsistente tittel-tags og meta-descriptions på alle sider. Enkelt å automatisere med et script som sjekker alle HTML-filer.

5. **Allergioversikt-bygger** — enkel å bygge, høy brukerverdi, og naturlig å kombinere med dagsrapportbygger.

6. **Ressurssiden «Overgang barnehage til skole»** — svært tidsaktuelt nå (vår = overgangsperiode). Udirs veileder, samarbeidsskjemaer og sjekklister for overgangssamtalen kan samles på én side raskt.

7. **Videoinnhold** — navnetrekkhjulet og opptaksplanleggeren er visuelt sterke og egner seg godt for et 30–60 sekunders klipp. TikTok og Instagram Reels er frie kanaler med stor rekkevidde i yrkesgrupper. En skjermopptak-video av navnetrekk med ekte barnenavn vil funke godt.

---

*Rapporten er automatisk generert fredag 27. mars 2026.*
