---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/863327?"
user: tbenst
date: 2020-10-03
repo_name: julia-vscode/julia-vscode
html_url: https://github.com/julia-vscode/julia-vscode/issues/1684
repo_url: https://github.com/julia-vscode/julia-vscode
---

<a href='https://github.com/tbenst' target='_blank'>tbenst</a> open issue <a href='https://github.com/julia-vscode/julia-vscode/issues/1684' target='_blank'>julia-vscode/julia-vscode#1684</a>.

<p>REPL actively clears LD_LIBRARY_PATH</p><small>Currently, the Julia REPL seems to actively clear environmental variables like `LD_LIBRARY_PATH`. This is disastrous for my setup as julia cannot find many key libraries without this. Setting inside of julia with `ENV["LD_LIBRARY_PATH"] = [...]` does not work for `LD_LIBRARY_PATH`. Related to https://github.com/julia-vscode/julia-vscode/issues/1142, but opened an issue as actively clearing is a distinct issue....</small><a href='https://github.com/julia-vscode/julia-vscode/issues/1684' target='_blank'>View Comment</a>