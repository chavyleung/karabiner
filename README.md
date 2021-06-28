# Karabiner 单键切换输入法配置

通过 短按 ( `⌘` | `⌥` ) 切换 `中`、`英` 输入法

1. 短按 左 Command `⌘` 切换 `ZH`
2. 短按 右 Command `⌘` 切换 `EN`
3. 短按 左 Option `⌥` 切换 `EN`

4. 短按 左 Shift `⇧` 切换 `EN`
5. 短按 左 Shift `⇧` 轮换 **（与前一项冲突，请二选一）**

6. 短按 `Caps Lock` 切换 `EN`
7. 替换 `Caps Lock` 为组合键: `⌃` + `⌘` + `⌥` + `⇧`

## 安装

### 第一种：远程导入

复制到浏览器打开

```
karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/chavyleung/karabiner/main/karabiner.json
```

### 第二种：本地安装

把 `karabiner.json` 复制到: `~/.config/karabiner/assets/complex_modifications` 下

## 然后

关掉中文输入法的 `中英` 切换快捷键

## 为什么

由于，我们码字的时候经常不知道当前是处于哪个输入法，中文输入法还有 `中英` 两种状态

另外， `macOS` 切换 `中` \ `英` 状态时还有可能会失败 (延时原因)

所以，我希望：

1. 短按 `⌘` 的时候切到中文输入法
2. 短按 `⌥` 的时候切到中文输入法

这样我就不用盲猜当前输入法是什么状态了

## 其他说明

关于：6. 替换 Caps Lock 为组合键: `⌃` + `⌘` + `⌥` + `⇧`

因为我有些快捷键是：

`⌃` + `⌘` + `⌥` + `⇧` + `D`：选词翻译

`⌃` + `⌘` + `⌥` + `⇧` + `S`：识图翻译

`⌃` + `⌘` + `⌥` + `⇧` + `C`：使用 Code 打开当前目录

`⌃` + `⌘` + `⌥` + `⇧` + `T`：使用 终端 打开当前目录

这样我只需要 `Caps Lock` + `D` 就可以选词翻译了

> 如果不需要，可以 `Remove` 这个映射
