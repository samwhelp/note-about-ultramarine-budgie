---
title: 鍵盤按鍵綁定一覽表
nav_order: 9010
has_children: false
parent: 一覽表
---


# 鍵盤按鍵綁定一覽表

> 概覽 / [工作流程](https://samwhelp.github.io/note-about-ultramarine-budgie/read/guide/workflow)

> [鍵盤按鍵綁定說明](https://samwhelp.github.io/note-about-ultramarine-budgie/read/config/keybind.html)

> 如何 / [設定「按鍵綁定」](https://samwhelp.github.io/note-about-ultramarine-budgie/read/howto/config-keybind.html)




## 主題

* [系統操作](#系統操作)
* [開啟應用程式](#開啟應用程式)
* [視窗操作](#視窗操作)
* [切換](#切換)
* [相關連結](#相關連結)




## 系統操作


## 系統操作 / 離開系統

| 按鍵組合           | 功能    | 執行指令                         |
| ------------------ | ----- | -------------------------------- |
| `Alt + Shift + z`  | 關機  | `budgie-session-quit --reboot` |
| `Alt + Shift + x`  | 登出  | `budgie-session-quit --logout` |




## 開啟應用程式


## 開啟應用程式 / 透過「應用程式啟動器」

| 按鍵組合     | 功能                                 | 設定項目                                                |
| ----------- | ----------------------------------- | ----------------------------------------------------- |
| `Alt + F1`  | `開啟「應用程式啟動主選單(Main Menu)」`  | 目前沒有作用 |
| `Alt + F2`  | `開啟「應用程式啟動器(Runner)」`        | `org.gnome.desktop.wm.keybindings panel-run-dialog`  |


> 關於「`Alt + F1`」目前沒有作用。

> 在『[停用按鍵綁定「Super_L」開啟「Main Menu」](https://samwhelp.github.io/note-about-ultramarine-budgie/read/howto/disable-keybind-open-main-menu.html)』這篇有提到原本預設是綁定「`Super_L`」，只是這個設定，測試結果，只能設定單一按鍵。為了避免干擾，所以被我停用了。




## 開啟應用程式 / 透過「Rofi」

| 按鍵組合          | 功能                           | 執行指令                        |
| ----------------- | ------------------------------ | ------------------------------- |
| `Alt + Shift + d` | 開啟 Rofi (可用應用程式列表)   | `rofi -show drun -show-icons`   |
| `Alt + Shift + w` | 開啟 Rofi (已經開啟的視窗列表) | `rofi -show window -show-icons` |
| `Alt + Shift + r` | 開啟 Rofi (可用指令列表)       | `rofi -show run`                |




## 開啟應用程式 / Terminal

| 按鍵組合           | 功能           | 執行指令           |
| ------------------ | -------------- | ------------------ |
| `Alt + Enter`      | 開啟 Terminal  | `gnome-terminal`  |
| `Alt + Shift + a`  | 開啟 Terminal  | `gnome-terminal`  |
| `Alt + Ctrl + a`   | 開啟 Terminal  | `sakura`           |
| `Alt + Shift + t`  | 開啟 Terminal  | `xfce4-terminal`   |
| `Alt + Ctrl + t`   | 開啟 Terminal  | `qterminal`        |




## 開啟應用程式 / 常用的應用程式

| 按鍵組合           | 功能            | 執行指令                         |
| ------------------ | --------------- | -------------------------------- |
| `Alt + Shift + f`  | 開啟檔案管理器  | `nemo`             |
| `Alt + Shift + g`  | 開啟檔案管理器  | `thunar`                     |
| `Alt + Shift + e`  | 開啟文字編輯器  | `gedit`              |
| `Alt + Shift + b`  | 開啟網頁瀏覽器  | `firefox --new-tab about:blank`  |
| `Alt + Shift + s`  | 開啟系統設定    | `budgie-control-center`                |




## 視窗操作

| 按鍵組合   | 功能                               | 設定項目                       |
| ---------- | ---------------------------------- | ------------------------------ |
| `Alt + Space`  | 顯示「視窗功能選單」  | `org.gnome.desktop.wm.keybindings activate-window-menu`            |
| `Win + q`  | 關閉視窗                           | `org.gnome.desktop.wm.keybindings close`                |
| `Win + f`  | 視窗全螢幕                         | `org.gnome.desktop.wm.keybindings toggle-fullscreen`           |
| `Win + w`  | 視窗最大化                         | `org.gnome.desktop.wm.keybindings toggle-maximized`             |
| `Win + x`  | 視窗最小化                         | `org.gnome.desktop.wm.keybindings minimize`             |
| `Win + d`  | 切換顯示桌面                         | `org.gnome.desktop.wm.keybindings show-desktop`             |
| `Win + e`  | 開始「視窗移動」                   | `org.gnome.desktop.wm.keybindings begin-move`                 |
| `Win + r`  | 開始「視窗更改大小」               | `org.gnome.desktop.wm.keybindings begin-resize`               |
| `Win + y`  | 視窗內容區塊收合                   | `org.gnome.desktop.wm.keybindings toggle-shaded`                |
| `Win + t`  | 視窗保持永遠在最上方               | `org.gnome.desktop.wm.keybindings toggle-above`  |
| `Win + z`  | 在最近聚焦過的兩個視窗切換               | `org.gnome.desktop.wm.keybindings raise-or-lower`  |


> 一般預設「`Alt + F4`」綁定「`視窗關閉`」

> 一般預設「`F11`」綁定「`視窗全螢幕`」




## 切換

## 切換 / 視窗

| 按鍵組合     | 功能                    | 設定項目                                       |
| ------------ | ----------------------- | ---------------------------------------------- |
| `Win + a`    | 聚焦切換到「前面一個視窗」  | `org.gnome.desktop.wm.keybindings switch-windows-backward`              |
| `Win + s`    | 聚焦切換到「後面一個視窗」  | `org.gnome.desktop.wm.keybindings switch-windows `                        |

> 一般預設「`Alt + Tab`」綁定「`視窗聚焦切換`」




## 切換 / 工作空間

| 按鍵組合   | 功能                  | 設定項目                            |
| ---------- | --------------------- | ----------------------------------- |
| `Alt + a`  | 切換到「上一個工作空間」  | `org.gnome.desktop.wm.keybindings switch-to-workspace-left`   |
| `Alt + s`  | 切換到「下一個工作空間」  | `org.gnome.desktop.wm.keybindings switch-to-workspace-right`  |




## 切換 / 概覽

> 無「概覽」相關功能。




## 相關連結

| 相關連結 |
| ------- |
| [鍵盤按鍵綁定](https://samwhelp.github.io/note-about-ultramarine-budgie/read/config/keybind.html) |
