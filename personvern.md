# Personvernerklæring for Tenkt

**Sist oppdatert: 4/5/2026

Denne personvernerklæringen beskriver hvordan Tenkt ("vi", "oss",
"appen") behandler informasjon når du bruker iOS-applikasjonen vår. Vi
er forpliktet til å holde appen privat som standard — de fleste
funksjoner fungerer helt offline, og vi driver ingen egne servere eller
analyseverktøy.

## 1. Informasjon vi samler inn

Tenkt samler inn svært lite selv. Dataflytene er:

### 1.1 Lokalt på enheten din (sendes aldri til oss)
- Puslespill-fremdrift, fullføringstider, streaks og statistikk
- Innstillinger (tema, språk, lyd, vibrasjon)
- Pågående puslespill (så appen kan fortsette etter en omstart)

Disse dataene lever kun i iOS-lagring på enheten din. De lastes aldri
opp til noen server vi kontrollerer. Hvis du sletter appen, er
dataene borte.

### 1.2 Anonymt globalt leaderboard (Apple iCloud / CloudKit)
Når du fullfører dagens sett, sender appen følgende til Apples CloudKit
public database:
- En anonym identifikator fra iCloud-kontoen din
  (`CKContainer.userRecordID` — vi ser aldri Apple-ID, navn eller
  e-post)
- UTC-datoen for puslespillet ("seedID")
- Total fullføringstid i sekunder

Dataene brukes utelukkende til å beregne og vise det globale
leaderboardet. Vi knytter dem aldri til navnet ditt, e-posten din eller
annen personlig informasjon. Andre spillere ser kun en anonymisert
identifikator (f.eks. «Spiller A3F4»), ikke ditt virkelige navn.

CloudKit drives av Apple under deres egne personvernvilkår. Du kan
logge ut av iCloud i iOS Innstillinger når som helst for å stoppe
dataflyten — appen fungerer uansett, men uten leaderboard-funksjoner.

### 1.3 Reklame (Google AdMob)
Tenkt er gratis og støttes av reklame fra Google AdMob. AdMob kan samle:
- Enhetens reklame-identifikator (IDFA), hvis du gir samtykke via
  iOS-dialogen for sporing (App Tracking Transparency)
- Standard reklamesignaler (visninger, klikk, ytelse)
- Diagnostikk for å levere annonser (enhetsmodell, OS-versjon,
  omtrentlig IP-basert lokasjon, språk)

Hvis du avslår sporings-dialogen, viser AdMob kun ikke-personaliserte
annonser.

Du kan fjerne all reklame permanent med ett engangskjøp i appen
(«Fjern reklame»). Etter kjøpet er AdMob fullstendig deaktivert.

For detaljer om hvordan Google behandler dataene, se Googles
personvernerklæring på https://policies.google.com/privacy.

### 1.4 Kjøp (Apple StoreKit)
Hvis du gjør «Fjern reklame»-kjøpet, behandler Apple transaksjonen via
StoreKit. Vi mottar en transaksjons-oppføring (produkt-ID, kjøpsdato,
transaksjons-ID) så vi kan verifisere kjøpet og deaktivere reklame. Vi
ser aldri betalingsmetoden din, navn eller adresse — Apple håndterer
all fakturering.

## 2. Informasjon vi IKKE samler inn

Vi vil være spesifikke om hva vi *ikke* gjør:
- Vi driver ingen egne servere eller backend
- Vi bruker ingen analysetjeneste (ikke Firebase Analytics, ikke
  Mixpanel, ingen tredjeparts-tracking-SDK-er utover AdMob)
- Vi samler ikke inn navn, e-post, telefonnummer eller kontaktinfo
- Vi har ikke tilgang til kamera, mikrofon, kontakter eller lokasjon
- Vi sender ikke markedsførings-e-poster eller push-markedsføring
- Vi selger ikke dataene dine til noen

## 3. Push-varsler

Tenkt kan sende lokale varsler (daglig påminnelse kl. 06:00 hvis du
aktiverer det). Disse planlegges utelukkende på enheten din — vi har
ingen push-server og sender aldri eksterne pushes. Du kan deaktivere
varsler når som helst i iOS Innstillinger.

## 4. Barns personvern

Tenkt samler ikke bevisst inn personlig informasjon fra barn under 13
år. Appen er aldersgrenseangitt 4+ og inneholder ingen chat-funksjoner,
ingen brukerprofiler, og ingen måte for brukere å kommunisere med
hverandre. Annonsene levert av AdMob er underlagt Googles
familievennlige reklamepolicy.

## 5. Dine rettigheter (GDPR)

Etter personvernforordningen (GDPR) har du følgende rettigheter:

- **Innsyn**: Du kan be om en kopi av eventuelle data vi har om deg. I
  praksis lagrer vi ingen personlige data — kun en anonym identifikator
  knyttet til iCloud-kontoen din.
- **Sletting**: Du kan slette leaderboard-oppføringene dine ved å
  sende e-post til [SUPPORT-EPOST]. Oppgi omtrentlige datoer for
  innsendelsene så vi finner dem.
- **Trekke samtykke til sporing**: Du kan deaktivere
  sporings-tillatelse når som helst i iOS Innstillinger → Personvern
  og sikkerhet → Sporing, eller fjerne all reklame med kjøpet
  «Fjern reklame».

## 6. Datalagring

- Lokale data: forblir på enheten din til du sletter appen
- CloudKit-leaderboard-oppføringer: lagres tidsubestemt for å støtte
  historiske leaderboards. Du kan be om sletting (se punkt 5).
- AdMob-data: lagres etter Googles retningslinjer (typisk 14 måneder
  for identifiserte data)

## 7. Endringer i denne erklæringen

Vi kan oppdatere denne erklæringen etter hvert som appen utvikler seg.
«Sist oppdatert»-datoen øverst gjenspeiler endringene. Vesentlige
endringer kunngjøres i appens versjonsnotat.

## 8. Kontakt

For personvernspørsmål eller for å utøve rettighetene dine, kontakt
oss:

**E-post:** jonasbjh@gmail.com
**Utvikler:** Jonas Haug
**Adresse:** Konvallveien 20a, Drammen
