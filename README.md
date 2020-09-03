# Vs Code PowerUser

Tutorials and Pro Tips to use Visual Studio Code as your main IDE.

## 1. Introduction

![Example Image](asset/test.png)

## 2. IDE Setup

### 2.1. General

`(...)`

### 2.2. TypeScript / JavaScript

`(...)`

### 2.3. Java

`(...)`

### 2.4. Golang

`(...)`

## 3. Productivity Tweaks

### 3.1. General

`(...)`

#### 3.1.1. Shortcuts

| Function                       | Shortcut                         |
|--------------------------------|----------------------------------|
| Command Handler                | `F1` or `Ctrl+Shift+P`           |
| Toggle Terminal                | `Ctrl+Shift+¨`                   |
| Toggle Terminal (linux)        | `Ctrl+Shift+^`                   |
| Search Files                   | `Ctrl+P`                         |
| Format Code                    | `Alt+Shift+F`                    |
| Organize Imports               | `Alt+Shift+O`                    |
| Toggle Comment                 | `Ctrl+K,Ctrl+C` or `Ctrl+§`      |


### 3.2. TypeScript / JavaScript

`(...)`

### 3.3. Java

### 3.3.1. Code Snippets

| Function                       | Snippet                          |
|--------------------------------|----------------------------------|
| Print stdout                   | `sysout`                         |
| Print stderr                   | `syserr`                         |
| Constructor skeletton          | `ctor`                           |

### 3.3.2. Code Generator

Following actions are available in the context menu at `Source Action...`:

| Function                       | Snippet                           |
|--------------------------------|-----------------------------------|
| Member copy constructor        | `Generate Constructors...`        |
| Accessors (get/set)            | `Generate Getters and Setters...` |


### 3.4. Golang

`(...)`

## 4. Troubleshooting

### 4.1. General

`(...)`

### 4.2. TypeScript / JavaScript

`(...)`

### 4.3. Java

#### 4.3.1. Java imports cannot be found

This generally happens when the Maven project is not updated correctly:

- Press `F1`
- Select `Java: Clean the Java language server workspace`

#### 4.3.2. Imports get discarded on save

This generally happens when you have enabled to organize imports on save, when parsing of the Java Source fails, the imports are discarded.

The solution is to either only save when you are sure that your source file is valid or to remove the following Setting from your `settings.json`:

```json
"editor.codeActionsOnSave": {
    "source.organizeImports": true
}
```

> **NB:** You can undo the removed imports by pressing the `undo` shortcut (`Ctrl+Z`)

### 4.4. Golang

`(...)`