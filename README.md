# wxt-turborepo-no-output-repo

After running `pnpm install`
1. WXT 0.19.4 inside a turborepo will give no output on `wxt submit`
```
cd wxt-inside-turborepo/apps/wxt-0.19.4
pnpm wxt submit
```

2. WXT 0.18.15 inside a turborepo will give output on `wxt submit`
```
cd wxt-inside-turborepo/apps/wxt-0.18.15
pnpm wxt submit
```

3. WXT 0.19.4 by itself (not in a monorepo environment) will have correct output on `wxt submit`
```
cd wxt-standalone
pnpm wxt submit
```
