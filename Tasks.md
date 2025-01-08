# Tasks

- [x] After learning JavaScript, modify the template such that it will show the title in *[bibliography format](https://github.com/windingwind/zotero-better-notes/discussions/1246)* (preferably in the currently-selected style in Zotero, but I don’t think that’s possible) rather than simply the title of the item.
    - Why? Because I don't want to depend on the Zotero note links to work indefinitely. If all I have is the reference and the note, with no other context, I want to have a reasonable chance of finding the reference again. Besides, it's useful to have at least a little more context than just the title to help remember what the reference is without having to mouseover or click through.
- [ ] If [windingwind](https://github.com/windingwind) fixes the @use-refresh title issue, perhaps change the template to update the title and metadata section at will. \\ He’s not going to fix it, but there’s a [workaround](https://github.com/windingwind/zotero-better-notes/issues/1247#issuecomment-2571755724). 
- [ ] It’d be great to automate the whole process in Step 7. I wonder if there’s a way to do it with Actions and Tags?
- [x] This doesn’t generate titles for [Cases](zotero://select/library/items/DDKUPSGQ). Fix.
- [ ] “References” and “Referenced in” are problematic labels. The purpose of these are to show *where I found the sources*, in order to establish the research chain, *not* to list every paper you happen to have (or that exists!) that it’s referenced in or that it references. Better labels would be better.
    - [x] How about “Referred from”? That’s a step forward.
- [x] Create new Style, based on [American Journal of Sociology](https://www.zotero.org/styles/american-journal-of-sociology), just for this purpose.
    - [x] Probably want to change it so that the title comes first, given that BN cuts off text that's too long when you create a link between notes.
- [ ] Move this list to Issues(?)
- [ ] Consider removing City (at least) and Publisher from reference-note.csl.
    - [x] City done.