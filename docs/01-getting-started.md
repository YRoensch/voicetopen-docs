# 1. Getting Started

VoiceToPen turns your spoken words into polished writing. You import an audio recording you made earlier, the app transcribes it, cleans up the transcript, and then rewrites it into the kind of text you ask for — a blog post, a book chapter, tidy notes.

VoiceToPen is built for an organized workflow: record your ideas whenever it suits you, collect the recordings, and turn them into text later. It deliberately has no recording feature of its own and is not a live dictation tool.

To do this, VoiceToPen uses two online services that you sign up for yourself:

| Service | What it does in VoiceToPen |
|---|---|
| **ElevenLabs** | Turns your audio into a text transcript |
| **Anthropic (Claude)** | Cleans the transcript and writes the final text |

You pay these services directly for what you use. VoiceToPen itself never sees your recordings, your text, or your keys — see [Privacy & Your Data](07-privacy-and-data.md).

## What you need

- A Mac running **macOS 14.6 (Sonoma) or later**
- An internet connection
- An **ElevenLabs API key**
- An **Anthropic API key**

## Step 1: Install VoiceToPen

1. Open the **App Store** on your Mac and search for **VoiceToPen**.
2. Click **Get**, then **Install**.
3. Open VoiceToPen from Launchpad or your Applications folder.

## Step 2: Get your ElevenLabs API key

1. Go to [elevenlabs.io](https://elevenlabs.io) and create an account (or sign in).
2. Open your account's **API Keys** page (in the developer/profile settings).
3. Create a new key. If you're asked to choose permissions, make sure **Speech to Text** is allowed.
4. Copy the key. You'll paste it into VoiceToPen in Step 4.

> **Tip:** Transcription uses ElevenLabs credits. Check that your ElevenLabs plan includes enough for the length of audio you plan to transcribe.

## Step 3: Get your Anthropic API key

1. Go to [console.anthropic.com](https://console.anthropic.com) and create an account (or sign in).
2. Add a payment method or buy credits under **Billing** — the API won't work without them.
3. Open **API Keys** and click **Create Key**.
4. Copy the key. It's shown only once, so paste it somewhere safe or straight into VoiceToPen.

> **Note:** An Anthropic API key is different from a Claude.ai chat subscription. A Claude Pro or Max plan does not include API access — you need a key from the Anthropic Console.

## Step 4: Enter your keys in VoiceToPen

1. In the bottom-left corner of the VoiceToPen window, click **Settings** (the gear icon).
2. Under **API Keys**, paste your ElevenLabs key into the **ElevenLabs** field.
3. Paste your Anthropic key into the **Anthropic** field.
4. Under **Transcription**, choose your **Default Language** — the language you usually speak in your recordings. Choose **Auto-detect** if it varies.
5. Click **Save**. You'll see "Settings saved ✓".

Your keys are stored securely in the macOS Keychain on your Mac.

## A quick tour of the window

- **Sidebar (left):** your projects and the entries inside them, the **Entries** / **Progress** switch at the top, and **Settings** at the bottom.
- **Main area (right):** the entry you're working on, or the Progress table.

> **Good to know:** VoiceToPen has a single main window. Closing it quits the app. Everything you do is saved automatically, so nothing is lost.

**Next:** [Quick Start →](02-quick-start.md)
