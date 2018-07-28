# Bad Permalink (bad-permalink)

Permalink is part of the HTTP URL, someone will visit in order to view/read your document. For same, `permalink` must not contain special characters like `spaces`, or `$`.

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
