# Reference Note Template
for Zotero Better Notes

## Background
Something I’ve long wanted in a reference manager is the ability to form *reference chains*, where you can easily discover what research path led you to whatever document you’re viewing.

After switching from [Mendeley](https://www.mendeley.com/reference-management/reference-manager) to [Zotero](https://www.zotero.org), seeing Zotero's [plugin](https://www.zotero.org/support/plugins) functionality, and messing with [Better Notes](https://github.com/windingwind/zotero-better-notes#readme), it looked like it might be possible, with some combination of Better Notes and [Actions and Tags](https://github.com/windingwind/zotero-actions-tags#readme), to set up the auto-reference chains I want, to where I can easily create directional links between items, using notes.

Indeed it is, and I have done so!

## Instructions
The process is as such:

1. Install [Zotero](https://www.zotero.org) if you don't already have it.
2. Install the [Better Notes](https://github.com/windingwind/zotero-better-notes) and [Actions and Tags](https://github.com/windingwind/zotero-actions-tags#readme) Zotero plugins (as this requires plugins, it can only be done on desktop, but the result will be visible on mobile (though the note links won’t function 😢)).
3. Install the “[Auto-run Better Notes template when opening an item](https://github.com/windingwind/zotero-actions-tags/discussions/108)” script.
4. Install the [Reference Note citation style](https://downgit.github.io/#/home?url=https://github.com/Calorion/zotero-better-notes-reference-note-template/blob/main/reference-note.csl). (*I promise this is safe! This link goes to a service to download files from GitHub, and some people have reported it as malicious because they downloaded viruses through it. This is not a virus! It is a Zotero citation style!*) 
    1. Open the zip file.
    2. Double-click on “reference-note.csl” to install it in Zotero.
5. Install this “Reference Note” Better Notes template.
    1. Copy the [raw file](https://github.com/Calorion/zotero-better-notes-reference-note-template/blob/main/reference-note-template.html).
    2. In Zotero, choose Tools>New Template from Clipboard.
    3. The template does *not* auto-update, so be sure to Watch this repository to be notified of changes!

For usage, see the “Use” section of the [Better Notes Discussion](https://github.com/windingwind/zotero-better-notes/discussions/1258) for Reference Note.

## Change Log

2025-11-09T11:55R Changed citation style to use short titles
2025-11-09T12:20R Removed series information for non-journal articles
