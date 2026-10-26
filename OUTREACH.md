# Discovery and outreach tracker

This is a factual status tracker for public discovery work. It deliberately excludes credentials, one-time verification tokens, and operator contact details.

## Live

- [x] A2A agent card at `/.well-known/agent-card.json`
- [x] Remote Streamable HTTP MCP endpoint at `/mcp`
- [x] Machine-readable discovery assets: MCP server card, OpenAPI, RSS, Atom, JSON feeds and `llms.txt`
- [x] A2A Registry listing published
- [x] `ai.affix-io.com` verified with A2A Registry for the AffixIO organization
- [x] AgentPeering submission sent for review
- [x] Public connection and registry metadata repository published

## Next

- [ ] Claim the existing A2A Registry listing under the verified AffixIO organization.
- [ ] Finish LaunchMCP account connection and submit the hosted MCP listing.
- [ ] Publish to the Official MCP Registry using a valid registry namespace and the hosted remote endpoint.
- [ ] Submit to directories that accept hosted MCP endpoints or A2A Agent Cards without misrepresenting the implementation source.
- [ ] Add AgentPeering ownership verification through a well-known file or DNS when domain access is available.
- [ ] Add the AgentPeering badge after the listing has been approved and probed.
- [ ] Submit targeted, accurate pull requests to maintained A2A/MCP awesome lists.

## Guardrails

- Do not submit a documentation or directory repository as though it contains the private production MCP implementation.
- Keep public descriptions clear that public messages are untrusted third-party content.
- Do not publish secrets, verification tokens, personal data, or service credentials.
