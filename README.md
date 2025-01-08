# Reference Note Template
for Zotero Better Notes

## Background
Something I’ve long wanted in a reference manager is the ability to form *reference chains*, where you can easily discover what research path led you to whatever document you’re viewing.

After switching from [Mendeley](https://www.mendeley.com/reference-management/reference-manager) to [Zotero](https://www.zotero.org), seeing Zotero's [plugin](https://www.zotero.org/support/plugins) functionality, and messing with [Better Notes](https://github.com/windingwind/zotero-better-notes#readme), it looked like it might be possible, with some combination of Better Notes and [Actions and Tags](https://github.com/windingwind/zotero-actions-tags#readme), to set up the auto-reference chains I want, to where I can easily create directional links between items, using notes.

Indeed it is, and I have done so!

## Instructions
The process is as such:

1. Ensure the [Better Notes](https://github.com/windingwind/zotero-better-notes) and [Actions and Tags](https://github.com/windingwind/zotero-actions-tags#readme) Zotero plugins are installed (as this requires plugins, it can only be done on desktop, but the result will be visible on mobile (though the note links won’t function 😢)).
2. Install the “[Auto-run Better Notes template when opening an item](https://github.com/windingwind/zotero-actions-tags/discussions/108)” script.
3. Install the [Reference Note citation style](https://github.com/Calorion/zotero-better-notes-reference-note-template/blob/main/reference-note.csl)
    1. Click the “Download Raw File” button
    2. Double-click the resulting file to open it with Zotero.
4. Ensure this “Reference Note” Better Notes template is installed.
    1. Copy the [raw file](https://github.com/Calorion/zotero-better-notes-reference-note-template/blob/main/reference-note-template.html).
    2. In Zotero, choose Tools>New Template from Clipboard.
    3. The template does *not* auto-update, so be sure to Watch this repository to be notified of changes!
5. After importing a new item, or at another time when you wish to create a reference link, open (double-click) the item in Zotero.
6. When you open it, a new Reference Note will be created within the item.
    1. The first time you do this, you’ll be asked to choose the template to use. Choose “Reference Note.”
    2. Some Zotero items don’t open in Zotero. For those, you’ll have to select the item, invoke the Note menu, choose “New Item Note from Template,” then select “Reference Note” and then “Use selected items in library.”
7. Select the new note. If the new item is referenced in an existing item:
    1. Ensure the referencing item has a reference note attached (Steps 4 & 5).
    2. Click the “Link creator” icon in the note pane.
    3. Scroll left, and find the item that references this one. Select its reference note (it will have the same name as the item).
    4. Go to the “Link to” pane.
    5. In the center pane, select “Referred from” and click OK.
    6. Click the “Link creator” icon again.
    7. Ensure the same note is selected as before, and go to the “Mention in” pane.
    8. Select “References,” and click OK.
    9. Add any additional information to either note. You can click back and forth between them using the links in the notes.
    10. If the items are merely related to each other rather than referenced, substitute “Related to” for “Referred from” and “References” above.
8. If the new note is not related to an existing item, make a note of where you found the item under Notes. This is *not* for general notes on the item, just for notes on provenance and references. Use a separate note for general notes on the item.
9. (Optional) Create a Zotero relationship as well, using the “Related” section of the right pane. I’ve been doing this, but it may not be worthwhile, as it’s a mostly inferior version of the above.
10. (Optional) Add “reference” and “referenced” tags as appropriate. I’ve been forgetting to do this, and I don’t know whether it’s worthwhile.