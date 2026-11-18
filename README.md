# LegalQuants for Google Antigravity

LegalQuants is a community of lawyers and engineers who build with AI. This plugin connects
Antigravity to the LegalQuants knowledge server, so your agent can search what members have
discussed and learned, and help you keep your member profile up to date.

## Before you install

- You need a LegalQuants account. Apply at <https://www.legalquants.com>.
- Community knowledge is open to members with an approved, published profile. If your profile
  is not published yet, you can still sign in and use the profile tools to finish it.

## Sign in

The plugin connects to `https://www.legalquants.com/mcp`. The first time your agent uses it,
Antigravity opens a browser window. Sign in with your LegalQuants account. There is no API key
to copy.

## What is included

One MCP server, `legalquants`, with two groups of tools.

**Community knowledge**

- `list`, `read`, `grep`: browse, read and search community discussions and curated notes.
- `scan_thread`: read a discussion thread in full.
- `traverse_graph`: follow links between related notes.
- `read_attachment`: read a file that was shared in a discussion.

Results keep their source, path and line, so your agent can cite them. Members appear only
under pseudonyms.

**Your account and profile**

- `get_my_lq_status`: check your membership and what you can access.
- `get_my_profile`, `update_my_profile`, `publish_my_profile` and related tools: view and edit
  your own profile, works, media and links. Nothing is published without your approval.
- `get_shared_calendar`, `set_my_event_attendance`: see community events and reply to them.

## Example workflows

- "What have LegalQuants members learned about using AI for contract review?"
- "Find community discussions on evaluating legal AI tools, with citations."
- "Draft an update to my LegalQuants profile from my latest project, and show me before saving."

## Support

Questions or problems: <https://www.legalquants.com> or j.tso@legalquants.com.

## License

MIT
