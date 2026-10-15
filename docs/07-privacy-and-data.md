# 7. Privacy & Your Data

VoiceToPen is a **local-first** app. There is no VoiceToPen account, no VoiceToPen server, and no analytics. Your recordings and texts are stored on your Mac.

## What leaves your Mac — and where it goes

Data is sent only when you use a feature that needs it, and it goes **directly from your Mac** to the service, using **your own** API key:

| When you… | What is sent | Sent to |
|---|---|---|
| Click **Transcribe** (or Run All) | The entry's audio file and the chosen language | ElevenLabs |
| Click **Clean with Claude** | The transcript and your cleaning instructions | Anthropic |
| Click **Generate with Claude** | The cleaned transcript (or the transcript) and your prompt | Anthropic |

Nothing is sent when you simply open, edit, organize or export entries.

How ElevenLabs and Anthropic handle your data is governed by their own terms and privacy policies, which you agreed to when you created your accounts with them.

For full details, see the [VoiceToPen Privacy Policy](legal/privacy-policy.md).

## Your API keys

Your ElevenLabs and Anthropic keys are stored in the **macOS Keychain** on your Mac — the same secure storage macOS uses for passwords. They are only ever sent to the service they belong to.

**To change a key:** open **Settings**, replace the key and click **Save**.
**To remove a key:** open **Settings**, clear the field and click **Save**.

If you think a key has been exposed, revoke it in your ElevenLabs or Anthropic account and create a new one.

## Where your data is stored

All projects, entries, transcripts, results and audio copies are stored in this folder:

```
~/Library/Containers/com.yuliaroensch.voicetopen/Data/Library/Application Support/VoiceToPen/
```

To open it: in Finder, choose **Go → Go to Folder…** (⇧⌘G), paste the path above and press **Return**.

> Please don't edit or rename files in this folder by hand — it can make entries disappear from the app. Use VoiceToPen to make changes, and [Export](06-exporting.md) to get copies of your work.

## Backing up

- **Time Machine** backs up this folder automatically, along with the rest of your home folder.
- For a manual backup, quit VoiceToPen and copy the `VoiceToPen` folder above to a safe place.
- For a readable copy of your writing, [export your projects](06-exporting.md) as Markdown.

API keys live in the Keychain, not in this folder, so they aren't part of a folder backup — you can always create new keys in your provider accounts.

## Deleting your data

- **Delete an entry or project** in the app. Deletion is permanent: it removes the files from your Mac and they don't go to the Trash.
- **Remove everything:** delete the app, then delete the folder shown above. Also remove your keys from **Settings** first (clear both fields and click **Save**) if you want them gone from the Keychain.

Data you sent to ElevenLabs or Anthropic is managed by those services — see their privacy policies or account settings.

**Next:** [Troubleshooting & FAQ →](08-troubleshooting.md)
