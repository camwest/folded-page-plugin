# Folded Page

Keep a journal. See your story take shape.

Folded Page connects your assistant to your private journal. Save your original
words and agreed reflections separately, return to them in later conversations,
and co-author a private, approved Story of you. Ordinary conversation does not
automatically become a journal entry. This is a journaling aid, not a therapist.

## Connect

Create an account at [foldedpage.app](https://foldedpage.app), then install the
plugin and connect its Folded Page connector. Sign in to Folded Page and approve
access to your journal through OAuth. The hosted MCP endpoint is
`https://foldedpage.app/mcp`; no API key or local server is required.

In Claude, connect `folded-page` from the plugin's Connectors tab. Type `/` and
select the `folded-page` skill to begin; the same skill handles capture,
reflection, retrieval, corrections, and your approved Story. You can also ask
Claude to use Folded Page naturally. In ChatGPT, complete the
plugin's connection flow. A Folded Page subscription costs US$20/year; purchase
and account management happen on the website. The plugin does not process payments.

Folded Page is available to adults aged 18 or older in Canada and the United States.
You choose which assistant to connect and which entries and reflections to save.

### Private testing in Claude

In Claude web or Desktop, open Customize, select Plugins, then Add and Upload
plugin. Upload the Claude ZIP supplied for testing. Connect from its Connectors
tab and use `/folded-page` in a fresh chat. A private test installation does not
mean the plugin is listed in Claude's public directory.

If an older test connection still appears as `journal`, remove that old custom
connector and the old test plugin, then re-add the plugin and connect again.

## Try it

- “Save this exactly, without a reflection: I walked to the library after lunch.”
- “Find the library entry I saved and show my original words.”
- “Help me reflect on today. Show me a proposed reflection before saving it.”
- “Help me tell my story. Let me approve the wording before you save it.”

Corrections preserve revision history. Trash is recoverable for 30 days.
Use the website for recovery, permanent deletion, export, billing, and connection
management. The plugin cannot send email or permanently erase your journal.

## Data handling

The plugin contains readable journaling instructions and a connection to Folded
Page's hosted service. It runs no local programs. Journal tools send requested
content and queries to Folded Page, which stores and processes journal material
for journal features and search. The assistant receives requested journal results.
The service's provider use and retention are described in the
[privacy policy](https://foldedpage.app/privacy). Do not put account credentials
or private journal material in this repository.

## Help

If authorization expires or a connection is revoked, reconnect through your
assistant. If a save fails, check the reported error and your account access;
do not assume the entry was saved. Manage your journal and subscription on the
website, or contact [support](https://foldedpage.app/support).

These plugin files are proprietary; see [LICENSE](LICENSE) and the
[terms of service](https://foldedpage.app/terms).

## Maintaining this repository

The maintainer generates this repository from the private Folded Page source.
Make changes in that source and export a versioned release. Direct edits here
will stop the next export until the maintainer reconciles them. The
`distribution.json` file records the source commit and SHA-256 hashes of the
distributed files. For problems or suggested changes, contact
[support](https://foldedpage.app/support).
