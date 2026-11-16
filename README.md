# qino-test-nextjs

A test Next.js site built with [Qino](https://github.com/CharlyMartin/qino). It's used to try out the Qino cloud UI, which reads the generated `qino/_generated/config.json`.

The app is a copy of `examples/next-js` from the Qino monorepo, using the published `@qino/cms` package.

## Getting started

```bash
pnpm install
pnpm dev
```

`pnpm build` runs `qino build` first, which regenerates `qino/_generated/config.json`. Commit that file when it changes so the cloud UI picks it up.
