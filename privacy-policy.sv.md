---
layout: legal
group: privacy
lang: sv
dir: ltr
permalink: /privacy/sv/
title: "Integritetspolicy"
---


> **UTKAST — INTE JURIDISK RÅDGIVNING.**
> Detta dokument är ett utkast som återspeglar hur appen faktiskt fungerar.
> Det måste granskas av en jurist med behörighet i svensk dataskyddsrätt
> och EU-konsumentskydd innan det publiceras. Ingenting här utgör juridisk
> rådgivning eller garanterar att dokumentet uppfyller lagens krav.
>
> **Notera:** Denna svenska text är maskinassisterad. En kvalificerad
> jurist med behörighet i Sverige MÅSTE granska och godkänna den innan
> publicering.

# Integritetspolicy — Körkort Theory

**Ikraftträdandedatum:** [IKRAFTTRÄDANDEDATUM]
**Version:** 1.0

Denna integritetspolicy ("**Policy**") förklarar hur
**[UTGIVARENS JURIDISKA NAMN]** ("**vi**", "**oss**", "**vår**") hanterar
information i samband med mobilapplikationen **Körkort Theory** ("**Appen**").

---

## 1. Vem vi är

**[UTGIVARENS JURIDISKA NAMN]**
[UTGIVARENS ADRESS]
[UTGIVARENS LAND]
Org./VAT nr: [ORG-NUMMER]
E-post: [KONTAKT-E-POST]

---

## 2. Kortversionen

**Körkort Theory samlar inte in, överför eller lagrar några personuppgifter
på våra servrar.** Appen har ingen server, inga användarkonton, inget
analyse-SDK, inget reklam-SDK och inget kraschrapporterings-SDK. All data som
genereras när du använder Appen (dina svar, provresultat, framsteg,
inställningar och Premium-behörighet) lagras uteslutande på din egen enhet och
lämnar aldrig den.

Vi agerar därför inte som personuppgiftsansvarig avseende personuppgifter du
genererar i Appen, eftersom vi aldrig tar emot eller behandlar sådana uppgifter.

Den enda behandling av personuppgifter som sker i samband med att hämta Appen
eller köpa Premium utförs av **Apple** (App Store) eller **Google** (Google
Play) under deras egna integritetspolicyer. Vi har inte tillgång till dina
betalningsuppgifter eller information om ditt butikskonto.

---

## 3. Data som lagras på din enhet

Följande information skapas och lagras lokalt på din enhet av Appen. Den
lämnar aldrig enheten.

| Datatyp | Vad den innehåller | Var den lagras |
|---------|-------------------|----------------|
| Frågaförsök | Vilka frågor du svarade på, om rätt, tidsstämpel | Lokal SQLite-databas (Drift) |
| Provresultat | Poäng, godkänd/underkänd, tidsstämpel, fråga-för-fråga-breakdown | Lokal SQLite-databas |
| Framsteg & analyser | Kategori-nivå prestandaaggregat härledd från försök | Lokal SQLite-databas |
| Flaggade frågor | Fråge-ID:n du manuellt flaggat för granskning | Lokal SQLite-databas |
| Premium-behörighet | En boolesk flagga som anger om Premium har låsts upp | Lokal krypterad säker lagring (flutter_secure_storage) |
| UI/innehållsspråkpreferens | Ditt valda UI-språk (sv/en/ar) och innehållsspråk | Lokal SQLite-inställningstabell |

Ingen av dessa uppgifter överförs till oss eller till någon tredje part av Appen.

---

## 4. Data som samlas in av Apple och Google

När du laddar ned Appen eller gör ett köp via Appen:

- **Apple App Store / Apple StoreKit**: Apple behandlar din butikskontoinformation,
  enhetsidentifierare och betalningsuppgifter under
  [Apples integritetspolicy](https://www.apple.com/legal/privacy/). Vi tar
  emot endast ett butikskvitto för att verifiera din behörighet lokalt, på
  enheten. Vi tar inte emot ditt Apple-ID, dina betalningsuppgifter eller
  andra personuppgifter.

- **Google Play / Google Play Billing**: Google behandlar motsvarande information
  under [Googles integritetspolicy](https://policies.google.com/privacy). Vi
  tar emot endast en inköpstoken, verifierad lokalt. Vi tar inte emot ditt
  Google-kontos uppgifter eller betalningsinformation.

Vi har ingen kontroll över hur Apple eller Google behandlar dina uppgifter;
granska deras integritetspolicyer direkt.

---

## 5. Inga cookies, ingen spårning, ingen reklam

Appen använder inte:

- cookies eller webbläsarlagring (det är en inbyggd mobilapp);
- reklamidentifierare (IDFA/GAID) — Appen begär eller läser inte dessa
  identifierare;
- något analyse-SDK (inget Firebase Analytics, Mixpanel, Amplitude eller
  motsvarande);
- något kraschrapporterings-SDK (inget Crashlytics, Sentry eller motsvarande);
- något annonsnätverk eller reklam-SDK.

---

## 6. Barn

Appen riktar sig inte till barn under 13 år. Vi samlar inte medvetet in
personuppgifter från barn under 13 år. Eftersom Appen inte samlar in några
personuppgifter alls från vår sida finns det ingen specifik åldersgräns i
Appen utöver behörighetskraven i våra Villkor. Om du är förälder eller
vårdnadshavare och tror att ditt barn har använt Appen finns det ingenting
för oss att radera; eventuell data är lokal på enheten och kan raderas
genom att avinstallera Appen.

---

## 7. Radering av data och lagring

All App-data lagras enbart på din enhet. Du kan radera all data när som helst
genom att avinstallera Appen. Eftersom vi inte håller några data på våra
servrar har vi inget att radera på begäran.

Din Premium-behörighet är knuten till ditt butikskonto (Apple-ID eller
Google-konto), inte till oss. Återställning av ett köp efter ominstallering
hanteras helt av respektive butik.

---

## 8. Dina rättigheter enligt GDPR och tillämplig dataskyddslagstiftning

Eftersom vi inte behandlar personuppgifter om dig som personuppgiftsansvarig
gäller de flesta registrerades rättigheter under GDPR (rätt till tillgång,
rättelse, radering, portabilitet, begränsning och invändning) inte oss i
förhållande till App-användningsdata — dessa uppgifter existerar bara på
din enhet.

Om du anser att vi innehar personuppgifter om dig (till exempel om du har
kontaktat oss via e-post) har du rätt att:

- få tillgång till en kopia av dessa uppgifter;
- få dem rättade eller raderade;
- invända mot eller begränsa behandlingen;
- lämna in ett klagomål till behörig tillsynsmyndighet.

**Tillsynsmyndighet:** Om du befinner dig i Sverige kan du kontakta
Integritetsskyddsmyndigheten (IMY) på [www.imy.se](https://www.imy.se). Om du
befinner dig i en annan EU/EES-medlemsstat kan du kontakta din lokala
tillsynsmyndighet.

För att utöva dina rättigheter eller ställa en integritetsfråga, kontakta oss på:
[KONTAKT-E-POST]

---

## 9. Internationella överföringar

Vi överför inte personuppgifter internationellt eftersom vi inte innehar
personuppgifter. Om du kontaktar oss via e-post kan din e-post behandlas av
vår e-postleverantör, som kan ha infrastruktur i länder utanför EU/EES.
[ÖPPEN PUNKT — identifiera din e-postleverantör och bekräfta om en
överföringsmekanism (t.ex. standardavtalsklausuler) krävs. Juristgranskning
behövs.]

---

## 10. Säkerhet

All App-data lagras på din enhet under de skydd som tillhandahålls av enhetens
operativsystem. Premium-behörighet lagras med `flutter_secure_storage`, som
använder iOS Keychain och Android Keystore för kryptering. Säkerheten för
dessa data beror på din enhets egna säkerhet (skärmlås, OS-version etc.).
Vi driver inga servrar som innehar dina data, så det finns ingen server-side
säkerhetsställning att beskriva.

---

## 11. Ändringar av denna Policy

Vi kan uppdatera denna Policy från tid till annan. **"Ikraftträdandedatum"**
längst upp anger när den nuvarande versionen trädde i kraft. Vi ger rimlig
förvarning om väsentliga ändringar (till exempel via ett meddelande i appen
eller en uppdaterad version i butiken). Din fortsatta användning av Appen
efter att ändringar trätt i kraft utgör ett godkännande av den reviderade
Policyn.

---

## 12. Kontakt

För integritetsrelaterade frågor eller förfrågningar:

**[UTGIVARENS JURIDISKA NAMN]**
[UTGIVARENS ADRESS]
[UTGIVARENS LAND]
E-post: [KONTAKT-E-POST]

---

*Körkort Theory är ett fristående studieverktyg och är inte anslutet till eller
godkänt av Trafikverket. Detta dokument är ett utkast och utgör inte juridisk
rådgivning; låt en kvalificerad jurist granska det innan publicering.*
