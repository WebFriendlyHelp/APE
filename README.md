# Accessible Phone Extractor (APE)

Read and archive your iPhone messages, accessibly. Called the
Accessible Conversation Extractor (ACE) until November 2026.

APE is a Windows desktop program from Web Friendly Help LLC. It reads a backup
of your iPhone that is already on your computer and turns the messages, calls
and voicemails into something you can actually read with a screen reader, move
through by keyboard, and export to a document you can keep.

This repository is where official APE builds are published. It carries the
downloads, the release notes and the issue tracker. It does not carry the source
code; APE is a paid, closed-source product.

## Downloads

Official builds are on the
[APE releases page](https://github.com/WebFriendlyHelp/APE/releases). Two kinds
are published for each version:

1. The installer, named like `APE-1.0.0-setup.exe`. Installs APE normally, adds
   a Start menu entry, and can be removed from Settings like any other program.
2. The portable build, named like `APE-1.0.0-portable.zip`. Unzip it anywhere,
   including a USB stick, and run it. Nothing is installed and nothing is
   written outside the folder you unzipped and your own user folder.

Every release also carries a `.sha256` file beside each download, so you can
check that what you received is what was published. APE checks this for you
automatically when it updates itself.

Current Windows builds are not code signed yet, so Windows SmartScreen or your
browser may warn you about an unrecognised publisher. Download only from the
releases page linked above.

## What APE does

- Reads an iPhone backup made by iTunes or by Finder, including an encrypted
  one, from a folder already on your computer.
- Presents conversations in a two pane window: the list of conversations, and
  the transcript of whichever one you are reading.
- Moves you through a transcript by message, by speaker, by day, by month, by
  year, or by attachment, so a long conversation is navigable rather than a wall
  of text.
- Gives every message an action menu, so you can copy it, save its attachment,
  or work with it without hunting.
- Keeps calls and voicemails on their own tabs, reachable with Control plus 1
  through Control plus 4. A voicemail's transcript is shown as text, which is
  the only part of a voicemail a deaf-blind reader can reach at all.
- Plays voice messages, converting them on demand when Windows cannot play the
  original format.
- Exports a conversation to Word, plain text or CSV, with an extraction report
  saying what was read and what was skipped.

## Your messages stay on your computer

APE reads a backup that is already on your machine and writes its results to
your own user folder. Your messages are never uploaded anywhere. The only time
APE reaches the internet is when you ask it to check for a new version, and when
it offers to fetch the media converter it needs to play certain voice messages.

## Requirements

- Windows 10 or Windows 11, 64 bit.
- A backup of your iPhone already on the computer, made by iTunes or by Finder.
  If the backup is encrypted, you will need its password.
- A screen reader if you use one. APE is built for NVDA, JAWS and Narrator, and
  follows the font size, colours and high contrast settings you have chosen in
  Windows rather than overriding them.

## Support

- Report a problem or ask for a feature on the
  [APE issue tracker](https://github.com/WebFriendlyHelp/APE/issues).
- Or write to [the Web Friendly Help support address](mailto:help@webfriendlyhelp.com).
- More about the company at [Web Friendly Help](https://webfriendlyhelp.com).

## Licence

APE is proprietary software. Copyright Web Friendly Help LLC. Downloading a
build does not grant a licence to use it; see the licence terms shipped with the
program.

APE includes third-party components under their own licences, listed in the
notices file installed alongside the program.
