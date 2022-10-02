---
title: 視窗基本操作
nav_order: 5020
has_children: false
parent: xerolinux-adjustment
grand_parent: 設定
---


# 視窗基本操作

* [關閉視窗](#關閉視窗)
* [全螢幕](#全螢幕)
* [最大化](#最大化)
* [最小化](#最小化)
* [開始視窗移動](#開始視窗移動)
* [開始視窗更改大小](#開始視窗更改大小)
* [永遠在最上方](#永遠在最上方)
* [永遠在最下方](#永遠在最上方)
* [內容區塊收合](#內容區塊收合)
* [切換顯示隱藏視窗裝飾](#切換顯示隱藏視窗裝飾)
* [將下方視窗移上來](#將下方視窗移上來)
* [視窗移動至中央部位](#視窗移動至中央部位)


## 關閉視窗

* [設定片段](https://github.com/samwhelp/xerolinux-adjustment/blob/main/prototype/xerolinux/part/xerolinux-keybind-main/config/xerolinux/kglobalshortcutsrc#L133)

| 按鍵組合          | 功能     | 執行指令         |
| ----------------- | -------- | ---------------- |
| `Win + q`         | 關閉視窗 | `Window Close` |


## 全螢幕

* [設定片段](https://github.com/samwhelp/xerolinux-adjustment/blob/main/prototype/xerolinux/part/xerolinux-keybind-main/config/xerolinux/kglobalshortcutsrc#L134)

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + f` | 視窗全螢幕 | `Window Fullscreen` |


## 最大化

* [設定片段](https://github.com/samwhelp/xerolinux-adjustment/blob/main/prototype/xerolinux/part/xerolinux-keybind-main/config/xerolinux/kglobalshortcutsrc#L138)

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + w` | 最大化 | `Window Maximize` |
| `Win + PgUp` | 最大化 | `Window Maximize` |

> 也可以在「標題列」，使用「滑鼠左鍵」，點選兩下，切換視窗最大化。


## 最小化

* [設定片段](https://github.com/samwhelp/xerolinux-adjustment/blob/main/prototype/xerolinux/part/xerolinux-keybind-main/config/xerolinux/kglobalshortcutsrc#L141)

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + x` | 最小化 | `Window Minimize` |
| `Win + PgDown` | 最小化 | `Window Minimize` |


## 開始視窗移動

* [設定片段](https://github.com/samwhelp/xerolinux-adjustment/blob/main/prototype/xerolinux/part/xerolinux-keybind-main/config/xerolinux/kglobalshortcutsrc#L142)

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + e` | 開始視窗移動 | `Window Move` |

> 按「Escape」鍵，取消「開始視窗移動」。


## 開始視窗更改大小

* [設定片段](https://github.com/samwhelp/xerolinux-adjustment/blob/main/prototype/xerolinux/part/xerolinux-keybind-main/config/xerolinux/kglobalshortcutsrc#L164)

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + r` | 開始視窗更改大小 | `Window Resize` |

> 按「Escape」取消「開始視窗更改大小」。


## 永遠在最上方

* [設定片段](https://github.com/samwhelp/xerolinux-adjustment/blob/main/prototype/xerolinux/part/xerolinux-keybind-main/config/xerolinux/kglobalshortcutsrc#L131)

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + t` | 永遠在最上方 | `Window Above Other Windows` |


## 永遠在最下方

* [設定片段](https://github.com/samwhelp/xerolinux-adjustment/blob/main/prototype/xerolinux/part/xerolinux-keybind-main/config/xerolinux/kglobalshortcutsrc#L132)

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + b` | 永遠在最下方 | `Window Below Other Windows` |


## 內容區塊收合

* [設定片段](https://github.com/samwhelp/xerolinux-adjustment/blob/main/prototype/xerolinux/part/xerolinux-keybind-main/config/xerolinux/kglobalshortcutsrc#L165)

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + y` | 內容區塊收合 | `Window Shade` |


## 切換顯示隱藏視窗裝飾

* [設定片段](https://github.com/samwhelp/xerolinux-adjustment/blob/main/prototype/xerolinux/part/xerolinux-keybind-main/config/xerolinux/kglobalshortcutsrc#L144)

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + n` | 切換顯示隱藏視窗裝飾(Decorations) | `Window No Border` |

> 視窗裝飾(Decorations)，最明顯的，就可以看到標題列隱藏或是顯示。


## 將下方視窗移上來

* [設定片段](https://github.com/samwhelp/xerolinux-adjustment/blob/main/prototype/xerolinux/part/xerolinux-keybind-main/config/xerolinux/kglobalshortcutsrc#L118)

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + z` | 將下方視窗移上來 | `Toggle Window Raise/Lower` |


## 視窗移動至中央部位

* [設定片段](https://github.com/samwhelp/xerolinux-adjustment/blob/main/prototype/xerolinux/part/xerolinux-keybind-main/config/xerolinux/kglobalshortcutsrc#L67)

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + m` | 視窗移動至中央部位 | `MoveWindowToCenter` |
