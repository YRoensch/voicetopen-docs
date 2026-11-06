# Release Notes

This guide always describes the **current App Store version** of VoiceToPen, shown at the top of every page. If your app is older, update it in the App Store (**App Store → Updates**) to get the features described here.

## Version 1.1

**New**

- VoiceToPen **keeps the original transcript and cleaned text** next to your edited versions. An **Edited | Original** switch shows the original, and **Restore Original…** brings it back. **Re-transcribe** and **Re-clean** now ask before replacing your text.
- **Record** straight into an entry: click **Record** in the **AUDIO** section, then **Stop**. See [Recording in VoiceToPen](04-workflow-stages.md#recording-in-voicetopen).
- **VoiceToPen for iPad** (iPadOS 17 or later). *Pending App Store approval: version 1.1 is available for Mac now, and the iPad version follows once Apple approves it.* It's the same App Store app as on the Mac, so you'll get it from the App Store on your iPad with the same Apple Account. Your Mac and your iPad each keep their own projects; they aren't synced. See [Using VoiceToPen on iPad](10-ipad.md).
- **Share recordings from Voice Memos:** choose **Share → VoiceToPen** on a recording, and it becomes a new entry in the **From Voice Memos** project, without leaving Voice Memos. See [Recordings from Voice Memos](03-projects-and-entries.md#recordings-from-voice-memos).
- **Drag entries** in the sidebar onto another project to move them.
- An **ⓘ button** next to each API key field in **Settings** shows how to get an ElevenLabs or Anthropic key and opens the page where you create it.
- **Share** the result directly to Mail, Messages, Notes, AirDrop or another app with the new **Share** button in the **RESULT** section and in the full-text window. It sends clean plain text without Markdown marks, so social posts look right; **Copy** still gives you Markdown.

**Improved**

- **Run All** keeps an existing transcript (including your edits) and asks before it replaces anything. Choose **Re-transcribe & Run** to transcribe the audio again.
- **Run All** uses the cleaning instructions currently in the **CLEAN** section.
- **Deleting several entries** at once now asks for confirmation.
- **Exports** of a project or a selection skip entries that have no content at the chosen stage, and tell you how many were skipped.
- Your **prompt** is saved automatically while you type, so switching to another entry no longer loses it.
- The **Result** preview grows with the text, so you can read more without scrolling inside a small box.
- **Settings:** clearer layout for the API key fields.
- An **Export** button in the **RESULT** section saves the result as a Markdown file in one click.
- **Generate with Claude** now sits next to the **PROMPT** label, like **Re-transcribe** and **Re-clean** in their sections.

**Fixed**

- The transcript and cleaned text are **read-only while a step is running**, so an edit made during cleaning or generating can no longer be mixed up with the text being processed.
- Cleaning or generating from a **very short transcript** no longer returns a reply from Claude ("I don't see any transcription…") instead of the cleaned text.
- Cleaned text and results in **Russian and other non-Latin languages** no longer come out as garbled characters.
- The title at the top of an entry now updates right away when you rename the entry from the sidebar.
- **Run All** no longer reports success when cleaning or generating failed, for example because an API key is missing.
- The full-text window no longer sometimes shows "This entry is no longer available" when it opens.

## Version 1.0.1

The first App Store release of VoiceToPen.

- **Import audio** recorded with any app: MP3, M4A, WAV, OGG and WEBM, by drag and drop or **Browse for file…**
- **Transcribe** recordings with ElevenLabs, in 15 languages or with automatic language detection
- **Clean** transcripts with Claude: removes filler words, timestamps and repeated phrases, with editable cleaning instructions
- **Generate** polished text with Claude from your own prompt or one of four ready-made prompts, shown as a formatted preview or as editable Markdown
- **Run All** to transcribe, clean and generate in one step
- **Projects and entries** to organize your work, with rename, move, mark as done and bulk actions
- **Progress view** showing the status of every entry at a glance
- **Export** transcripts, cleaned text and results as Markdown — one entry, a selection or a whole project — and save copies of your audio
- **Your own API keys**, stored in the macOS Keychain; recordings and texts stay on your Mac
- Closing the main window quits the app; everything is saved automatically
