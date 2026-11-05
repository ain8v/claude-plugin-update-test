# Plugin update test (throwaway)

A test by AI Native. It checks whether a claude.ai plugin skill can make an artifact and later update that same artifact in place when a new plugin version arrives. It holds no client code or data and will be deleted after the test.

## Try it

1. In claude.ai, open **Plugins**, select **Add marketplace** and enter `ain8v/claude-plugin-update-test`. Turn on **Sync automatically**.
2. Install **artifact-update-test**.
3. In a new chat, ask: "Set up the plugin update test page." The page shows **Version 1** and greets you by name.
4. When version 2 is released, select **Check for updates** on the marketplace (or wait for the sync).
5. In a new chat, ask: "Update the plugin update test page." The same link should then show **Version 2**, still with your name.
