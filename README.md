<div align="center">
  <a href="https://v2.nonebot.dev/store"><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/nbp_logo.png" width="180" height="180" alt="NoneBotPluginLogo"></a>
  <br>
  <p><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/NoneBotPlugin.svg" width="240" alt="NoneBotPluginText"></p>
</div>

<div align="center">

# nonebot-plugin-moyu

_✨ 摸鱼一时爽, 一直摸鱼一直爽 ✨_


<a href="./LICENSE">
    <img src="https://img.shields.io/github/license/A-kirami/nonebot-plugin-moyu.svg" alt="license">
</a>
<a href="https://pypi.python.org/pypi/nonebot-plugin-moyu">
    <img src="https://img.shields.io/pypi/v/nonebot-plugin-moyu.svg" alt="pypi">
</a>
<img src="https://img.shields.io/badge/python-3.8+-blue.svg" alt="python">

</div>

## 💿 安装

<details>
<summary>使用 nb-cli 安装</summary>
在 nonebot2 项目的根目录下打开命令行, 输入以下指令即可安装

    nb plugin install nonebot-plugin-moyu

</details>

<details>
<summary>使用包管理器安装</summary>
在 nonebot2 项目的插件目录下, 打开命令行, 根据你使用的包管理器, 输入相应的安装命令

<details>
<summary>pip</summary>

    pip install nonebot-plugin-moyu
</details>
<details>
<summary>pdm</summary>

    pdm add nonebot-plugin-moyu
</details>
<details>
<summary>poetry</summary>

    poetry add nonebot-plugin-moyu
</details>
<details>
<summary>conda</summary>

    conda install nonebot-plugin-moyu
</details>

打开 nonebot2 项目的 `bot.py` 文件, 在其中写入

    nonebot.load_plugin('nonebot_plugin_moyu')

</details>

## 🎉 使用
### 指令表
| 指令  | 说明 |
|:-----:|:----:|
| 摸鱼/摸鱼日历 | 查看今天的摸鱼日历 |
| 摸鱼/摸鱼日历+设置 | 以连续对话的形式设置摸鱼日历的推送时间 |
| 摸鱼/摸鱼日历+设置 小时:分钟 | 设置摸鱼日历的推送时间 |
| 摸鱼/摸鱼日历+状态 | 查看本群的摸鱼日历状态 |
| 摸鱼/摸鱼日历+禁用 | 禁用本群的摸鱼日历推送 |