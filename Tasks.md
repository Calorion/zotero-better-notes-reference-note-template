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
- [ ] reference-note.csl lists all editors. I can't figure out how to make it use et al with editors.
- [ ] Mention something in the readme(s) about the fact that Zotero's built-in "related" function doesn't cut the mustard.
- [x] Strongly consider making this repository *only* for the csl file.
- [ ] et al isn't working properly. Items with more than one author or editor are not getting et al'd for some reason I can't determine.
    - [ ] e.g. compare
```
	{
		"id": "http://zotero.org/users/8962722/items/X3JPZUGY",
		"type": "article-journal",
		"abstract": "A copy of the manuscript can be found here (also can be found on PsychologyToday (Politics in Academia): \nhttps://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwiikOmAnL3uAhURB50JHaulCv8QFjABegQIAxAC&url=https%3A%2F%2Fosf.io%2F495nc%2Fdownload&usg=AOvVaw1izCk8sLQ3Q1GXZU-TKGjf",
		"language": "en",
		"source": "ResearchGate",
		"title": "Politics and academic values in higher education: just how much does political orientation drive the values of the ivory tower?",
		"title-short": "Politics and Academic Values in Higher Education",
		"URL": "https://www.researchgate.net/publication/319990558_Politics_and_Academic_Values_in_Higher_Education_Just_How_Much_Does_Political_Orientation_Drive_the_Values_of_the_Ivory_Tower",
		"author": [
			{
				"family": "Geher",
				"given": "Glenn"
			},
			{
				"family": "Jewell",
				"given": "Olivia"
			},
			{
				"family": "Holler",
				"given": "Richard"
			},
			{
				"family": "Planke",
				"given": "Julie"
			},
			{
				"family": "Betancourt",
				"given": "Kian"
			},
			{
				"family": "Baroni",
				"given": "Amanda"
			},
			{
				"family": "DiSanto",
				"given": "Jacqueline"
			},
			{
				"family": "Gleason",
				"given": "Morgan"
			},
			{
				"family": "Eisenberg",
				"given": "Jacqueline"
			}
		],
		"issued": {
			"date-parts": [
				[
					"2020",
					11,
					26
				]
			]
		}
	}
]
```
, which works properly, with
```
[
	{
		"id": "http://zotero.org/users/8962722/items/YXG9SEN5",
		"type": "book",
		"ISBN": "978-0-07-802591-4",
		"language": "en",
		"publisher": "McGraw-Hill",
		"title": "Fundamentals of financial accounting",
		"URL": "https://www.pdfdrive.com/fundamentals-of-financial-accounting-e186191104.html",
		"author": [
			{
				"family": "Phillips",
				"given": "Fred"
			},
			{
				"family": "Libby",
				"given": "Robert"
			},
			{
				"family": "Libby",
				"given": "Patricia"
			}
		],
		"accessed": {
			"date-parts": [
				[
					"2021",
					2,
					20
				]
			]
		},
		"issued": {
			"date-parts": [
				[
					"2015"
				]
			]
		}
	}
]
```
, which does not.