---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/1480321?"
user: SergioBenitez
date: 2020-11-03
repo_name: jebrosen/Rocket
html_url: https://github.com/jebrosen/Rocket/commit/52320020bc26387b96a0126a0d49821ad3125e7d
repo_url: https://github.com/jebrosen/Rocket
---

<a href='https://github.com/SergioBenitez' target='_blank'>SergioBenitez</a> pushed to <a href='https://github.com/jebrosen/Rocket' target='_blank'>jebrosen/Rocket</a>

<small>Use thread-safe 'CookieJar's.

The user-facing changes effected by this commit are:

  * The 'http::Cookies<'_>' guard is now '&http::CookieJar<'_>'.
  * The "one-at-a-time" jar restriction is no longer imposed.
  * 'CookieJar' retrieval methods return 'http::CookieCrumb'.
  * The 'private-cookies' feature is now called 'secrets'.
  * Docs flag private cookie methods with feature cfg.
  * Local, async request dispatching is never serialized.
  * 'Client::cookies()' returns the tracked 'CookieJar'.
  * 'LocalResponse::cookies()' returns a 'CookieJar'.
  * 'Response::cookies()' returns an 'impl Iterator'.
  * A path of '/' is set by default on all cookies.
  * 'SameSite=strict' is set by default on all cookies.
  * 'LocalRequest::cookies()' accepts any 'Cookie' iterator.
  * The 'Debug' impl for 'Request' prints the cookie jar.

Resolves #1332.</small>

<a href='https://github.com/jebrosen/Rocket/commit/52320020bc26387b96a0126a0d49821ad3125e7d' target='_blank'>View Commit</a>