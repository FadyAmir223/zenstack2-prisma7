just don't use `@default(auth().id)` to avoid generating logical schema files which fail and have no workaround

```sh
pnpm db:generate
```
