# feather
a lightweight cross platform GUI system with pure algorithm

写于2020年春节抗疫期间,整理文档,准备开源...
Written in Spring Festival in 2020(fighting covid-19)
an based pure Algorithm GUI framework library, sorting out documents, about to open source.


**NOTE: this project is highly experimental for now. use at your own risk.**

## Introduction
#### Using quickjs to compile components and SDL to realize cross platform application.

![screenshot](https://github.com/zhangxx2015/feather/blob/master/screenshot/bar+popup.png?raw=true)
![screenshot](https://github.com/zhangxx2015/feather/blob/master/screenshot/colorPicker.png?raw=true)
![screenshot](https://github.com/zhangxx2015/feather/blob/master/screenshot/dialog.png?raw=true)
![screenshot](https://github.com/zhangxx2015/feather/blob/master/screenshot/grid+pinyin.png?raw=true)
![screenshot](https://github.com/zhangxx2015/feather/blob/master/screenshot/line+ball.png?raw=true)
![screenshot](https://github.com/zhangxx2015/feather/blob/master/screenshot/pie+password.png?raw=true)
![screenshot](https://github.com/zhangxx2015/feather/blob/master/screenshot/radar+slider.png?raw=true)
![screenshot](https://github.com/zhangxx2015/feather/blob/master/screenshot/tree+wubi.png?raw=true)
![screenshot](https://github.com/zhangxx2015/feather/blob/master/screenshot/wave+menu.png?raw=true)

## supported platform
- 64-bit debain linux
- 64-bit windows
- 64-bit macos

### prerequisite
    QuickJS https://bellard.org/quickjs/
    SDL http://www.libsdl.org/

### Todos

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







