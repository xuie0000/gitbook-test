# 安装极点五笔

## 1. 将键盘输入修改为`fcitx`
设置->区域与语言->管理已安装的语言->键盘输入法系统->`fcitx`

## 2. `sudo apt install fcitx-table-wbpy`后，再重启系统。

```
//拼音：
fcitx-pinyin、fcitx-sunpinyin、fcitx-googlepinyin，
//五笔：
fcitx-table、fcitx-table-wubi、fcitx-table-wbpy（五笔拼音混合）
```

## ~~3. switch~~
```
    sudo im-config -s fcitx
```
