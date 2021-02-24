---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1480321?"
user: SergioBenitez
date: 2021-02-23
repo_name: dtolnay/async-trait
html_url: https://github.com/dtolnay/async-trait/pull/143
repo_url: https://github.com/dtolnay/async-trait
---

<a href='https://github.com/SergioBenitez' target='_blank'>SergioBenitez</a> commented on issue <a href='https://github.com/dtolnay/async-trait/pull/143' target='_blank'>dtolnay/async-trait#143</a>.

<small>@Kiiyya Your larger project is probably enabling features of `syn` that result in `Debug` being implemented on those types while `async-trait` doesn't enable such features. This is was an omission on my part ... to omit the `Debug` derive. I've pushed a commit that should resolve the issue! Thanks for testing....</small>

<a href='https://github.com/dtolnay/async-trait/pull/143' target='_blank'>View Comment</a>