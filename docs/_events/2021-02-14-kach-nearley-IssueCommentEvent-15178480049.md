---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5202416?"
user: kach
date: 2021-02-14
repo_name: kach/nearley
html_url: https://github.com/kach/nearley/pull/567
repo_url: https://github.com/kach/nearley
---

<a href='https://github.com/kach' target='_blank'>kach</a> commented on issue <a href='https://github.com/kach/nearley/pull/567' target='_blank'>kach/nearley#567</a>.

<small>Ah, so I took another look the other and actually I think the current behavior is correct and indeed what is intended: if the lexer doesn't has() a token with that name, then the next fallback is to check if there is a variable with that name in scope that describes the token. I think this was a backwards-compatibility-related thing....</small>

<a href='https://github.com/kach/nearley/pull/567' target='_blank'>View Comment</a>