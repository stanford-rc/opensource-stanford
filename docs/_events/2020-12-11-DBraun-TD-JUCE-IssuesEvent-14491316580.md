---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/2096055?"
user: DBraun
date: 2020-12-11
repo_name: DBraun/TD-JUCE
html_url: https://github.com/DBraun/TD-JUCE/issues/6
repo_url: https://github.com/DBraun/TD-JUCE
---

<a href='https://github.com/DBraun' target='_blank'>DBraun</a> open issue <a href='https://github.com/DBraun/TD-JUCE/issues/6' target='_blank'>DBraun/TD-JUCE#6</a>.

<p>Support VST3 effects with secondary inputs</p><small>This is something I already addressed in [DawDreamer](https://github.com/DBraun/DawDreamer/). In VST3 instruments that have secondary inputs, `myPlugin->processBlock` must receive a buffer that has 4 channels (a stereo pair for each of the two inputs). For example, the second input can be the signal for sidechain compression. You can't pass 2 channels. Instead you'd just put zeros in the third and fourth channels....</small><a href='https://github.com/DBraun/TD-JUCE/issues/6' target='_blank'>View Comment</a>