# RomaJS intro slides

Intro slides used at the beginning of RomaJS meetings.

## Development

### Requirements

This project requires [node 20](https://nodejs.org/en/) and uses [`pnpm`](https://pnpm.io/) as package manager.

If you have [`nvm`](https://github.com/nvm-sh/nvm) installed run

```bash
nvm use
```

#### pnpm & corepack

You do not need to install [`pnpm`](https://pnpm.io), you just need have [`node 20`](https://nodejs.org/en/) installed and then enable [`corepack`](https://nodejs.org/api/corepack.html):

```bash
corepack enable
```

You should then be able to run pnpm normally in this project, e.g.

```bash
pnpm run build
```

### Start project

To start the slide show:

- `pnpm install`
- `pnpm run dev`
- visit http://localhost:3030

Edit the [slides.md](./slides.md) to see the changes.

Learn more about Slidev on [documentations](https://sli.dev/).

### Build

```bash
pnpm run build
```

### Preview

exec [build](#build) script then run:

```bash
pnpm run preview
```

### Change theme

Add or update the theme config object in the frontmatter of [slides.md](./slides.md).

```yaml
# used for theme customization, will inject root styles as `--slidev-theme-x` for attribute `x`
themeConfig:
  primary: '#ffb200'
  bg-primary: '#111'
```

See https://sli.dev/custom/ for more details.
