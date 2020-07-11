# lens-npm-install

Inject `node_modules/` with `npm`

## Example

`.holo/lenses/npm-install.toml`:

```toml
[hololens]
package = "holo/lens-npm-install"

[hololens.input]
files = [
    "package.json",
    "package-lock.json"
]
```
