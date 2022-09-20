# Doc Separation

**Description**: Separate template documentation to it's own page on `/doc`

**Status**: ![status-done] Done

**Pages checked**: 194

**Auto/manual**: Automated

## Background

Information related to the template can be put inside <noinclude\></noinclude\>, which can be called as the documentation of the template.

While this is fine for basic usage, this usually may inflate the page size larger, which may be not ideal for Fandom servers (this is one hypothesis of why it is slow). Moreover, when a page is locked, the documentation can't be updated, even though it should be fine to update it.

Luckily, there is a solution for this: putting the documentation in it's own page on `[TEMPLATE_NAME]/doc`, and then link it using the available templat `{{Documentation}}`. So this task has a goal to do that.

## Links

- [Pywikibot script](https://gitlab.com/Hans5958-MWS/fandom-fridaynightfunking/-/blob/master/pwb/scripts/userscripts/doc_separator.py)

## Plan

- [x] Get list of pages to check
- [x] Create script for automated editing
- ~~[ ] Get approval to run script~~ (small scope, executed slowly)
- [x] Run script on Bot5958 supervised
 
## Pages to check

This page lists how many pages to check. The amount of edited pages are most likely will be less than this. The amount of pages may change as time goes.

[Link to list (194 pages)](pages.txt)

<!-- status start -->
[status-done]: https://upload.wikimedia.org/wikipedia/commons/thumb/4/41/Symbol_confirmed.svg/16px-Symbol_confirmed.svg.png
[status-wait]: https://upload.wikimedia.org/wikipedia/commons/thumb/5/54/Symbol_wait.svg/16px-Symbol_wait.svg.png
[status-stub]: https://upload.wikimedia.org/wikipedia/commons/thumb/f/f5/Symbol_stub_class.svg/16px-Symbol_stub_class.svg.png
[status-ongo]: https://upload.wikimedia.org/wikipedia/commons/thumb/9/94/Symbol_support_vote.svg/16px-Symbol_support_vote.svg.png
[status-done]: https://upload.wikimedia.org/wikipedia/commons/thumb/4/41/Symbol_confirmed.svg/16px-Symbol_confirmed.svg.png
<!-- status end -->
