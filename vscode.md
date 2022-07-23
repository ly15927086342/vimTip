# vscode快捷键

[keyboard-shortcuts-macos.pdf](./keyboard-shortcuts-macos.pdf)

## 终端

|功能|快捷键|
|:--|:--|
|打开/关闭终端|ctrl+`|
|新建窗口|command+\|
|关闭窗口|command+w|

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
