# Privacy Policy

**Effective date:** 2026-05-02
**Last updated:** 2026-05-02

This Privacy Policy explains how Ronny Doron Efronny ("**we**", "**us**", "**Robed**"), an individual sole developer based in Israel, collects, uses, and shares information when you use the Robed mobile application ("**App**" or "**Service**").

If you have questions about this policy or want to exercise any of the rights described below, contact us at **robed.app@gmail.com**.

## 1. Scope

This policy applies to the Robed Android application published under the package name `com.lark.robed`. It does not apply to third-party services that we link to or that integrate with the App; those are governed by their own privacy policies, several of which are listed in Section 6.

## 2. Who can use Robed

Robed is intended for users who are **at least 16 years old**. We do not knowingly collect information from anyone under 16. If you believe a person under 16 has provided us information, please contact us and we will delete it.

## 3. Information we collect

### 3.1 Information you give us

- **Account information.** When you sign in with Google, we receive your Google account email address, full name, and Google account identifier from Google. We do not receive your Google password.
- **Profile information.** You may optionally add information such as gender to your in-app profile.
- **Wardrobe content.** Photos you take or upload of your clothing items, plus any metadata you add or that is generated for those items (category, brand, colors, materials, patterns, fit, occasions, tags, notes, ratings, and similar attributes).
- **Optional body image.** If you choose to upload a body image to help Robed visualize outfits on you, we store that image. You can remove it at any time from the App.
- **Looks and outfits.** Outfits ("looks") that you compose, save to your lookbook, generate using AI, name, rate, or annotate.
- **Communications.** If you email us at robed.app@gmail.com, we receive the contents of your message and your email address.

### 3.2 Information collected automatically

- **Usage data.** Records of AI-related actions you take (for example, how many clothing items you uploaded for AI tagging today, or how many AI look previews you generated) for the purpose of enforcing daily limits and operating the Service.
- **Diagnostic data.** When the App crashes or encounters errors, we collect crash reports and error context through Sentry. These reports are tagged with your account identifier (so we can correlate issues to your account) along with technical information such as device model, operating system version, App version, stack traces, and breadcrumbs of recent App actions. We do **not** attach your email address or name to crash reports.
- **Session replays.** Sentry captures short replays of App interactions (screen content, gestures, and navigation) when an error occurs, so we can reproduce the bug. Replays are tagged with your account identifier. Replays may incidentally capture content displayed on screen during the error (for example, the wardrobe screen you were viewing).
- **In-App feedback.** If you use the in-App "Send feedback" form, the message you write, plus any name or email you choose to include in the form, is sent to Sentry so we can read and respond to it.
- **Feature-flag context.** We use LaunchDarkly to roll out features gradually. We send LaunchDarkly a context that may include your account identifier so that flag values are stable for your account.
- **Update channel data.** We use Expo Application Services (EAS) to deliver over-the-air updates. Standard request metadata (such as your IP address, App version, and device fingerprint) is processed when checking for updates.
- **Advertising data.** Robed shows ads through Google AdMob. AdMob and its partners may collect or receive information including your Android Advertising ID, approximate (non-precise) location derived from your IP address, device identifiers, and limited interaction data with ads. AdMob's data practices are governed by Google's privacy policy and partner program policies.

### 3.3 Information we do **not** collect

We do not collect or process precise GPS location, contacts, microphone audio, biometric identifiers, payment card numbers, government identification numbers, or health information. We do not knowingly collect special categories of personal data (as that term is used under the GDPR) other than what you may voluntarily place into your photos or wardrobe descriptions.

## 4. How we use information

We use the information described above to:

- create and operate your account;
- store, display, and let you manage your wardrobe and looks;
- power the AI features of the App, including automatic tagging of clothing photos and AI-assisted outfit suggestions (see Section 5);
- enforce per-account daily usage limits on AI-related features;
- diagnose, fix, and prevent bugs, crashes, and abuse;
- communicate with you about your account, security, important changes to the Service, and your support requests;
- comply with applicable law and respond to lawful requests; and
- show ads through Google AdMob and measure their delivery.

We do not sell your personal information, and we do not "share" your personal information for cross-context behavioral advertising as those terms are defined under the California Consumer Privacy Act, except to the limited extent that AdMob and its partners receive advertising identifiers in order to serve ads (you can opt out at the operating-system level — see Section 9).

### Legal bases (GDPR / UK GDPR)

Where the GDPR or UK GDPR applies, we rely on the following legal bases:

- **Performance of a contract** (Article 6(1)(b)): to provide the Service you signed up for, including storing your wardrobe content and producing the AI features you request.
- **Legitimate interests** (Article 6(1)(f)): to keep the Service secure, prevent abuse, debug crashes, enforce usage limits, and operate the App in a sustainable way. We have balanced these interests against your privacy rights.
- **Consent** (Article 6(1)(a)): for any processing that requires consent under applicable law, such as the use of advertising identifiers where consent is required in your jurisdiction. You can withdraw consent at any time.
- **Legal obligation** (Article 6(1)(c)): where we must process information to comply with applicable law.

## 5. AI features and Google Gemini

Robed uses Google's Gemini models, accessed through a paid Google AI Studio API key, to (a) analyze photos of clothing items you upload and extract attributes such as category, color, material, pattern, and fit, and (b) generate outfit ideas based on the wardrobe metadata you have built up.

When you upload a clothing item, the image is sent to Google's Gemini API for analysis. When you ask the App to generate an outfit, Robed sends Gemini metadata about the relevant items in your wardrobe (such as colors, categories, and tags) along with your prompt. Body images, if you have chosen to upload one, are not sent to Gemini for outfit generation.

Google's API terms for paid use of the Gemini API state that Google does not use prompts, inputs (including images), or responses generated through paid use of the API to train or improve Google's products. We rely on Google's terms for that representation; we encourage you to review Google's published API terms and privacy policy for the most current information.

AI outputs may be inaccurate, incomplete, or biased. They are suggestions, not professional advice.

## 6. How we share information (sub-processors and recipients)

We share information with the following categories of recipients in order to operate the Service. Each is bound by its own privacy commitments and contractual or legal obligations.

- **Supabase, Inc.** — Hosts our database, authentication system, and image storage buckets. Receives your account information, wardrobe content, looks, usage records, and any other content stored in the App.
- **Google LLC and affiliates:**
  - **Google Sign-In** — handles authentication and provides us your email, name, and Google account identifier.
  - **Google AI Studio (Gemini API)** — receives clothing photos and wardrobe metadata for AI processing as described in Section 5.
  - **Google AdMob** — receives advertising identifiers and ad-related signals to serve ads.
- **Functional Software, Inc. (Sentry)** — receives crash and error reports tagged with your account identifier, technical device data, short session replays of in-App activity around an error, and any feedback you submit through the in-App feedback form.
- **Catamorphic Co. (LaunchDarkly)** — receives a feature-flag evaluation context that may include your account identifier.
- **650 Industries, Inc. (Expo / EAS)** — delivers over-the-air updates and receives standard request metadata when your App checks for updates.
- **Service providers we engage in the future** — we may add similar infrastructure providers and will update this policy when we do.

We may also disclose information (i) to comply with valid legal process, (ii) to protect the rights, property, or safety of users, the public, or us, (iii) to investigate fraud, abuse, or security issues, or (iv) in connection with a merger, acquisition, financing, or sale of assets, in which case we will require the recipient to honor commitments made in this policy or notify you of material changes.

We do not sell your personal information for money.

## 7. International data transfers

Robed is operated by an individual based in Israel. Israel has been recognized by the European Commission as providing an adequate level of protection for personal data transferred from the European Economic Area. Several of the sub-processors listed in Section 6 are based in the United States or operate global infrastructure, so your information may be transferred to and processed in countries outside your country of residence. Where required, those transfers rely on mechanisms such as the European Commission's Standard Contractual Clauses, applicable adequacy decisions, or the EU–U.S. Data Privacy Framework, depending on the recipient.

## 8. How long we keep information

We keep your account information and content for as long as your account exists. When you delete your account from within the App (or by emailing us), we promptly delete:

- your account record and authentication data;
- all clothing items, looks, lookbook entries, and uploaded images (including any body image) from our database and storage; and
- any associated usage records that are tied to your account.

After deletion:

- **Backups.** Routine backups are retained on a rolling basis for up to approximately 30 days and then overwritten in the ordinary course of business.
- **Diagnostic logs and session replays.** Sentry diagnostic data tagged with your account identifier (crash reports, breadcrumbs, and session replays) is retained for up to approximately 90 days, then is deleted or de-identified.
- **Legal retention.** We may retain a minimal record of the deletion event itself, and any information we are legally required to keep, for as long as required.

## 9. Your choices and rights

Subject to applicable law, you have the following rights with respect to your personal information:

- **Access** the personal information we hold about you.
- **Correct** information that is inaccurate or incomplete.
- **Delete** your personal information ("right to erasure" / "right to delete"). You can do this yourself by deleting your account from the App settings, or by emailing us.
- **Object to** or **restrict** certain processing.
- **Portability** — receive a copy of the information you provided to us in a structured, machine-readable format.
- **Withdraw consent** where processing is based on consent.
- **Lodge a complaint** with a supervisory authority (for EEA/UK users) or your local data protection authority.

To exercise any of these rights, email **robed.app@gmail.com** from the email address associated with your account. We will respond within the timeframes required by applicable law (typically 30 days under the GDPR and 45 days under the CCPA/CPRA, with extensions where permitted). We do not discriminate against users who exercise their privacy rights.

### California residents (CCPA / CPRA)

In the past 12 months, we have collected the categories of personal information described in Section 3 (identifiers, customer-account information, internet/electronic-network activity, geolocation derived from IP, visual information you upload, and inferences drawn from that information for the purpose of operating AI features). We have disclosed those categories to the categories of recipients listed in Section 6 for the operational purposes described in Section 4.

We do **not** sell personal information for money. We do not knowingly use or share personal information about consumers under 16. To the extent that the use of advertising identifiers by AdMob and its partners constitutes "sharing" under the CPRA, you may opt out by following the AdMob/Google opt-out instructions and by enabling "Opt out of Ads Personalization" in your Android device's settings under **Settings → Google → Ads**. You may also email us to request that we stop any such sharing for your account.

You may designate an authorized agent to make a request on your behalf; we will require reasonable verification of the agent's authority and your identity.

### Advertising controls

You can reset or limit the use of your Android Advertising ID at any time from your device settings (**Settings → Google → Ads** on most Android devices). If you reset the ID or opt out of ads personalization, you may still see ads, but they will be less personalized.

## 10. Security

We use standard security practices to protect your information, including encryption in transit (HTTPS) for data sent between the App and our servers, encryption at rest provided by our infrastructure providers, and access controls limited to the developer. No system is perfectly secure. If we become aware of a security incident that affects your information, we will notify you and applicable regulators as required by law.

## 11. Children

Robed is not directed to children under 16, and we do not knowingly collect personal information from anyone under 16. If you are a parent or guardian and believe your child has provided us with personal information, please contact us at robed.app@gmail.com and we will delete it.

## 12. Changes to this policy

We may update this Privacy Policy from time to time. If we make material changes, we will update the "Last updated" date at the top of this policy and, where required by law, provide additional notice (for example, an in-App notice or an email to the address associated with your account). Your continued use of the App after a change becomes effective constitutes acceptance of the updated policy.

## 13. Contact

For questions, complaints, or to exercise your rights under this policy:

**Email:** robed.app@gmail.com
**Operator:** Ronny Doron Efronny, Israel
