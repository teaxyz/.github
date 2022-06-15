# Coding Style

* Abbreviations are ok, if they are common or common in our domain, eg. `pkg`,
    `deps`, etc.
* Spaces in one-line objects: `{ foo }` not `{foo}`
* Prefer double quotes, `"`, over single quotes, `'`
* Prefer `kebab-case`, then `camelCase`. Most languages do not support
    kebab-case, however *you can name your files this way*.
* Avoid `async` for chainable constructs since TypeScript does not chain off the promise result and usage becomes awkward

## Generally

We are not all or nothing: what matters most is code clarity and intent.
