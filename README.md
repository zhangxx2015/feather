# feather
a lightweight cross platform GUI system with pure algorithm

**NOTE: this project is highly experimental for now. use at your own risk.**

## Introduction
#### Using quickjs to compile components and SDL to realize cross platform application.

## supported platform
- 64-bit debain linux
- 64-bit windows
- 64-bit macos

### prerequisite
    QuickJS https://bellard.org/quickjs/
    SDL http://www.libsdl.org/

## Todos

- [x] MVC

- Chinese inputting method
    - [x] pinyin1
    - [x] wubi

- Event queue
    - [x] keyboard
    - [x] mouse
    - [ ] touch

- animation
    - [x] transform
    - [x] transtion

- filter
    - [x] brightness
    - [x] contrast
    - [x] saturation
    - [x] gradient
    - [x] alpha blend

- [ ] Ture Type Font support
- [ ] tween
- [ ] acceleration
- [ ] dirty rect
- [ ] XML layout
- [ ] dithering
- [ ] i18n

- responsive grid system
    - [ ]

- layout
    - [ ] absolutePosition
    - [ ] flowLayoutPosition
    - [ ] borderLayoutPosition
    - [ ] gridLayoutPosition

### Features
- widgets

| Base                  | Data                  | Layout                | Navigation            | Utils                 |
|  :------------------- |  :------------------- |  :------------------- |  :------------------- |  :------------------- |
|- [√] label            |- [√] listBox          |- [√] tabPanel         |- [√] menu             |- [√] fps-meter        |
|- [√] button           |- [√] dataGrid         |- [ ] panel            |- [√] calendar         |- [√] clock            |
|- [√] check            |- [√] treeView         |- [ ] collapse         |- [√] suspensionBall   |- [√] screen-keyboard  |
|- [√] radio            |- [√] chart            |- [ ] layout           |- [ ] splitter         |- [√] dialog           |
|- [√] editor           |                       |- [ ] toolbar          |                       |- [√] carousel         |
|- [√] password         |                       |                       |                       |- [√] waveView         |
|- [√] progress         |                       |                       |                       |- [ ] gauge            |
|- [√] slider           |                       |                       |                       |- [ ] console          |
|- [√] dropdown         |                       |                       |                       |                       |
|- [√] colorPicker      |                       |                       |                       |                       |
|- [ ] spinner          |                       |                       |                       |                       |
|- [ ] switcher         |                       |                       |                       |                       |
|- [ ] textarea         |                       |                       |                       |                       |
|- [ ] tooltip          |                       |                       |                       |                       |
|- [ ] badge            |                       |                       |                       |                       |
|- [ ] rate             |                       |                       |                       |                       |
|- [ ] avatar           |                       |                       |                       |                       |

