[[!table class="front" header="column" delimiter="," data="""
[[!img images/ai3m.png size="64x64" link="index"]],[[!inline raw=yes pages="front/title"]]
"""]]

[[!inline
description="Comments pending moderation"
pages="comment_pending(*)"
show=-1
feedfile=pendingmoderation
rss=yes
]]

Comments in the [[!commentmoderation desc="moderation queue"]]:
[[!pagecount
pages="comment_pending(*)"
]]

Recently posted comments:
[[!inline
pages="comment(*)"
template="comment"
rss=yes
]]
