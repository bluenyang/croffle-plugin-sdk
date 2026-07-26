# @croffledev/croffle-sdk (archived)

> **This repository is archived.**

The former **plugin SDK / CLI** package was renamed to **`@croffledev/croffle-cli`** and moved into the Croffle monorepo.

| Before (this repo)        | After (monorepo)                                                                                                                                       |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `@croffledev/croffle-sdk` | `@croffledev/croffle-cli`                                                                                                                              |
| Standalone repo           | [`team-croffle/croffle`](https://github.com/team-croffle/croffle) → [`packages/cli`](https://github.com/team-croffle/croffle/tree/master/packages/cli) |

### Install / use

```bash
pnpm dlx @croffledev/croffle-cli create my-plugin
# or
pnpm dlx create-croffle-plugin my-plugin

pnpm dlx @croffledev/croffle-cli build
pnpm dlx @croffledev/croffle-cli pack
```

Plugin TypeScript types: [`@croffledev/croffle-types`](https://www.npmjs.com/package/@croffledev/croffle-types) (also maintained in the monorepo under `packages/types`).

Do not open PRs against this repo. Contribute in the [main Croffle repository](https://github.com/team-croffle/croffle). See [CONTRIBUTING.md](https://github.com/team-croffle/croffle/blob/master/CONTRIBUTING.md).

---

## License

MIT — see `LICENSE` if present in this tree, otherwise the license in the monorepo.

Copyright (c) 2026 Croffle Dev. & Croffle Contributors
