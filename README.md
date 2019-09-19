# Open Source Games

**[Dynamic HTML table](https://trilarion.github.io/opensourcegames/)** of the entries / Development **[Blog](https://trilarion.blogspot.com/search/label/osgames)** / **[Statistics](statistics.md#statistics)**

[comment]: # (start of autogenerated content, do not edit)
**[All entries](games/tocs/_all.md#All)** (1048)

By category: **[Action](games/tocs/_action.md#action)** (186), **[Adventure](games/tocs/_adventure.md#adventure)** (28), **[Arcade](games/tocs/_arcade.md#arcade)** (60), **[Board game](games/tocs/_board-game.md#board-game)** (9), **[Card game](games/tocs/_card-game.md#card-game)** (2), **[Educational](games/tocs/_educational.md#educational)** (5), **[Framework](games/tocs/_framework.md#framework)** (67), **[Game engine](games/tocs/_game-engine.md#game-engine)** (71), **[Library](games/tocs/_library.md#library)** (28), **[Music](games/tocs/_music.md#music)** (10), **[Platform](games/tocs/_platform.md#platform)** (33), **[Puzzle](games/tocs/_puzzle.md#puzzle)** (81), **[Remake](games/tocs/_remake.md#remake)** (461), **[Role playing](games/tocs/_role-playing.md#role-playing)** (149), **[Simulation](games/tocs/_simulation.md#simulation)** (77), **[Sports](games/tocs/_sports.md#sports)** (18), **[Strategy](games/tocs/_strategy.md#strategy)** (221), **[Tool](games/tocs/_tool.md#tool)** (22), **[Visual novel](games/tocs/_visual-novel.md#visual-novel)** (4)

By platform: **[Windows](games/tocs/_windows.md#windows)** (276), **[Linux](games/tocs/_linux.md#linux)** (252), **[macOS](games/tocs/_macos.md#macos)** (147), **[Android](games/tocs/_android.md#android)** (47), **[iOS](games/tocs/_ios.md#ios)** (5), **[Web](games/tocs/_web.md#web)** (48)

[comment]: # (end of autogenerated content)

A list of open source games sorted by genre. The projects are at least in beta stage with a code basis that builds
into an executable demo. The code must be under a [FOSS](https://en.wikipedia.org/wiki/FOSS) license that allows
modification and sharing by others. For each entry, relevant information is collected regarding code repositories,
download possibilities and build instructions.

Similar collections include [Open Source Clones](https://github.com/opengaming/osgameclones) of popular games;
Popular games, add-ons, maps, etc. [hosted on GitHub](https://github.com/leereilly/games); [List of open-source video games](https://en.wikipedia.org/wiki/List_of_open-source_video_games) on Wikipedia or the [LibreGameWiki](https://libregamewiki.org/Main_Page).

## Contribute

To add or modify entries, please use the [Issue tracker](https://github.com/Trilarion/opensourcegames/issues),
or fork this repository and submit a pull request.

### Adding a new entry

Checklist for a new entry

- Must be a game, a game maker, a game's tool, a framework or a library, used in games
- Must be under a FOSS license (GPL, MIT, ...) and code must be available
- Must be mature or at least in beta (with an executable demo)
- Active or inactive is irrelevant.

All entries are stored as [markdown](https://en.wikipedia.org/wiki/Markdown) text with some specific conventions.
Adding a new entry is as easy as modifying the [template](games/template.md) and adding the modified markdown file in a subdirectory of [games](games).

Description of the fields in the template. Comments start with "//".

<pre>
# {NAME} // name of the game

_{Description}_ // single description line (typically taken from about page of game)

- Home: {URL} // project main site(s) (most significant first)
- Media: {URL} // (optional) links to wikipedia and other significant mentions
- State: {XX} // one of {beta, mature} and optional "inactive since YEAR"
- Play: {URL} // (optional) link(s) to online play possibility
- Download: {URL} // (optional) link(s) to download binary (or source) releases
- Platform: {XX} // (optional) list of supported platforms {Linux, Windows, macOS, Android, ..}
- Keywords: {XX} // list of tags describing the game, first tage is the main category tag
- Code repository: {URL} // code repositories (most significant first)
- Code language: {XX} // programming language(s) used 
- Code license: {XX} // license of the code, use "Custom" with comment in () if the license is project-specific
- Code dependencies: {XX} // (optional) important third party libraries / frameworks used by the project
- Assets license: {XX} // (optional) license(s) of the assets (artwork, ..)

// whatever you want to put here

## Building

- Build system: {XX} // (optional) typically one of {CMake, Autoconf, Gradle, ..}
- Build instructions: {URL} // (optional) link(s) to build instructions offered by the project

// whatever you want to put here
</pre>

- If there are multiple links, licenses, ... separate them by comma.
- The same link can be assigned to different fields (home could also be the code repository, etc.).
- Put comments in "()" parentheses (do not put commas in comments).
- Remove lines with fields that do not apply to the project or where information is not available otherwise.
- Status active is implied/default unless the optional "inactive since" is present
- All lines starting with '- ' are considered fields.

Help: [MarkDown Help](https://help.github.com/articles/github-flavored-markdown), [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## Background

I love open source projects and games and I am interested in learning more about building systems.
I see the following benefits of having this database.

- General information about open source games
- Possibility of improving build instructions on the projects side (not all projects actually have build instructions)
- Revival of abandoned games that do not build anymore
- Conversion of old repository formats like CVS to Git

## Disclaimer
 
No warranty whatsoever of the information presented herein for any purpose. There could (will) be errors in here.

## License

See [LICENSE](LICENSE). This work is dedicated to the public domain by waiving all rights to the work worldwide under copyright law, including all related and neighboring rights, to the extent allowed by law.

Additionally, the content is also licensed (multi-licensed) under the following other licenses: [WTFPL](http://www.wtfpl.net/txt/copying/), [CC-BY-3.0](https://creativecommons.org/licenses/by/3.0/),
[GFDL 1.3](https://www.gnu.org/licenses/fdl-1.3.txt) and given to the Public Domain (wherever it exists and to the maximum possible extent).

I hope that this does the trick. But really, just use the content however you like.
