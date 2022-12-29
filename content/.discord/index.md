+++
title = "DESU: Dynamis Extreme, Savage, Ultimate"
template = "terraform/server.tf.html"

in_search_index = false
sort_by = "weight"

[extra]
data_roles = ["Moderator", "TunedIn", "KupoBot"]

[[extra.categories]]
name = "info"
channels = ["welcome-info", "announcements", "rules", "server-map", "resources", "community-links", "optional-roles"]

[[extra.categories]]
name = "party up"
channels = ["party-finder", "events", "planning"]

[[extra.categories]]
name = "community"
channels = ["introductions", "general", "ask-questions-here", "story-lore", "screenshots", "memes", "desu-meta", "lb4-lounge"]

[[extra.categories]]
name = "strats & theory"
channels = ["pf-culture", "macro-tech", "encounter-discussion", "conventions-voting"]

[[extra.categories]]
name = "static formation"
channels = ["static-recruiting", "static-lfg", "static-recruiting-archive", "static-lfg-archive"]

[[extra.categories]]
name = "voice"
channels = ["General", "Party One", "Party Two"]

[[extra.categories]]
name = "server"
channels = ["open-a-ticket", "setup-instructions", "char-setup", "bot-spam"]

[[extra.categories]]
name = "admin"
channels = ["community-building", "moderation", "admin-bot-commands", "member-logs", "bot-logs"]

[[extra.categories]]
name = "open tickets"

[[extra.categories]]
name = "closed tickets"
# 
[extra.args]
default_message_notifications = 1
explicit_content_filter = 2
region = "us-south"
verification_level = 2
+++
