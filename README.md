# Zion Landing Page

Source export of the Zion student identity landing page.

## Run locally

1. Install [Node.js](https://nodejs.org/) and pnpm.
2. From this folder, run `pnpm install`.
3. Start the landing page with:

   ```bash
   pnpm --filter @workspace/zion-landing run dev
   ```

The app is located at `artifacts/zion-landing`.

## Useful commands

```bash
pnpm --filter @workspace/zion-landing run typecheck
pnpm --filter @workspace/zion-landing run build
```

Generated folders such as `node_modules` and `dist` are intentionally not included; they are recreated by `pnpm install` and the build command.
