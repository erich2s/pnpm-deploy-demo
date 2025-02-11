# `pnpm deploy` not bring the "packageManager" field of root package.json to the target directory's package.json

Install dependencies

```bash
pnpm i
```

Deploy a package from a workspace to ./prod/app

```bash
pnpm deploy --filter=app --prod ./prod/app
```
