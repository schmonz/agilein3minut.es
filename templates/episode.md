[[!meta name="twitter:card" content="player"]]
[[!meta name="twitter:site" content="@AgileIn3Minutes"]]
[[!meta name="twitter:title" content="Agile in 3 Minutes <TMPL_VAR NAME=page>: <TMPL_VAR NAME=title>"]]
[[!meta name="twitter:description" content="<TMPL_VAR NAME=question>"]]
[[!meta name="twitter:player" content="https://agilein3minut.es/twittercard/<TMPL_VAR NAME=page>/"]]
[[!meta name="twitter:player:width" content="480"]]
[[!meta name="twitter:player:height" content="20"]]
[[!meta author="Amitai Schleier"]]
[[!meta title="<TMPL_VAR NAME=page>: <TMPL_VAR NAME=title>"]]
[[!meta date="<TMPL_VAR NAME=date>"]]
[[!meta enclosure="ai3m<TMPL_VAR NAME=page>.mp3"]]
[[!tag episode season-<TMPL_VAR NAME="season"> <TMPL_VAR NAME="tags">]]

[[!table class="front" header="column" delimiter="," data="""
[[!img images/ai3m.png size="64x64" link="index"]],[[!inline raw=yes pages="front/title"]]
# <TMPL_VAR NAME="question">,
Listen&nbsp;&nbsp;,<div id="inlineaudio"><audio src="/ai3m<TMPL_VAR NAME=page>.mp3" preload="metadata" controls="controls"></audio></div>
Discuss&nbsp;&nbsp;,[[!inline raw=yes pages="front/discuss"]]
Subscribe&nbsp;&nbsp;,[[!inline raw=yes pages="front/subscribe"]]
"""]]

# Learn More

<TMPL_VAR NAME="learnmore">

# Give Feedback

- [Comment on this episode](https://agilein3minut.es/cgi/ikiwiki?do=comment&page=<TMPL_VAR NAME="page">)
- [[Support the show|support]]
