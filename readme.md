<div align="center">
<h1>Translater</h1>
<p>一个用于<a href=https://github.com/microsoft/PowerToys>PowerToys Run</a>的翻译插件, 快速, 稳定.</p>

![release](https://badgen.net/github/release/N0I0C0K/PowerToysRun.Plugin.Translater) ![issue](https://badgen.net/github/issues/N0I0C0K/PowerToysRun.Plugin.Translater) ![star](https://badgen.net/github/stars/N0I0C0K/PowerToysRun.Plugin.Translater?color=green)

[English](./readme_en.md)

</div>

## About

一个用于[PowerToysRun](https://github.com/microsoft/PowerToys)的插件.

现已更新到有道翻译, **支持有道翻译的全部语言翻译**.

## Usage

- 默认触发键为`^`.(当前默认触发键会和 Everything 插件冲突, 可以参考下面的方式修改触发)
- 指定翻译文本

  - `alt+space`打开 PowerToysRun, 输入`^[你要翻译的地方]`
  - `Enter`复制翻译结果到剪贴板

  演示翻译 `command`
  ![command](Images/command.gif)

  演示翻译 `命令`
  ![chinese](Images/%E5%91%BD%E4%BB%A4.gif)

- 中文带有拼音
  参考上方演示翻译`命令`

- 快速翻译剪贴板

  - 当剪贴板内有文字, 直接键入触发关键字`^`, 即可快速翻译剪贴板内的内容

    ![clipboard](Images/clipboard.gif)

- 指定翻译目标语言

  - 使用 `^[words]->[Target language]`, 例如: `^你好->ja` 表示把你好翻译为日文
    ![Specified language](Images/target%20lan.gif)

- 搜索建议
  - 根据当前的输入建议搜索内容
    ![suggest](Images/suggest.gif)
  - 你可以在设置里取消
    ![suggest setting](Images/suggest_setting.png)

常用语言代码
|语言|代码|备注|
|---------|------|-|
|汉语(简体) | zh-CHS | 汉语简体
|汉语(繁体) | zh-CHT| 漢語翻譯
|日语 |ja| 日本語
|英语 |en| English
|韩语 |ko| 한국어
|法语 |fr| En français
|俄语 |ru| русск

## Install

1. 关闭 PowerToys
2. 下载 [Translater.zip](https://github.com/N0I0C0K/PowerToysRun.Plugin.Translater/releases)
3. 解压到`{安装目录}\modules\launcher\Plugins\`
   如图所示
   ![file](Images/file.png)
4. 启动 PowerToys

## Setting

- 修改默认触发键 (如果需要修改,建议修改为" ` ", 同时建议检查一下有无冲突)
  ![change active key](Images/change_active.png)
- 建议勾选`启动时清除上一查询`, 可以解决剪贴板快速翻译不能触发的问题
  ![auto clean](Images/auto_clean.png)
- 建议勾选, 可以优化输入体验
  ![enable Smooth input](Images/enable%20Smooth%20input.png)

## Issue

如果发现了无法翻译, 出现了未知错误, 需要新的功能, 欢迎提交 issue. 我会及时修复或改进
