---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3916816?"
user: jmschrei
date: 2021-01-08
repo_name: jmschrei/pomegranate
html_url: https://github.com/jmschrei/pomegranate/issues/423
repo_url: https://github.com/jmschrei/pomegranate
---

<a href='https://github.com/jmschrei' target='_blank'>jmschrei</a> commented on issue <a href='https://github.com/jmschrei/pomegranate/issues/423' target='_blank'>jmschrei/pomegranate#423</a>.

<small>Howdy. If you want to make a GMM-HMM, you'll need one GMM for each of the states in the HMM, rather than a single GMM. I'd recommend this process: (1) use k-means to break your data into j chunks, (2) train a GMM on each chunk, (3) build a HMM using the `from_matrix` method (uniform transitions are OK to start off with) and the trained GMM, and use `fit` to train it for a few iterations. This is ROUGHLY the same process that happens in the backend when you use HiddenMarkovModel.from_samples. However, you're currently trying to pass in a trained GMM into the HMM from_samples method, when that method takes in the callable of a distribution. Here is an outline of code that is not bug-tested, but provided just to give you a bump in the right direction....</small>

<a href='https://github.com/jmschrei/pomegranate/issues/423' target='_blank'>View Comment</a>