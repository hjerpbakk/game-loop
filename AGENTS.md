# game-loop

Small browser game that demonstrates game loop variants (simple loop, variable timestep, fixed timestep). Vite and TypeScript, no framework.

## Run

```bash
npm install
npm run dev
npm run build   # tsc && vite build
```

There is no test suite.

- Each loop variant is a git tag: `v1` (simple loops), `v2` (variable timestep), `v3` (fixed timestep), `v4` (separate UPS and FPS, on a side branch that was never merged into `main`). Checking one out detaches HEAD, so go back to `main` afterwards.
- Both `package-lock.json` and `pnpm-lock.yaml` exist. The README uses npm.
