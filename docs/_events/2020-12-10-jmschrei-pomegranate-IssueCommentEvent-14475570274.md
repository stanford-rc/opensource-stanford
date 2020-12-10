---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3916816?"
user: jmschrei
date: 2020-12-10
repo_name: jmschrei/pomegranate
html_url: https://github.com/jmschrei/pomegranate/issues/848
repo_url: https://github.com/jmschrei/pomegranate
---

<a href='https://github.com/jmschrei' target='_blank'>jmschrei</a> commented on issue <a href='https://github.com/jmschrei/pomegranate/issues/848' target='_blank'>jmschrei/pomegranate#848</a>.

<small>There should never be impossible undefined events in the format of a Bayesian network. What's happening in this example is that your network does not include all of the edges that it should. Specifically, there is a dependence between A and B that you are not telling your model about. Because you are not telling your model about this dependence, the inference step from the model does not include it. A more accurate model, in your case, would have an edge between A and B and specify, in the conditional probability table of the child, which combinations can happen. ...</small>

<a href='https://github.com/jmschrei/pomegranate/issues/848' target='_blank'>View Comment</a>