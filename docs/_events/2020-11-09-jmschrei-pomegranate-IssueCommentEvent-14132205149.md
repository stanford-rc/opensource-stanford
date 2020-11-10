---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3916816?"
user: jmschrei
date: 2020-11-09
repo_name: jmschrei/pomegranate
html_url: https://github.com/jmschrei/pomegranate/issues/835
repo_url: https://github.com/jmschrei/pomegranate
---

<a href='https://github.com/jmschrei' target='_blank'>jmschrei</a> commented on issue <a href='https://github.com/jmschrei/pomegranate/issues/835' target='_blank'>jmschrei/pomegranate#835</a>.

<small>So, you getting a NaN is a problem because pomegranate should never return NaN's. However, conceptually, I'm not sure I understand why sklearn is returning what it does. Both components of the naive Bayes should have the same underlying distributions and so the likelihood of each class should be the same regardless of feature smoothing. However, the prior probability should favor class 0 because 66% of training examples have that class. If you smooth that by adding a pseudocount of 1 to each class, you should get that 60% of examples fall under class 0. ...</small>

<a href='https://github.com/jmschrei/pomegranate/issues/835' target='_blank'>View Comment</a>