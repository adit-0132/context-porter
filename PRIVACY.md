# Context Porter Privacy Policy

Last updated: November 3, 2026

Context Porter is a browser extension that exports AI chat conversations to a file on your device and converts
them to Markdown. It has no servers, no accounts, no analytics and no tracking. **Your data never leaves your
browser except to the AI site you are already using.**

## What the extension accesses, and when

- **Your conversations** on chatgpt.com, chat.openai.com, claude.ai, gemini.google.com and grok.com, only when
  you click Export Chat, Export All Chats or Copy in the extension's popup. The extension reads them through the
  same site, using the session you are already signed in with.
- **Your ChatGPT session header.** On chatgpt.com, the extension reads the Authorization header that the site
  itself sends to its own API, so it can fetch your conversation from that same API. It is kept only in the
  extension's memory while the browser runs. It is never written to storage and never sent anywhere else.
- **Your clipboard**, only when you click Copy (to place an export on the clipboard) or Paste (to read an export
  you copied, so it can be converted to Markdown).
- **The address of the current tab**, to tell which supported AI site you are on. During Export All on Gemini,
  the extension opens your Gemini conversations one by one in that tab and then returns to where you were.

## Where your data goes

Nowhere. Exports are saved as files to your Downloads folder, or copied to your clipboard when you ask. The
extension makes no network requests except to the AI site you are on, and shares nothing with the developer or
any third party. Data is not sold, not used for advertising, and not used for any purpose other than exporting
and converting your conversations.

## What is stored, and for how long

- **Export progress** (counts such as "87/214"), in the browser's session storage while a bulk export runs. It is
  cleared when the export finishes or the browser session ends.
- **A finished bulk export**, held in the extension's local storage only until the popup packages it into a ZIP
  for download. It is then deleted.
- Nothing else is stored.

## Removing your data

Uninstalling the extension deletes everything it stored. Files you exported are yours, and you can delete them
like any other file.

## Open source

The complete source code is public: https://github.com/adit-0132/context-porter

## Contact

Questions or concerns: open an issue at https://github.com/adit-0132/context-porter/issues

Context Porter is an independent project and is not affiliated with OpenAI, Anthropic, Google or xAI.
