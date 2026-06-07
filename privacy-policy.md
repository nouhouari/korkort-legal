---
layout: legal
group: privacy
lang: en
dir: ltr
permalink: /privacy/
title: "Privacy Policy"
---


> **DRAFT — NOT LEGAL ADVICE.**
> This document is a first draft prepared to reflect how the App actually
> operates. It must be reviewed and approved by a lawyer qualified in
> Swedish/EU data-protection law before it is published or relied upon.
> Nothing here constitutes legal advice or guarantees compliance with any law.

# Privacy Policy — Körkort Theory

**Effective date:** [EFFECTIVE DATE]
**Version:** 1.0

This Privacy Policy ("**Policy**") explains how **[PUBLISHER LEGAL NAME]**
("**we**", "**us**", "**our**") handles information in connection with the
**Körkort Theory** mobile application ("**App**").

---

## 1. Who we are

**[PUBLISHER LEGAL NAME]**
[PUBLISHER ADDRESS]
[PUBLISHER COUNTRY]
Org./VAT no.: [ORG NUMBER]
Email: [CONTACT EMAIL]

---

## 2. The short version

**Körkort Theory does not collect, transmit, or store any personal data on our
servers.** The App has no backend, no user accounts, no analytics SDK, no
advertising SDK, and no crash-reporting SDK. All data generated while you use
the App (your answers, exam results, progress, settings, and Premium
entitlement) is stored exclusively on your own device and never leaves it.

We are therefore not acting as a data controller in respect of personal data
you generate inside the App, because we never receive or process that data.

The only personal data processing that occurs in connection with obtaining the
App or purchasing Premium is carried out by **Apple** (App Store) or **Google**
(Google Play) under their own privacy policies. We have no access to your
payment details or your store account information.

---

## 3. Data stored on your device

The following information is created and stored locally on your device by the
App. It never leaves the device.

| Data type | What it contains | Where stored |
|-----------|-----------------|--------------|
| Question attempts | Which questions you answered, whether correct, timestamp | On-device SQLite database (Drift) |
| Exam results | Score, pass/fail, timestamp, per-question breakdown | On-device SQLite database |
| Progress & analytics | Category-level performance aggregates derived from attempts | On-device SQLite database |
| Flagged questions | Question IDs you have manually flagged for review | On-device SQLite database |
| Premium entitlement | A boolean flag indicating whether Premium has been unlocked | On-device encrypted secure storage (flutter_secure_storage) |
| UI / content language preference | Your chosen UI language (sv/en/ar) and content language | On-device SQLite settings table |

None of this information is transmitted to us or to any third party by the App.

---

## 4. Data collected by Apple and Google

When you download the App or make a purchase through the App:

- **Apple App Store / Apple StoreKit**: Apple processes your store account
  information, device identifiers, and payment details under
  [Apple's Privacy Policy](https://www.apple.com/legal/privacy/). We receive
  only a store receipt to verify your entitlement locally, on-device. We do
  not receive your Apple ID, payment details, or any other personal data.

- **Google Play / Google Play Billing**: Google processes equivalent information
  under [Google's Privacy Policy](https://policies.google.com/privacy). We
  receive only a purchase token, verified locally. We do not receive your
  Google account details or payment information.

We have no control over how Apple or Google process your data; please review
their privacy policies directly.

---

## 5. No cookies, no tracking, no advertising

The App does not use:

- cookies or browser storage (it is a native mobile app);
- advertising identifiers (IDFA / GAID) — the App does not request or read
  these identifiers;
- any analytics SDK (no Firebase Analytics, no Mixpanel, no Amplitude, or
  equivalent);
- any crash-reporting SDK (no Crashlytics, no Sentry, or equivalent);
- any advertising network or ad SDK.

---

## 6. Children

The App is not directed at children under 13. We do not knowingly collect
personal data from children under 13. Because the App collects no personal
data at all on our end, there is no specific age-gating mechanism in the App
itself beyond the eligibility requirements in our Terms & Conditions. If you
are a parent or guardian and believe your child has used the App, there is
nothing for us to delete on our side; any data is local to the device and can
be erased by uninstalling the App.

---

## 7. Data deletion and retention

All App data is stored only on your device. You can delete all data at any time
by uninstalling the App. Because we hold no data on our servers, we have
nothing to delete on request.

Your Premium entitlement is linked to your store account (Apple ID or Google
account), not to us. Restoring a purchase after reinstalling is handled
entirely by the relevant store.

---

## 8. Your rights under GDPR and applicable data-protection law

Because we do not process personal data about you as a data controller, most
data-subject rights under the GDPR (right of access, rectification, erasure,
portability, restriction, and objection) do not apply to us in relation to App
usage data — that data exists only on your device.

If you believe we hold any personal data about you (for example, if you have
contacted us by email), you have the right to:

- access a copy of that data;
- have it corrected or erased;
- object to or restrict its processing;
- lodge a complaint with the competent supervisory authority.

**Supervisory authority:** If you are located in Sweden, you may contact the
Swedish Data Protection Authority (Integritetsskyddsmyndigheten, IMY) at
[www.imy.se](https://www.imy.se). If you are located in another EU/EEA member
state, you may contact your local supervisory authority.

To exercise your rights or make a privacy enquiry, contact us at:
[CONTACT EMAIL]

---

## 9. International transfers

We do not transfer personal data internationally, because we do not hold
personal data. If you contact us by email, your email may be processed by our
email service provider, which may operate infrastructure in countries outside
the EU/EEA. [OPEN ITEM — identify your email provider and confirm whether a
transfer mechanism (e.g. Standard Contractual Clauses) is required. Lawyer
review needed.]

---

## 10. Security

All App data is stored on your device under the protections provided by your
device's operating system. Premium entitlement is stored using
`flutter_secure_storage`, which uses the iOS Keychain and Android Keystore
for encryption. The security of this data depends on your device's own security
(screen lock, OS version, etc.). We do not operate servers that hold your data,
so there is no server-side security posture to describe.

---

## 11. Changes to this Policy

We may update this Policy from time to time. The **"Effective date"** at the
top indicates when the current version took effect. We will provide reasonable
notice of material changes (for example, via an in-app notice or an updated
version in the store). Your continued use of the App after changes take effect
constitutes acceptance of the revised Policy.

---

## 12. Contact

For any privacy-related questions or requests:

**[PUBLISHER LEGAL NAME]**
[PUBLISHER ADDRESS]
[PUBLISHER COUNTRY]
Email: [CONTACT EMAIL]

---

*Körkort Theory is an independent study aid and is not affiliated with or
endorsed by Trafikverket. This document is a draft template and does not
constitute legal advice; have it reviewed by a qualified lawyer before
publication.*
