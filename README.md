# Vs Code PowerUser

Tutorials and Pro Tips to use Visual Studio Code as your main IDE.

## Introduction

![Example Image](asset/test.png)

## IDE Setup

### General

`(...)`

### TypeScript / JavaScript

`(...)`

### Java

`(...)`

### Golang

`(...)`

## Productivity Tweaks

### General

`(...)`

#### Shortcuts

| Function                       | Shortcut                         |
|--------------------------------|----------------------------------|
| Command Handler                | `F1` or `Ctrl+Shift+P`           |
| Toggle Terminal                | `Ctrl+Shift+¨`                   |
| Toggle Terminal (linux)        | `Ctrl+Shift+^`                   |
| Search Files                   | `Ctrl+P`                         |
| Format Code                    | `Alt+Shift+F`                    |
| Organize Imports               | `Alt+Shift+O`                    |
| Toggle Comment                 | `Ctrl+K,Ctrl+C` or `Ctrl+§`      |

### TypeScript / JavaScript

`(...)`

### Java

`(...)`

### Golang

`(...)`

## Troubleshooting

### General

`(...)`

### TypeScript / JavaScript

`(...)`

### Java

#### Imports get discarded on save

**Problem:**

This generally happens when you have enabled to organize imports on save, when parsing of the Java Source fails, the imports are discarded.

**Solution:**

Either only save when you are sure that your source file is valid or remove the following Setting from your `settings.json`:

```json
"editor.codeActionsOnSave": {
    "source.organizeImports": true
}
```

> **NB:** You can undo the removed imports by pressing the `undo` shortcut (`Ctrl+Z`)

### Golang