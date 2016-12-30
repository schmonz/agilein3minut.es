[[!meta name="twitter:card" content="player"]]
[[!meta name="twitter:site" content="@AgileIn3Minutes"]]
[[!meta name="twitter:title" content="Agile in 3 Minutes <TMPL_VAR NAME=page>: <TMPL_VAR NAME=title>"]]
[[!meta name="twitter:description" content="<TMPL_VAR NAME=question>"]]
[[!meta name="twitter:player" content="https://agilein3minut.es/twittercard/<TMPL_VAR NAME=page>/"]]
[[!meta name="twitter:player:width" content="480"]]
[[!meta name="twitter:player:height" content="20"]]
[[!meta author="<TMPL_IF AUTHOR><TMPL_VAR NAME=author><TMPL_ELSE>Amitai Schleier</TMPL_IF>"]]
[[!meta title="<TMPL_VAR NAME=page>: <TMPL_VAR NAME=title>"]]
[[!meta date="<TMPL_VAR NAME=date>"]]
[[!meta enclosure="ai3m<TMPL_VAR NAME=page>.mp3"]]
[[!tag episode season-<TMPL_VAR NAME="season"> <TMPL_VAR NAME="tags">]]

<TMPL_VAR NAME=page>: <TMPL_VAR NAME=title> (part of [[Season <TMPL_VAR NAME="season">|tag/season-<TMPL_VAR NAME="season">]])

_<TMPL_IF AUTHOR>Special guest <TMPL_VAR NAME=author><TMPL_ELSE>Amitai</TMPL_IF> asks..._

# <TMPL_VAR NAME="question">

<div id="inlineaudio"><audio src="/ai3m<TMPL_VAR NAME=page>.mp3" preload="metadata" controls="controls"></audio></div>

# Learn More

<TMPL_VAR NAME="learnmore">

# Discuss

[[!inline raw=yes pages="front/discuss"]] | [agilein3minut.es](https://agilein3minut.es/cgi/ikiwiki?do=comment&page=<TMPL_VAR NAME="page">)

# Subscribe

[[!inline raw=yes pages="front/subscribe"]]
