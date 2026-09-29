# Carly for Claude

![Carly](assets/icon.png)

[Carly](https://www.usecarly.com) is an executive assistant for your email,
calendar, CRM, and recurring work. This plugin connects Claude to your Carly
account and teaches Claude how to use it well.

With it, Claude can search and reply to your Gmail or Outlook mail, find free
time and book meetings across your calendars, keep contacts and CRM records
current, manage to-dos and files in Drive or OneDrive, and build workflows that
keep running after the conversation ends — a morning digest, inbox triage, a
scheduled follow-up.

## What's inside

| Component | What it does |
| --- | --- |
| `.mcp.json` | Connects to Carly's hosted MCP server at `https://carlyassistant.com/mcp`. You sign in with OAuth the first time Claude uses it. |
| `skills/carly-assistant` | Instructions for Claude: confirm results before reporting them, preview bulk changes before making them, recover from common tool errors, and send you to the right page to connect an app or get help. |

The plugin contains no code. It does not run anything on your machine and sends
nothing anywhere except the Carly MCP server above, which acts only on the
account you sign in with.

## Get started

1. Install the plugin from the Claude directory.
2. The first time Claude calls a Carly tool, sign in with Google or Microsoft.
3. Connect your mailboxes, calendars, and other apps at
   https://carlyassistant.com/integrations.

New to Carly? Sign up at https://www.usecarly.com. Full connector docs:
https://www.usecarly.com/mcp

## Support

- Help and FAQ: https://calbotservice.com/faq
- Email: support@calbotservice.com
- Privacy policy: https://calbotservice.com/privacy
- Terms: https://calbotservice.com/terms
