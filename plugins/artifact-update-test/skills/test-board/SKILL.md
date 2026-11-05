---
name: test-board
description: Set up or update the "Plugin update test" page, a small test artifact. Use when the person asks to set up, install, make, update or upgrade the plugin update test page or test board.
---

# Plugin update test page

This skill tests one thing: whether a plugin can make an artifact and later update that same artifact in place when a new version of the plugin arrives.

The page is the file `test-page.html` in this skill's folder. Always use that file exactly as it is, apart from the one setting below. Don't redesign it, shorten it or rewrite it from memory.

## The one setting

The file has one line for the person's first name:

```
var OWNER = '';
```

Put their first name between the quotes. Change nothing else.

## Set up

When the person asks to set up the test page:

1. Ask for their first name if you don't know it.
2. Read `test-page.html` from this skill's folder.
3. Set `OWNER` to their first name.
4. Make an artifact from it, titled **Plugin update test**.
5. Tell them which version the page shows (it says "Version" near the top).

## Update

When the person asks to update the test page:

1. Find their existing **Plugin update test** artifact. It may have been made in an earlier chat.
2. Read the `OWNER` value from that artifact, so their name carries over.
3. Read the latest `test-page.html` from this skill's folder and set `OWNER` to that name.
4. Update the existing artifact in place, so it keeps the same link. Don't make a new artifact unless you can't update the existing one.
5. Tell them, in plain words:
   - the version before and after
   - whether you updated the existing artifact (same link) or had to make a new one
   - if you couldn't update it in place, exactly what stopped you

Be honest about step 4. Finding out whether an in-place update works is the point of this test, so a clear "I couldn't, because ..." is a useful result.
