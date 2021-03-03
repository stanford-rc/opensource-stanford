---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/1480321?"
user: SergioBenitez
date: 2021-03-02
repo_name: SergioBenitez/Rocket
html_url: https://github.com/SergioBenitez/Rocket/commit/a9fd6c556e0e4fbeb74718081edb0f56e0012a1c
repo_url: https://github.com/SergioBenitez/Rocket
---

<a href='https://github.com/SergioBenitez' target='_blank'>SergioBenitez</a> pushed to <a href='https://github.com/SergioBenitez/Rocket' target='_blank'>SergioBenitez/Rocket</a>

<small>Revamp codegen, fixing inconscpicuous bugs.

This commit completely revamps the way that codegen handles URI
"parameters". The changes are largely internal. In summary, codegen code
is better organized, better written, and less subject to error.

There are two breaking changes:
  * `path` is now `uri` in `route` attribute: `#[route(GET, path = "..")]`
    becomes `#[route(GET, uri = "..")]`.
  * the order of execution for path and query guards relative to
    each-other is now unspecified

Several error messages were improved. A couple of bugs were fixed:
  * Prior to this commit, Rocket would optimistically try to parse every
    segment of a URI as an ident, in case one was needed in the future.
    A bug in rustc results in codegen "panicking" if the segment
    couldn't _lex_ as an ident. This panic didn't manifest until far
    after expansion, unfortunately. This wasn't a problem before as we
    only allowed ident-like segments (ASCII), but now that we allow any
    UTF-8, the bug surfaced. This was fixed by never attempting to parse
    non-idents as idents.
  * Prior to this commit, it was impossible to generate typed URIs for
    paths that ignored path parameters via the recently added syntax
    `<_>`: the macro would panic. This was fixed by, well, handling
    these ignored parameters.</small>

<a href='https://github.com/SergioBenitez/Rocket/commit/a9fd6c556e0e4fbeb74718081edb0f56e0012a1c' target='_blank'>View Commit</a>