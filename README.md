# The Star Smuggler Project

**_Star Smuggler_** is solitaire role playing game, of the paper/pencil variety.
You play a Han Solo-like character, trying to get rich, and stay alive.

**_Star Smuggler_** was designed by Dennis Sustare, and published by 
Dwarfstar Games in 1982. It is currently available as 
[free-to-download PDFs](http://dwarfstar.brainiac.com/ds_starsmuggler.html).

Despite the free download, note that _Sustare retains the copyright_. It is not 
public domain.

The [BGG page](https://boardgamegeek.com/boardgame/1699/star-smuggler) hosts an 
authorized re-design by Todd Sanders.

This project will gradually convert **_Star Smuggler_** to an electronic 
format. The plan of action is something like:

1. ~~Convert rules to markdown~~
1. Convert rules to json
1. Generate cross-linked html from the json
1. Automate die rolls in html rules
1. Create vector graphics
1. Record keeping system
1. Event log
1. Land combat sub-game
1. Space combat sub-game

If I get all the way through the list, I'll go the last mile and put together a 
web page that lets me play the game on a phone or tablet.


## Work Notes

### 2016-03-25

The markdown rules now have cross-ref links for all rules and encounters.


### 2016-03-25

Wow, it took _way_ more effort to convert to markdown than I anticipated. 
Converting wargame rules to markdown is not to be taken lightly.

That said - mission accomplished! Rules are now in clean markdown format.

The markdown file is adapted from the Todd Sanders' pdf files. Minor edits were 
made: Typos were fixed. Some text was expanded for readability. Some adaptations
were made to allow for markdown.

I will freeze work on ```rules.md```. Next up: begin work on a json file. 
