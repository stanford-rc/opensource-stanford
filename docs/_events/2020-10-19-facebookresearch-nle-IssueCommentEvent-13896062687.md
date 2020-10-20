---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1855260?"
user: vzhong
date: 2020-10-19
repo_name: facebookresearch/nle
html_url: https://github.com/facebookresearch/nle/issues/90
repo_url: https://github.com/facebookresearch/nle
---

<a href='https://github.com/vzhong' target='_blank'>vzhong</a> commented on issue <a href='https://github.com/facebookresearch/nle/issues/90' target='_blank'>facebookresearch/nle#90</a>.

<small>@aleSuglia I believe one of the key difference is the use of polybeast (paper) instead of monobeast (this repo). Due to the parallel nature of the former, I believe the learning characteristics of the latter is different. FWIW, I have ran each task individually with the default hyperparameters. They all seem to improve (I didn't run them for 1 billion steps as in the paper), however the rate of convergence seems slower than the paper (perhaps due to different code base). The two envs that I find problematic are Staircase and Pets, neither of which converge to anything beyond zero even after I increased the reward from 1 to 100....</small>

<a href='https://github.com/facebookresearch/nle/issues/90' target='_blank'>View Comment</a>