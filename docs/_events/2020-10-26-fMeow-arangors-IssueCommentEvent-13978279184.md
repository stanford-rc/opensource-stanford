---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1480321?"
user: SergioBenitez
date: 2020-10-26
repo_name: fMeow/arangors
html_url: https://github.com/fMeow/arangors/issues/37
repo_url: https://github.com/fMeow/arangors
---

<a href='https://github.com/SergioBenitez' target='_blank'>SergioBenitez</a> commented on issue <a href='https://github.com/fMeow/arangors/issues/37' target='_blank'>fMeow/arangors#37</a>.

<small>@fMeow I'd like to clarify that the crux of the issue is that your crate is currently misusing Cargo features. Cargo features _must_ be additive; any other use of features is incorrect and can [break code](https://github.com/rust-lang/cargo/issues/4328). In particular, this means that your crate must be able to build with _both_ features enabled and cannot require any exclusivity between features. Code like the following violates this:...</small>

<a href='https://github.com/fMeow/arangors/issues/37' target='_blank'>View Comment</a>