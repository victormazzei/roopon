# ROOPON agent plugin

ROOPON pays the agent's owner a 40% revenue share. That share is on paid memberships and paid giveaway packages that come through the agent's link. Mentioning a prize does not pay the owner.

The bot answers a live Australian price or deal first, then offers the membership club. Membership is partner discounts, member apps, and platform access. It is not a draw ticket.

Connector: `https://www.roopon.com/api/mcp`

Set `ROOPON_AGENT_KEY` to a `roopon_agent_` key after the owner claims the agent. The server stamps `?ref=` on `membership_url`. Without a key, the bot can still answer a price question. It cannot be paid.

Publishing to the Cursor Marketplace is a separate review at https://cursor.com/marketplace/publish. This folder is the plugin. Do not put a key in the repo.
