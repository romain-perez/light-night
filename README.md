# Light Night

A dark VS Code theme that uses the **color logic of VS Code's default light theme** (Light+ / Light Modern): one color = one role, so you can read code at a glance.

## Colors by role

| Role | Example | Color |
|---|---|---|
| Modifiers | `public static final class` | `#4fc1ff` **bold** |
| Control flow | `if return new throw` | `#da70d6` *italic* |
| Types | `String`, `int`, `List<T>`, `@Override` | `#4ec9b0` (interfaces *italic*) |
| `this`, `null`, `true` | | `#4fc1ff` |
| Local variable | `result` | `#fcf8ec` |
| Parameter | `title` | `#9cdcfe` *italic* |
| Field / attribute | `this.name` | `#f07178` |
| Method / function | `getName()` | `#ffb454` |
| Constant, enum value | `MAX_SIZE`, `Status.ACTIVE` | `#f29668` **bold** |
| String | `"hello"` | `#c3e88d` |
| Number | `42` | `#b5cea8` |
| Comment | `// ...` | `#7f8a9e` *italic* |
| Operators, punctuation | `a = b`, `;` | `#bfc7d5` |

Role-based colors for Java need the **Language Support for Java by Red Hat** extension (semantic tokens).

### Bash

Commands in gold (like methods), options and tests in cyan, variable reads in light blue, `$1` / `$@` in light blue italic, `|`, `&&`, `>` in orchid.

### TypeScript / JavaScript

`import` and `export` in bold orchid.

## Install

Clone the repository into the VS Code extensions folder, then reload VS Code and pick **Light Night** (`Ctrl+K` `Ctrl+T`).

```bash
# Linux / macOS
git clone https://github.com/Dainji-dev/light-night.git ~/.vscode/extensions/dainji.light-night-1.0.0
# Windows (PowerShell)
git clone https://github.com/Dainji-dev/light-night.git "$HOME\.vscode\extensions\dainji.light-night-1.0.0"
```

Update: `git pull` in that folder, then *Developer: Reload Window*.

## Credits

Interface colors based on Palenight and Ayu Mirage. Syntax color layout inspired by VS Code's Light+ theme.
