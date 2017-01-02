[[!templatebody <<ENDBODY
[[!meta name="twitter:card" content="player"]]
[[!meta name="twitter:site" content="@AgileIn3Minutes"]]
[[!meta name="twitter:title" content="Agile in 3 Minutes <TMPL_VAR page>: <TMPL_VAR title>"]]
[[!meta name="twitter:description" content="<TMPL_VAR question>"]]
[[!meta name="twitter:player" content="https://agilein3minut.es/twittercard/<TMPL_VAR page>/"]]
[[!meta name="twitter:player:width" content="480"]]
[[!meta name="twitter:player:height" content="20"]]
[[!meta author="<TMPL_IF AUTHOR><TMPL_VAR author><TMPL_ELSE>Amitai Schleier</TMPL_IF>"]]
[[!meta title="<TMPL_VAR page>: <TMPL_VAR title>"]]
[[!meta date="<TMPL_VAR date>"]]
[[!meta enclosure="ai3m<TMPL_VAR page>.mp3"]]
[[!tag episode season-<TMPL_VAR season> <TMPL_VAR tags>]]

_<TMPL_IF AUTHOR>Special guest <TMPL_VAR author><TMPL_ELSE>Amitai</TMPL_IF> asks..._

# <TMPL_VAR question>

<div id="inlineaudio"><audio src="/ai3m<TMPL_VAR page>.mp3" preload="metadata" controls="controls"></audio></div>

# Learn More

<TMPL_VAR learnmore>

# Discuss

[[!inline raw=yes pages="front/discuss"]] | [agilein3minut.es](https://agilein3minut.es/cgi/ikiwiki?do=comment&page=<TMPL_VAR page>)

# Subscribe

[[!inline raw=yes pages="front/subscribe"]]
ENDBODY]]

[[!meta redir="index"]]
