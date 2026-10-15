# Privacy Policy

*Last Updated: June 17, 2026*


**Provider / Data Controller:**
Dr. Yulia Rönsch
Kirchenstrasse 2
82194 Gröbenzell, Germany
Email: peal-tables.3v@icloud.com
Phone: +49-177-4901659

#### Introduction

This Privacy Policy explains how VoiceToPen (the "App") handles your data. It applies to all users worldwide.

The single most important thing to understand about VoiceToPen is this: **it is a local-first application with no backend of our own.** We operate no servers, no database, and no user accounts. We never receive, see, or store the voice memos you import, the transcripts produced from them, or the polished text the App generates. All of that lives on your Mac.

The App does two things that involve sending data off your device, and in both cases the data goes **directly from your Mac to a third-party service that you have signed up for yourself, using your own credentials**:

- **Transcription** — your audio is sent to **ElevenLabs** to be converted to text, using **your own ElevenLabs API key**.
- **Polishing and structuring** — the resulting transcript is sent to **Anthropic** (the Claude API) to be cleaned up and structured, using **your own Anthropic API key**.

Because you connect these services with your own accounts and keys, your relationship for that processing is **directly with ElevenLabs and Anthropic**, under their terms and privacy policies. We are not in the middle of it and we do not receive a copy. This policy explains all of that honestly and in detail.

We do not use cookies, advertising trackers, analytics, or crash-reporting SDKs. We do not maintain user accounts and we do not know who you are by name.

#### 1. Data Controller

The provider of the App is:

Dr. Yulia Rönsch, Kirchenstrasse 2, 82194 Gröbenzell, Germany.
Email: peal-tables.3v@icloud.com — Phone: +49-177-4901659.

We act as a "data controller" within the meaning of the GDPR only for the limited personal data we actually receive — in practice, the contents of any email or support message **you choose to send us**. For the transcription and polishing steps, you initiate the processing under your own provider accounts (see Section 5).

#### 2. How the App Works (Data Flow)

1. You import a voice memo that you recorded elsewhere. The audio file is stored **locally on your Mac**.
2. When you choose to transcribe it, the App sends the audio **directly to ElevenLabs**, authenticated with the ElevenLabs API key **you** entered. ElevenLabs returns a text transcript, which is stored **locally on your Mac**.
3. When you choose to polish and structure the transcript, the App sends that text **directly to Anthropic's Claude API**, authenticated with the Anthropic API key **you** entered. Anthropic returns the polished text, which is stored **locally on your Mac**.
4. At no point does any of this data pass through, or get stored on, any server operated by us. We have no such server.

#### 3. Data That Stays on Your Mac

The following is stored exclusively on your device and is never transmitted to us:

- **Imported voice memos** (audio files).
- **Transcripts** returned by ElevenLabs.
- **Polished and structured text** returned by Anthropic.
- **Your API keys** for ElevenLabs and Anthropic. These are stored in the **macOS Keychain**, the operating system's encrypted credential store. We never transmit your keys to ourselves.
- **App preferences and settings.**

You can delete any of this at any time within the App, or by removing the App and its data from your Mac. We have no ability to access, recover, or restore it.

#### 4. Data We Process

Because the App has no backend, the only personal data we ever receive is data **you actively choose to send us** — for example, if you email us for support. In that case we process your email address and the contents of your message for the sole purpose of responding to you. The legal basis is our legitimate interest in providing support and our interest in (and your interest in) resolving your enquiry (Article 6(1)(f) GDPR), and, where your message concerns the App's paid functions, the performance of our contract with you (Article 6(1)(b) GDPR).

We do **not** collect or process: your name (unless you provide it), location data, cookies or tracking identifiers, advertising identifiers, usage analytics, crash analytics, or behavioural statistics. The App contains no third-party SDK that collects data on our behalf.

#### 5. Third-Party Services You Connect With Your Own Credentials

To use the transcription and polishing features, you must have your own accounts and API keys with the following providers. When you use those features, the App sends data **directly from your Mac to these providers under your account**. Your use of each service is governed by that provider's own terms and privacy policy, and your data-protection relationship for that processing is with them, not with us.

**ElevenLabs** (speech-to-text / transcription)
Your audio is sent to ElevenLabs to be transcribed. According to ElevenLabs, by default it retains request data in accordance with its privacy policy in order to operate, troubleshoot, and improve its services, and it may use voice data to help its models learn; it states that it does not use such data to profile or target you. ElevenLabs offers data-protection controls (and, on certain plans, zero-retention and EU data-residency options). We strongly recommend you review ElevenLabs' Privacy Policy and configure the privacy settings available in your ElevenLabs account.
- Privacy Policy: https://elevenlabs.io/privacy-policy
- Data Processing Addendum: https://elevenlabs.io/dpa

**Anthropic, PBC** (text polishing and structuring via the Claude API)
Your transcript text is sent to Anthropic's Claude API. According to Anthropic's commercial (API) terms, data you submit through the API is **not used to train its models** (unless you separately opt into a development-partner programme), and API inputs and outputs are retained only for a short period for operational and safety purposes. We recommend you review Anthropic's terms and privacy policy.
- Commercial Terms of Service: https://www.anthropic.com/legal/commercial-terms
- Privacy Policy: https://www.anthropic.com/legal/privacy

Both providers process data on servers that may be located in the **United States** or other countries. Because you transmit your data to them under your own account, any international transfer is carried out on the basis of **each provider's own published transfer safeguards** (such as EU Standard Contractual Clauses), as described in their respective policies. We are not party to those transfers.

A practical consequence of the "bring your own key" design: the privacy of your voice memos and transcripts during transcription and polishing depends primarily on the settings and plan you choose with ElevenLabs and Anthropic. We encourage you to review and configure them.

#### 6. Apple and the App Store

VoiceToPen is distributed through the Apple App Store / Mac App Store. When you download or purchase the App, **Apple** processes the transaction and any associated data as an independent controller under Apple's own privacy policy.  Where the App is a paid app, Apple is the merchant of record; we receive only aggregate, anonymised sales and (if you leave one) review information from Apple. We do not receive your name, email, or payment details. See Apple's privacy policy at https://www.apple.com/legal/privacy/.

#### 7. Legal Bases (GDPR)

For users in the EU, EEA, and the UK, the limited processing **we** carry out rests on the following legal bases under Article 6(1) GDPR:

| Purpose | Data | Legal basis |
|---|---|---|
| Responding to a support request you send us | Your email address and message content | Article 6(1)(f) GDPR (legitimate interest in providing support); Article 6(1)(b) where the request concerns a paid function. |
| Retaining records of any paid transaction for tax/accounting purposes | Transaction metadata provided by Apple | Article 6(1)(c) GDPR — legal obligation (in particular §§ 140, 147 of the German Fiscal Code). |

For the transcription and polishing steps, **you** are the one who initiates the transfer to ElevenLabs and Anthropic under your own accounts; the legal basis and controller responsibilities for that processing sit with you and those providers under their respective terms.

#### 8. Data Retention

| Data | Retention |
|---|---|
| Voice memos, transcripts, polished text, API keys, settings (on your Mac) | Kept on your device until you delete them or remove the App. We cannot access, recover, or restore them. |
| Data sent to ElevenLabs / Anthropic | Retained by each provider according to its own policy and your account settings (see Section 5). We retain nothing. |
| Support correspondence | Kept only as long as needed to handle your request and to comply with any applicable legal retention periods, then deleted. |

#### 9. Security

Communication between the App and the providers uses TLS encryption. Your API keys are held in the macOS Keychain, encrypted by the operating system. Your local files are protected by your Mac's built-in security features; we recommend you secure your Mac with a password and full-disk encryption (FileVault) and keep macOS updated.

No system can be guaranteed perfectly secure. Because we hold no personal data on any server of our own, the risk surface on our side is minimal. For the providers you connect to, their security is governed by their own policies.

#### 10. Your Rights

Regardless of where you live, you can:

- Delete any voice memo, transcript, or polished text directly in the App at any time;
- Remove the App and its local data from your Mac at any time;
- Contact us at peal-tables.3v@icloud.com with any privacy question or request. We aim to respond within 30 days.

Because we hold essentially no personal data about you on our side, requests for access, rectification, erasure, restriction, portability, or objection (Articles 15–21 GDPR) will, in most cases, concern data we simply do not have. **For data held by ElevenLabs or Anthropic, you should exercise your rights directly with those providers**, since you are their account holder and they control that data.

**EU/EEA users (GDPR):** You have the rights set out in Articles 15–22 GDPR and the right to lodge a complaint with a supervisory authority. The authority competent for us is the **Bayerisches Landesamt für Datenschutzaufsicht (BayLDA)**, Promenade 18, 91522 Ansbach, Germany — https://www.lda.bayern.de. You may also complain to the authority where you live or work.

**UK users (UK GDPR):** Equivalent rights apply; you may contact the Information Commissioner's Office at https://ico.org.uk.

**California residents (CCPA/CPRA):** You have the rights to know, access, correct, delete, and limit use of personal information, and to opt out of sale or sharing. **We do not sell or share personal information**, and as described above we hold virtually none. Contact peal-tables.3v@icloud.com.

**All other users:** You have the rights granted by the laws of your country. Because your data lives on your own device, you already have direct control over it.

#### 11. Children's Privacy

The App is not directed at children.  It is intended for users aged **17 and older**. We do not knowingly process data from children below this age. If you believe a child has used the App, contact peal-tables.3v@icloud.com.

#### 12. Use of AI and Its Limitations

VoiceToPen relies on third-party artificial-intelligence services to transcribe audio and to polish text. AI output can contain errors, omissions, or mis-transcriptions and may not faithfully represent what was said. You are responsible for reviewing the output before relying on it. If your voice memos contain other people's voices or personal data, you are responsible for having a lawful basis to record and process that content (see the Terms of Service).

#### 13. Changes to This Privacy Policy

We may update this Privacy Policy to reflect changes in the App or in applicable law. We will update the "Last Updated" date above, and where a change is material — for example, if we ever introduce analytics, a backend, or new data processing — we will make the change prominent within the App before it takes effect.

#### 14. Contact Us

Provider / Controller: Dr. Yulia Rönsch — peal-tables.3v@icloud.com — +49-177-4901659 — Kirchenstrasse 2, 82194 Gröbenzell, Germany. We aim to respond within 30 days.
