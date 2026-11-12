# PrettyMD Privacy Policy

**Last updated:** Nov 12, 2026
**Applies to:** PrettyMD version [0.7.3]

PrettyMD is a Chrome extension that displays local Markdown (`.md`, `.markdown`) and plain-text (`.txt`, `.log`) files as readable pages and lets you edit them.

## Summary

PrettyMD processes your documents locally to display and edit them. It does not upload your documents and includes no analytics, advertising or telemetry. Online images referenced in a document are loaded from their hosting websites, which then receive the request.

## Your documents

- PrettyMD reads and processes documents **locally in your browser** to display them and, if you choose, to let you edit them.
- Plain-text files (`.txt`, `.log`) open as plain text. If you choose **View as Markdown**, PrettyMD formats that file as Markdown in the current tab only, still locally.
- PrettyMD **does not upload your documents** to the developer or to any other service.
- PrettyMD includes **no analytics, tracking, advertising or telemetry**.

## Unsaved edits

Edits you make are held only in the current page. If you close or leave the page without saving, they are lost. PrettyMD does not keep backups or drafts elsewhere.

## Settings

PrettyMD stores these preferences using Chrome's local extension storage (`chrome.storage.local`):

- the Render on/off switch
- your theme (system, light or dark)
- whether Contents (the table of contents) is open
- whether Wrap lines is on for plain-text files

It also stores one internal flag used to reopen the welcome page after you turn on file access. None of these contain document content or personal information. They stay on your device, are not synced across devices, and are deleted when you uninstall PrettyMD.

Your choice to view a plain-text file as plain text or as Markdown applies only to the current tab and is not stored.

## Online images and links

- If a document shown as Markdown references an online image (for example, `https://example.com/image.png`), your browser requests it from that website, just as with any web page. The website receives the image's address, your IP address and browser details, and handles them under its own privacy policy. PrettyMD does not control or receive this information.
- Images on plain `http:` addresses are loaded without encryption, so the request can be seen on the network.
- Following a link in a document to a website opens that website, like any link.
- Plain-text files shown as plain text load no images or other external content.
- All of PrettyMD's own code, fonts and libraries are bundled inside the extension. It loads no code from remote servers.

## Saving files

- PrettyMD writes files **only when you choose to save**.
- The first time you save, Chrome's Save dialog suggests a copy that keeps the original extension and its case (for example, `notes (edited).md` or `app (edited).LOG`). You can choose any name or location.
- While the tab stays open and Chrome's permission lasts, later saves normally write to the file you chose without asking again. Reloading or closing the tab forgets that choice.
- If saving to a file isn't possible, PrettyMD offers a **Download copy** button; a download only starts when you click it.
- Files you save remain on your device after you uninstall PrettyMD.

## Permissions

- PrettyMD requests only the `storage` permission, to remember the settings listed above.
- It runs only on local file pages (`file://`), which requires Chrome's **Allow access to file URLs** switch. On local files it doesn't support, it does nothing.
- It has no access to websites.

## Limited use

PrettyMD's use of information complies with the [Chrome Web Store User Data Policy](https://developer.chrome.com/docs/webstore/program-policies/user-data-faq), including the Limited Use requirements.

Any user data PrettyMD handles is used only to provide its disclosed functionality: displaying, editing and saving documents, and remembering your settings. It is not sold, not used for purposes unrelated to that functionality, and not used to determine creditworthiness or for lending purposes. PrettyMD does not transfer data to third parties; the only outside requests are the image loads described in *Online images and links*, which your browser makes to the image's host.

## Children

PrettyMD collects no personal information from anyone, including children.

## Changes to this policy

If PrettyMD's features or data handling change, this policy will be updated at this page with a new "Last updated" date.

## Contact

If you have questions about this policy or PrettyMD, email **bwiriyapong@gmail.com**.
