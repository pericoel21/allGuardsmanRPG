# AllGuardsman RPG
This is *All Guardsman Role Playing Game*, a Tabletop Roleplaying System designed to play in a grimdark science-fantasy setting with lots of humor.

> If you need a quick start on the rules, go to [[players-guide|Player's Guide]].

## The objectives of this system
### Old School gameplay
- A solid but minimalist system that allows for GM rulings.
- A game loop that stays always on turns.
- The system specifically supports a west-marches style of play, where players' ambitions guide the discovery of the world.
### Modern improvements
- Simple d12 Black Jack system.
- One action, one roll: the basic roll gives all the information needed.
- A roll always matters; bad things can happen with any failed check!
- Clocks help keep track of events, threats and statuses with ease.
## Setting
> *"Enough head-cannon to surprise veterans, and so little that players' ideas can be added on the fly."*

- The setting is heavily inspired by the lore of some famous sci-fi wargames.
- The lore is supported in the mechanics, but only the broader strokes:
	- A demigod Emperor on his throne, far away.
	- A parallel dimension created by the emotion of people, populated by horrors.
	- A faction that prays to the soul of machines.
	- A galaxy always in war.
	- Some fantasy tropes in space, with a twist.
- The ideas and opinions of the GM should be always easy to implement.
	- The setting is vague enough that any GM can re-write parts of the cannon without contradicting any lore written in allGuardsmanRPG.
	- Plus, the mechanics will probably support the re-write.
- If any section of the system talks about the setting, it will give ideas, use examples to explain mechanics or help the reader create their own setting.

# How to use this repo
I am creating this repository by pushing my local Obsidian vault. This means:
- The repository is mostly readable within GitHub, because it uses markdown formatting. **All the vital information is readable in GitHub.**
- **GitHub lacks some of the quality of life features** that Obsidian does.

By far, the **biggest problem** with reading Obsidian files in GitHub is that **links don't work**. **Instead of clean links** you can click on, you will see **text similar to**: `[[example-page|Example Page]]`. Don't worry! The first name is the name of the page (in this case, `example-page`) and **you can simply navigate to it manually**, inside the folder structure of this repo.

## Folder Structure
The repository is divided in several folders that contain all the info structured logically:
- `root` (that is, files outside any folder): **Stuff that is general to the system**. It can be a bit technical.
- `_utility` contains **technical stuff**. This is where code goes, and excel files with lots of data. The images seen on the notes are actually links to an image file inside `_utility/media`.
- `lore`: Here I place **lore-related notes**.
- `system`: The meat and potatoes of the repository. Here I place **all the stuff needed for the actual running of the game**:
	- `core-mechanics`: The **system itself**. Here are all the mechanics that make everything work.
	- `gm-section`: Notes on how to **prep, run and handle the system from a GM's perspective**.
	- `objs`: **Database** of bits and bobs. Here is where I'll place every Item, Feat, Background option...
	- `players-guide`: Notes intended to **guide players**.
- `system-dev`: Like a devlog. Here I document my **thoughts on building the system** and the **reasoning behind design decisions**.

## The best possible experience
If you want the **best possible experience**, pull (download) this repo into your local files and open it with Obsidian. 

### Plug-ins
The only plug-in you need to see everything I see is **Dataview.** It shows databases made from other pages.

Some other recommended plug-ins I use:
- **Folder Notes:** for a small QoL improvement, where you can click a folder to open a note with the exact same name as the folder. This is a behavior that imitates Notion.
- **Templater,** only if you want to work in the repository as I do. It allows you to create or apply templates to notes. I use the templates in `_utility/templates`.

### Some extra stuff
I'm using some other pieces of software to make things work:
- I use OpenOffice sheets to catalog all types of stuff. You can find them in the `_utility` folder (they open perfectly on Google Drive or Excel).
- When I finish them up to their alpha version, run some magic code to create markdown pages for each item, tag, etc; meaning that you'll be able to access them from GitHub too.
- If you'd were to create your own tables... Don't worry, I'll share the magic code too! It is Python and once I have the final scripts, I'll create a `_utility/py` folder for them.