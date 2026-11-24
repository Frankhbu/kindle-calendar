# 字体目录

把篆体字体文件放在这里，命名为 **`zhuan.ttf`**（或 `zhuan.otf`），日历页面的「字体 → 篆体」就能生效。

macOS / Windows 系统都不自带篆体，需要自己准备字体文件，例如：

- 方正小篆体（`FZXiaoZhuanTi.ttf`）
- 汉仪篆书繁（`HYZhuanShuF.ttf`）
- 华文篆书（`STZhuanShu.ttf`，旧版 macOS 附加字体）

拿到 `.ttf` / `.otf` 后直接改名复制过来即可，无需改代码：

```bash
cp ~/Downloads/FZXiaoZhuanTi.ttf fonts/zhuan.ttf
```

如果系统已经安装了篆体字体（Font Book 里能看到），也可以不用这个目录：
页面里的字体栈会按名字查找 `方正小篆体`、`汉仪篆书繁`、`STZhuanShu`、`华文篆书` 等常见家族名。

注意：

- 请使用自己有权使用的字体文件，商用请购买授权。
- 篆体字库通常只覆盖常用汉字，数字、字母可能回退成系统字体。
