



# GTAhaxUI教程及界面使用操作指引




> 编辑：konev5
##  必要的前置操作
- 游戏必须设置为窗口模式或无边窗口模式
- 必须先开启游戏再打开gtahaxui
- 应当使用对应游戏版本的gtahaxui

##  简要描述

- 目前大家所最多使用的（GTAOL)stat编辑器是 GTAhaxUI，其操作界面简单易懂
- <IMG SRC=https://img.kookapp.cn/assets/2022-07/Q0RYcs1AqB0bn0gx.png>

## 全局（Global）代码使用示例
-    ` Global_262145.f_30658=1 `

- ![](https://img.kookapp.cn/assets/2022-07/uQOjhdLrlD0640a9.png)
- 如图所示，全局代码编辑步骤：红→黄→绿→蓝(写入)
此区域为全局（Global）代码编辑
## （int）代码使用示例
- `$MP0_HEIST_PLANNING_STAGE
     -1`
- ![](https://img.kookapp.cn/assets/2022-07/cmMwzogVdN06202e.png)
- 如图所示，（int）代码编辑步骤：红→黄→绿(int更改)
- 此区域为（int）代码编辑
- 部分此类代码需要在特定地点使用，如设施等室内
- 部分此类代码在使用后需要更换战局以刷新
## （bool）代码使用示例
- `$MP0_LOW_FLOW_CS_FIN_SEEN  (true) (bool)`
- ![](https://img.kookapp.cn/assets/2022-07/1nXnsWQfFm065039.png)
- 如图所示，（bool）代码编辑步骤：红→黄(bool锁定)
- 此区域为（bool）代码编辑
- 游戏内需要先戴好一顶可以拉上拉下护目镜的帽子
- 此类代码在点击(bool锁定)前，游戏内护目镜拉下，点击(bool锁定)后，游戏内护目镜会自动拉上，此时在游戏内拉下护目镜则完成代码使用操作
- 备注为（flase）（bool）代码与上一条操作相反
- 如果状态已经解锁，则使用该类代码时游戏内护目镜无反应
## 导入使用示例
- ![](https://img.kookapp.cn/assets/2022-07/fY8LNqSEI506901l.png)
- 如图所示，导入代码直接点击导入即可
- 此区域为导入代码
- 在同一文件夹内，gtahaxui.exe可以导入stat.txt内的代码
- stat.txt代码规范→头为：int32 下附int代码及数值
- 使用条件与（int）一致

## 特别说明
- `$MPX_CHAR_SET_RP_GIFT_ADMIN //// Add MP0_ or MP1_`
- 在实际使用中，代码前必须要添加符号$
- 非导入代码，mp0为主角色，mp1为第二角色，不能使用mpx
- 导入的代码可以直接填为mpx，会自动应用于当前角色
- mpply起的代码为全局，不需要区分角色

## 备注

- 更多代码请返回上级页面查看或搜索
