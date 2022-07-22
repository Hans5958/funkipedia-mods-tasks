# songinfo-update

**Description**: Merge {{SongInfo}} with {{SongInfoGradient}} and {{SongInfoLoud}}

**Pages checked**: 1981

**Auto/manual**: Manual (template making), automated (updating pages)

## Links

- [User:Hans5958/SongInfo](https://fridaynightfunking.fandom.com/wiki/User:Hans5958/SongInfo)
- [User:Hans5958/SongInfo/testcases](https://fridaynightfunking.fandom.com/wiki/User:Hans5958/SongInfo/testcases)
- [User:Hans5958/SongInfo/doc](https://fridaynightfunking.fandom.com/wiki/User:Hans5958/SongInfo/doc)
- [Pywikibot script](https://gitlab.com/Hans5958-MWS/fandom-fridaynightfunking/-/blob/master/pwb/scripts/userscripts/songinfo_updater.py)

## Plan

- [x] Merge {{SongInfoGradient}} to {{SongInfo}}
- [x] Merge {{SongInfoLoud}} to {{SongInfo}}
- [x] Create TemplateData and other documentation
- [x] Get list of pages to check
- [x] Create script for automated editing
- [ ] Get approval to run script 
- [ ] Run script on Bot5958 supervised

## Pages to check

This page lists how many pages to check. The amount of edited pages are most likely will be less than this. The amount of pages may change as time goes.

### Priority 1

Pages on this priority transcludes {{SongInfoLoud}}, which requires additional work to use the newer {{SongInfo}}

[Link to list (39 pages)](pages-prio-1.txt)

### Priority 2

Pages on this priority transcludes the other variations, which only requires template, but it is done to move to the newer parameter names.

[Link to list (1942 pages)](pages-prio-2.txt)