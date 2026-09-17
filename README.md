# me MOEG

Laboratory technician by training, self-taught systems builder by compulsion.

Plan less, build more, ship what's usable. Let actual usage tell me what the project wants to become.

Most of what's below exists because I needed it. The rest exists because apparently I cannot leave a mildly inconvenient problem alone.

## what I build

**[FindOut](https://github.com/MOEG-5/FindOut-client)** — answers for questions too small to deserve opening a browser tab. Hit a hotkey, ask something or paste an image, get a short answer. Rust/Slint desktop client + PWA, with model routing and web search politely pretending not to exist. My main ongoing project.

**[D2Rcompanion](https://github.com/MOEG-5/D2Rcompanion)** — reads your Diablo II: Resurrected rune stash from a screenshot and shows what you can craft, including what you're one rune short of. Runewords, cube recipes and item lookup. Python; Linux and Windows.

**[ScrubTub](https://github.com/MOEG-5/ScrubTub)** — a desktop video catalogue with scrubbable previews, search, tags and ratings. Built with C++/Qt, SQLite and mpv for Linux and Windows. Because a folder full of filenames is only technically a media library.

**[consultant](https://github.com/MOEG-5/consultant)** — a Pi coding-agent skill for getting focused help from a stronger model when reasoning or debugging stalls. The main agent still owns implementation and verification.

Also:

- **[piwrap](https://github.com/MOEG-5/piwrap)** — my Bubblewrap sandbox for Pi on Linux. Because "please don't destroy my computer" is not a security boundary.
- **[moegpi](https://github.com/MOEG-5/moegpi)** — my shareable Pi setup: skills, Exa search, model preferences and an interactive installer.
- **[animew](https://github.com/MOEG-5/animew)** — a Linux desktop widget that tracks mpv playback and keeps MyAnimeList updated. Maximum accountability for the backlog.

## how I think about AI tooling

*(wait let me ask Codex)*

- Ground-truth context beats throwing more tokens at missing information.
- In my own testing, orchestrators with narrowly scoped workers beat open-ended agent soup. High throughput agents with a [consultant](https://github.com/MOEG-5/consultant) beat frontier orchestrators on cost and speed while maintaining a high success rate and quality.
- Tool design matters as much as model choice. Removing a dangerous capability beats asking nicely.

I mostly build AI into tools as infrastructure. Ideally you see the useful result, not how many tokens were sacrificed to obtain it.

## currently

Building FindOut, making small tools I actually use, and job hunting in Finland. Learning software engineering by accidentally needing software engineering.
