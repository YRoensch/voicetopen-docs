# 8. Troubleshooting & FAQ

Messages from VoiceToPen appear briefly in the bottom-right corner of the window — green for success, red for problems.

## Problems

### "API key required"

You tried to transcribe, clean or generate without the needed key.
Click **Open Settings**, paste the key and click **Save**. See [Getting Started](01-getting-started.md#step-2-get-your-elevenlabs-api-key) for how to get one.

- Transcribing needs the **ElevenLabs** key.
- Cleaning and generating need the **Anthropic** key.

### "Transcription failed: ElevenLabs error: …"

The text after "ElevenLabs error" comes from ElevenLabs and usually says what's wrong. Common causes:

- **Invalid key** — the key was mistyped, revoked or is missing a permission. Copy it again from ElevenLabs into **Settings**; make sure the key allows **Speech to Text**.
- **Not enough credits / quota exceeded** — top up or upgrade your ElevenLabs plan.
- **Unsupported or damaged file** — convert the recording to MP3 or M4A and try again.

### "Cleaning failed" or "Generation failed: Claude 401 / 400 / 429 / 529 …"

The number tells you what happened:

| Code | Meaning | What to do |
|---|---|---|
| **401** | The Anthropic key isn't valid | Copy the key again from the Anthropic Console into **Settings** |
| **400** mentioning *credit balance* | Your Anthropic account is out of credits | Add credits under **Billing** in the Anthropic Console |
| **429** | Too many requests or a usage limit was hit | Wait a minute and try again, or check your limits in the Anthropic Console |
| **500 / 529** | Anthropic is busy or having problems | Wait a few minutes and try again |

### The buttons are greyed out

- **Transcribe** and **Run All** need an audio file in the entry.
- **Clean with Claude** and **Generate with Claude** need a transcript first.
- While a step is running, its button is disabled until it finishes.

### "Enter a prompt first"

**Run All** needs text in the **PROMPT** box. Click one of the ready-made prompts or type your own.

### The audio file won't import

Make sure it's one of the supported formats: **MP3, M4A, WAV, OGG, WEBM**. If it's a video file or another format, convert it to M4A first — for example, open it in QuickTime Player and choose **File → Export As → Audio Only**.

### Transcription or generation takes a long time

Long recordings and long texts take longer — up to several minutes for an hour of audio. Keep the app open and your Mac online until it finishes. If nothing happens for more than 10 minutes, the request times out; try again.

### The transcript is in the wrong language or full of mistakes

Choose the correct language in the **TRANSCRIPT** section (instead of **Auto**) and click **Re-transcribe**. Clear recordings with little background noise give the best results. You can also correct the transcript by hand.

### My edits disappeared

Re-transcribe, Re-clean, Generate and Run All **replace** the text of the stage they produce, including edits. See [The Writing Workflow](04-workflow-stages.md#run-all). Export or copy versions you want to keep before running a step again.

### The window closed and the app quit

That's expected — VoiceToPen has one main window, and closing it quits the app. Your work is saved. Open VoiceToPen again to continue.

## FAQ

**How much does it cost to use?**
VoiceToPen doesn't charge you for transcription or writing. Those are billed by ElevenLabs and Anthropic to your own accounts, based on how much you use them. Check their pricing pages for current rates; your usage is shown in each service's dashboard.

**Can I record directly in VoiceToPen?**
No, and that's intentional. VoiceToPen isn't a dictation tool. It's for turning recordings you've already made — with Voice Memos or any other app — into finished writing, whenever you're ready. Drag the file into the **AUDIO** section to start.

**Can I use VoiceToPen offline?**
You can open, read, edit, organize and export your entries offline. Transcribing, cleaning and generating need an internet connection.

**Which Claude model does VoiceToPen use?**
VoiceToPen uses one of Anthropic's most capable Claude models, chosen for high-quality writing. It isn't configurable.

**What languages can I write in?**
Transcription supports the languages listed in [The Writing Workflow](04-workflow-stages.md#transcript). Claude can write in many languages — just say which one in your prompt (for example, "Write the result in German").

**Can I undo?**
Text boxes support **⌘Z** while you're typing. Deleting entries or projects and re-running a step can't be undone.

**Is my writing used to train AI models?**
VoiceToPen doesn't collect your data. For how ElevenLabs and Anthropic treat API data, see their privacy policies. See also [Privacy & Your Data](07-privacy-and-data.md).

**Still stuck?** [Contact support →](09-support.md)
