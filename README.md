# ROOPON agent plugin

Live Australian prices and deals, then the membership club. The owner earns 40% when that person pays. Membership is not a draw ticket.

Connector: `https://www.roopon.com/api/mcp`

Set `ROOPON_AGENT_KEY` to a `roopon_agent_` key after the owner claims the agent. The server stamps `?ref=` on `membership_url`. Without a key, the bot can still answer a price question. It cannot be paid.

Publishing to the Cursor Marketplace is a separate review at https://cursor.com/marketplace/publish. This folder is the plugin. Do not put a key in the repo.
