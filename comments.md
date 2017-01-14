[[!meta title="Comments on the Show"]]

[[!inline
pages="blurb/*"
limit=0
sort="title_natural"
raw=yes
]]

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
