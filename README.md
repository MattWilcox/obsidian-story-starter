This project is a starter Obsidian Vault for use with the Obsidian.md application, aimed at helping you to write fiction stories. Or D&D Campaigns. That sort of thing.

Once you download it and open it in Obsidian I'd suggest you start familiarising yourself by going and reading the first scene in this bare-bones example story... [[Story One/Scenes/A Discovery|A Discovery]]

Before you download anything though I rather suspect you'll want a bit more context:

This vault doesn't rely on community plugins, and the methodology in it is suggestion rather than strict system.

More than anything though: this is just a starter Vault that I find works for me. It's scaffolding when starting a new project, because "I'll likely want to think about _these sort of things_ and _in this sort of way_". It's not meant to be restrictive or prescriptive. Just a guide to adapt.

For the sake of making it public, I've added "an example story" aimed at people not myself (hi, that's you), in an attempt to get what my brain already knows into your brain, which doesn't. Those "documentation story notes" are all tagged with 'deleteme'. You can see them all here, in this handy-dandy inline-search query (the sort of thing you'll find useful as you write stories and want to keep track of "stuff" - Obsidian can automate a lot of that...):

```query
tag:#deleteme
```

I didn't have to write that list - Obsidian just found all the notes I added the tag to. Nice hey. I suggest you delete those notes in that list before starting your project. And then delete this note once that list is empty. Well, once you've glanced over them and got the gist of things.

# Requirements

- [Obsidian](https://obsidian.md) - the note-taking app. 
	- It's free.
	- It uses standard MarkDown files so there is no vendor lock-in.
	- It's cross-platform, including phones.

# Nice to have

If you want it to look like I prefer, you will need:

- [Monaspace FontFamily](https://monaspace.githubnext.com)
	- Free. Install them onto your Operating System.
- [Catppuccin Theme](https://github.com/catppuccin/obsidian)
	- The theme I use for Obsidian's appearance.

You absolutely do not need to. The defaults are fine. But if you do, here's how...

## Obsidian Appearance Settings

Open: `Settings` > `Appearance`

- Themes:         `Catppuccin`
- Interface Font: `Monaspace Argon Var`
- Text Font:      `Monaspace Xenon Var`
- Monospace Font: `Monaspace Krypton Var`

# Using this vault

It's organised in such a way that you could write multiple different stories in it, and still have everything available for if your stories ever intersect; e.g., you could write Book One and Book Two, which share some of the same characters and locations.

Or you could just write one story and make a new vault for another story - just remember that you can't link between vaults; so if you end up wanting to reference Character One from Story One in Story Two... you can't if they're in different vaults.

## The methodology

I don't like writing one big long document as a story. It's hard to organise and keep track of things. If you want to move things around you've got to cut-and-paste big chunks of text around a giant document and that can be fragile and confusing.

Likewise I don't like having one folder on my computer with a bunch of files in it, because they're a pain to work with and need a ton of windows open at once, etc.

That's why I don't use Word or whatever. I use Obsidian and keep everything in it, because Obsidian is _extremely_ good at organising and searching related written content.

I write _scenes_ as individual notes. Scenes are things I can assign `properties` to - like "who's POV is this scene? Where does it take place? Which characters are in the scene? On what date does the events of the scene happen?" and then I can use Obsidian's built in tools to keep track of those things. I then compile scenes into chapters using `Embeds`. Meaning I can move scenes around accurately and quickly - work on them atomically but still seamlessly see them as part of a larger document. 

Do I need to know what scenes Character Bob is actually in? Easy, it's tracked already in his Character Sheet with a simple embedded Search Query. Did Bob ever meet Jo? In which scenes? Easy to find out! It's all there (assuming you add the appropriate properties to the scene), without needing to go read or do laborious text searches over entire book-length documents. This is what Obsidian _is for_. Exposing relations between notes.

## The vault structure

Folders that start with an underscore are _meta_ folders; that is to say they do not form part of the story itself, but hold files _relating to it_. The vault is organised into the following folders.

### `_media`

This is where all images used in any pages are stored. It's just handy to have media stored in one place. You might want a photo of an actual real-world sword to reference inside a Research Note on the topic of swords, for example.

###  `_meta`

This is where any files that are not part of the story belong. For example, you could put any notes to yourself in here, or group your research notes in here. e.g.,

- Details about real world swords that are a basis of your in story ones; weight, care steps, a photo, etc.
- Research about common illnesses in medieval times, and their supposed cures - that you might want to reference and adapt for your own world.

### `_templates`

Obsidian templates to allow the quick creation of note _types_ as you write. For example, Character notes, or Location notes, with pre-scaffolded out sections and properties for you when you need a new one.

### Characters

> This is where all of your characters should be stored.

One Note per character is all I usually do, with stuff I as the author want to remember and know about my concept of them, which I can refer back to as I write.

### Locations

> This is where all of your locations should be stored.

One Note per location is all I usually do, with stuff I as the author want to remember and know about it, which I can refer back to as I write.

### Organisations

> This is where all of your in-world organisations should be stored.

Guess what? One Note per organisation is all I usually do, with stuff I as the author want to remember and know about my concept of them, which I can refer back to as I write. "What was the name of the guild responsible for wagons again? And who was it heading up the organisation? Ah yes..."

### Scenes (named)

> Components of the story itself, split into individual named scenes.

Not numbered, because the order of scenes is likely to change as you progress on the story. You'll likely want to try out different ways of organising the scenes as part of the tory flow. So rather than just having one huge long document, I prefer to write atomic scenes and then compile those into a Chapter using Obsidian's "Embed" feature...

### Chapters (named)

> Embeded compilations of Scenes to form a chapter

Again, not numbered because you may also want to re-arrange chapters as you work, to facilitate different story flow. Instead, I use titles for the chapter.

No actual writing is in these Notes, just Obsidian's feature of embedding other Notes - this then allows you to drag-and-drop re-arrange scenes within a Chapter (by using Source view and moving the embed lines around, before going back to Reading view).

### Story Manuscript

> Embeded Chapters, in order, to form the final story

Again, no actual text is in the Story note - just Embeds. Uses the same logic as Chapters described above.
