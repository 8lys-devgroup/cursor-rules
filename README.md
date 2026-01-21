# 8lys Cursor Rules

Shared Cursor IDE rules for 8lys projects.

## Usage

Add as a git submodule to your project:

```bash
git submodule add https://github.com/8lys-devgroup/cursor-rules.git .cursor/rules/shared
```

To update rules in existing projects:

```bash
git submodule update --remote .cursor/rules
```

## Adding New Rules

1. Create a `.mdc` file at repo root
2. Commit and push
3. Update submodules in dependent projects
