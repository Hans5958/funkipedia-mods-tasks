# {{SongInfo}} Update

**Description**: Merge {{SongInfo}} with {{SongInfoGradient}} and {{SongInfoLoud}}

**Status**: ![status-wait] Waiting

**Pages checked**: 1981

**Auto/manual**: Manual (template making), automated (updating pages)

## Background

The wiki has {{SongInfo}}, the template for songs, but spin-offs/variations exists to support other use cases. {{SongInfoGradient}} is the most used one, with additional support for gradient and multiple colors, and {{SongInfoLoud}} is used to warn readers regarding the song.

This task has two goals:
- To update the base {{SongInfo}}, merging {{SongInfoGradient}} and {{SongInfoLoud}} in the process, achieving parity and consistency, and other substantial updates.
- To edit the pages using the templates. This includes parameter name changes for clarity and template name change. This is a must for {{SongInfoLoud}}, and suggested on the others.

## Links

- [User:Hans5958/SongInfo](https://fridaynightfunking.fandom.com/wiki/User:Hans5958/SongInfo)
- [User:Hans5958/SongInfo/testcases](https://fridaynightfunking.fandom.com/wiki/User:Hans5958/SongInfo/testcases)
- [User:Hans5958/SongInfo/doc](https://fridaynightfunking.fandom.com/wiki/User:Hans5958/SongInfo/doc)
- [Pywikibot script](https://gitlab.com/Hans5958-MWS/fandom-fridaynightfunking/-/blob/master/pwb/scripts/userscripts/songinfo_updater.py)
- [Initial Discord message](https://discord.com/channels/954532398400417832/969714711052554311/998634681668997330)
- [Post on #wiki-feedback forum](https://discord.com/channels/954532398400417832/1039194154850336778)

## Plan

- [x] Merge {{SongInfoGradient}} to {{SongInfo}}
- [x] Merge {{SongInfoLoud}} to {{SongInfo}}
- [x] Create TemplateData and other documentation
- [ ] Move template to the mainspace templates. ![status-wait]
- [x] Get list of pages to check
- [x] Create script for automated editing
- [ ] Get approval to run script ![status-wait]
- [ ] Run script on Bot5958 supervised

## Idea

These are the list of ideas. This may, or may not be implemented, and it is up for debate.

- [x] Add more fields for variations on select parameters
- [ ] `speed`, `maxscore`: Use multiple parameters for instead of doing new lines (worth it?)
- [ ] `speed`, `maxscore`: All difficulties or hardest?
- [ ] Support for `maxnotes`
- [ ] Have it as a new name (e.g. {{Song info}})

## Pages to check

This page lists how many pages to check. The amount of edited pages are most likely will be less than this. The amount of pages may change as time goes.

### Priority 1

Pages on this priority transcludes {{SongInfoLoud}}, which requires additional work to use the newer {{SongInfo}}

[Link to list (39 pages)](pages-prio-1.txt)

### Priority 2

Pages on this priority transcludes the other variations, which only requires template, but it is done to move to the newer parameter names.

[Link to list (1942 pages)](pages-prio-2.txt)

<!-- status start -->
[status-done]: https://upload.wikimedia.org/wikipedia/commons/thumb/4/41/Symbol_confirmed.svg/16px-Symbol_confirmed.svg.png
[status-wait]: https://upload.wikimedia.org/wikipedia/commons/thumb/5/54/Symbol_wait.svg/16px-Symbol_wait.svg.png
[status-stub]: https://upload.wikimedia.org/wikipedia/commons/thumb/f/f5/Symbol_stub_class.svg/16px-Symbol_stub_class.svg.png
[status-ongo]: https://upload.wikimedia.org/wikipedia/commons/thumb/9/94/Symbol_support_vote.svg/16px-Symbol_support_vote.svg.png
[status-done]: https://upload.wikimedia.org/wikipedia/commons/thumb/4/41/Symbol_confirmed.svg/16px-Symbol_confirmed.svg.png
<!-- status end -->
