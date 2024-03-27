# Frida TypeScript Agent

This is a minimal Frida agent written in TypeScript!

## Requirements

- Frida ↪ _`pip3 install frida-tools`_
- PNPM ↪ _`brew install pnpm`_

## Workflow

### Install Dependencies

```bash
pnpm install
```

### Build the Agent

```bash
pnpm build
```

_NOTE: watch mode is not enabled by default, but you can pass <kbd>-w</kbd> to the command to enable it._

### Launch Frida _(execute after build)_

```bash
pnpm load -n name

# You can also specify the target program with:
# ---------------------------------------------
# -p pid
# -f path/to/binary
# -N identifier
```
