# Bad Permalink (bad-permalink)

Permalink is part of the HTTP URL, someone will visit in order to view/read your document. For same, `permalink` must not contain special characters like `spaces`, or `$`.

## Why not fix it automatically?
Fixing permalinks behind the scenes, will create bad exceptations. The writer will expect the permalink in their markdown file to work, However the fixed version is still unknown to them.

## Allowed characters

The complete list of allowed characters are:

- Letters `A-Z or a-z`
- Number `0-9`
- Underscore `_`
- Dot `.`
- Forward slash `/`
- Dash `-`
- Tilde `~`

For programmers out there, here is the regex.

```
/[A-Za-z0-9_./\-~]+$/
```
