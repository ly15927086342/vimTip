# vscode快捷键

[keyboard-shortcuts-macos.pdf](./keyboard-shortcuts-macos.pdf)

## 通过vim命令调用vscode命令

在setting.json中vim.normalModeKeyBindings下，配置

```json
{
  "before": ["vim命令"],
  "command": ["vscode命令id"]
}
```

`tip`vscode命令id搜索keyboard，对应文件中可以查询，例如editor.action.formatDocument

## 操作文件
 
`tip`以下命令部分是配置的

|功能|快捷键|
|:--|:--|
|切换到资源管理器/编辑器|ctrl+;|
|移动/折叠/展开/进入文件|jk/h/l|
|创建文件(在file explorer中)|a|
|创建文件夹（在file explorer中）|shift+a|
|重命名文件/夹|r|
|删除文件/夹|d|

## 操作多个vscode窗口

|功能|快捷键|
|:--|:--|
|打开新的vscode窗口|shift+command+n|
|选择工作区|ctrl+r|
|切换窗口|command+`|
|关闭窗口|command+w|

`tip`分屏无法切换

## 搜索

|功能|快捷键|
|:--|:--|
|搜索当前文件的定义|command+t|
|查看当前文件的结构|command+shift+o|
|查看当前文件的结构，按类别分组|command+shift+o+:|
|搜索vscode配置|command+shift+p|
|快速文件导航|command+p|
|切换文件|ctrl+tab|
|全局搜索|command+shift+f|
|切换聚焦区|command+up/down|
|触发查询条件模块|command+shift+j|

## 编码

|功能|快捷键|
|:--|:--|
|代码提示|command+.|
|参数提示|command+shift+空格|
|建议提示|command+i|
|移动行|option+up/down|
|增加行|command+回车|
|删除前面的单词|option+删除|
|选中所有单词|command+f2|

## 重构

|功能|快捷键|
|:--|:--|
|重构提示|command+.|
|Abracadabra插件||

## 终端

|功能|快捷键|
|:--|:--|
|打开/关闭终端|ctrl+`|
|分屏|command+\|
|清空终端|command+k|
|切换分屏|command+[|
|关闭窗口|shift+option+q|
|新建窗口|shift+option+n|
|切换窗口|shift+command+[|
|打开终端程序|shift+command+c|