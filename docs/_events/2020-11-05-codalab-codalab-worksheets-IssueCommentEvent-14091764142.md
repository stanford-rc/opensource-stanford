---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/7272031?"
user: nelson-liu
date: 2020-11-05
repo_name: codalab/codalab-worksheets
html_url: https://github.com/codalab/codalab-worksheets/pull/3022
repo_url: https://github.com/codalab/codalab-worksheets
---

<a href='https://github.com/nelson-liu' target='_blank'>nelson-liu</a> commented on issue <a href='https://github.com/codalab/codalab-worksheets/pull/3022' target='_blank'>codalab/codalab-worksheets#3022</a>.

<small>I made a large set of changes in 6e3b7e1, because I noticed that the upgrade wasn't working if we were already on the bad revision (and had gotten there via an upgrade). To handle this case, I executed raw SQL to move rows with id 0 to the end of the table (the next highest ID), and then ALTERed the columns to be auto-incrementing. It's documented in a bit more detail in the code itself....</small>

<a href='https://github.com/codalab/codalab-worksheets/pull/3022' target='_blank'>View Comment</a>