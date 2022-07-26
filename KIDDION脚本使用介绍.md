



# KID扩展脚本使用介绍

> 编辑：konev5



##  简介与操作
- kiddion脚本文件格式：***.lua
- 新建笔记本-另存为-文件格式选为所有文件

<img src=https://img.kookapp.cn/assets/2022-07/qHnUHTvGpS0i003e.png>

- ***.lua需要放置在与kiddion程序同文件夹的`SCRIPT`（不区分大小写）文件夹内

<IMG SRC=https://img.kookapp.cn/assets/2022-07/KIx94VewOb0j60bq.png>

- 应当使用对应游戏版本的kiddion以及脚本


##  简要描述

- 目前大家所最多使用的（GTAOL)stat编辑器是 GTAhaxUI，而kid脚本可以快速引用编辑，仅仅在终端点击即可代替代码编辑操作



## 脚本代码示例

 ```
local function Text(text)
 menu.add_action(text, function() end)
end

Text("KONEV5")
Text("GTA6CLUB")

menu.add_action("Up-n-Atomizer", function()
		globals.set_int(102764, 90)
end)
menu.add_action("Festive tint", function()
		globals.set_int(102765, 1)
end)
```


##  其他
- 首次将脚本放置后需要刷新kid菜单刷新脚本或者重启kid（自动读取）
- 由于大部分的代码为globals（该类代码随游戏版本更迭而变动），故此类代码都放置在社区 https://bbs.bbfas.com/

## 感谢
- bbfas所携带的kiddion脚本由Alice制作。
- 特别感谢Alice.

## 参阅地址
- 可打开https://www.unknowncheats.me/forum/grand-theft-auto-v/463868-modest-menu-lua-scripting-megathread.html

##  备注

- 更多代码请返回上级页面查看或搜索
