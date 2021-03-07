---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/1480321?"
user: SergioBenitez
date: 2021-03-06
repo_name: jebrosen/Rocket
html_url: https://github.com/jebrosen/Rocket/commit/4d0042c3951acc0d9ab1008893918ca94c45972c
repo_url: https://github.com/jebrosen/Rocket
---

<a href='https://github.com/SergioBenitez' target='_blank'>SergioBenitez</a> pushed to <a href='https://github.com/jebrosen/Rocket' target='_blank'>jebrosen/Rocket</a>

<small>Allow '<path..>' to match zero segments.

This changes core routing so that '<path..>' in a route URI matches zero
or more segments. Previously, '<path..>' matched _1_ or more.

  * Routes '$a' and '$b/<p..>' collide if $a and $b previously collided.
  * For example, '/' now collides with '/<p..>'.
  * Request '$a' matches route '$b/<p..>' if $a previously matched $b.
  * For example, request '/' matches route '/<p..>'.

Resolves #985.</small>

<a href='https://github.com/jebrosen/Rocket/commit/4d0042c3951acc0d9ab1008893918ca94c45972c' target='_blank'>View Commit</a>