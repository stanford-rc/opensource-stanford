---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/208955?"
user: keithw
date: 2020-08-31
repo_name: mobile-shell/mosh
html_url: https://github.com/mobile-shell/mosh/issues/1112
repo_url: https://github.com/mobile-shell/mosh
---

<a href='https://github.com/keithw' target='_blank'>keithw</a> commented on issue <a href='https://github.com/mobile-shell/mosh/issues/1112' target='_blank'>mobile-shell/mosh#1112</a>.

<small>It's not quite that "the server was using the Indian locale" -- the processes on the server have no idea what locales/languages are available without brute-force trying a bunch. This is just the way that C and POSIX work. **You** know as a human that the server has en_IN.UTF-8 available (and maybe you have a shell rc file or PAM config file that sets this environment variable when you log in with an interactive session) but there's no way for a process to know that without brute-force searching through all the world's languages....</small>

<a href='https://github.com/mobile-shell/mosh/issues/1112' target='_blank'>View Comment</a>