# Dia-OneClick
对话型文字转语音合成软件Dia-1.6B免安装部署一键启动整合包

![](https://raw.githubusercontent.com/aidayang/Dia-OneClick/refs/heads/main/dia.jpg)


## Dia-1.6B一键启动整合包使用说明

首先将网盘内的软件压缩包下载到本地电脑上并解压。然后双击启动软件.exe启动。

软件成功启动后会自动打开webUI界面。

在Input Text里输入对话文本，[S1]开头，就是人物1，后面跟说话内容。然后再跟[S2]，就是人物2，依次交替。

Audio Prompt里可以上传5-10秒的音频用于音色克隆，也可以忽略。

点击下方的Generate Audio按钮开始生成音频。

默认使用GPU处理，耗时由英伟达显卡配置决定。

下面Generation Parameters里还有一些参数设置，感兴趣的可以自行调节测试。

注意：

保持输入文本长度适中

短输入（相当于 5 秒以下的音频）听起来会不自然

非常长的输入（相当于超过 20 秒的音频）会使语音不自然地快。

请谨慎使用非语言标签，过度使用或使用未列出的非语言标签可能会导致奇怪的问题。

始终以[S1]开始输入文本，并始终在[S1]和[S2]之间交替（不要[S1]…[S1]…）

使用音频提示（语音克隆）时，请仔细遵循以下说明：

在生成文本之前提供待克隆音频的文字记录。

成绩单必须正确使用[S1]、[S2]发言者标签（即单个发言者：[S1]…、两个发言者：[S1]…… [S2]）

为了获得最佳效果，待克隆音频的时长应为 5 到 10 秒。（请注意：1 秒 ≈ 86 个 token）

将[S1]或[S2]（倒数第二个说话者的标签）放在音频末尾，以提高结尾的音频质量

软件暂时以英语合成为主，还不能生成中文语音。

非语言音效代码：

(laughs), (clears throat), (sighs), (gasps), (coughs), (singing), (sings), (mumbles), (beep), (groans), (sniffs), (claps), (screams), (inhales), (exhales), (applause), (burps), (humming), (sneezes), (chuckle), (whistles)

视频教程及效果演示：https://www.youtube.com/watch?v=GUTmegDX3VM

## 注意事项
英伟达显卡显存6G可用，但是速度略慢，建议英伟达显存更高电脑使用

支持英伟达50系列显卡

使用前请将英伟达显卡驱动更新到最新版本

只支持Windows 10或11

软件运行路径中不要有非英文字符和空格，待处理文件素材也要注意

## 对话型文字转语音软件Dia下载链接
https://pan.quark.cn/s/1cc00b4dc89c

## 原项目链接
https://github.com/nari-labs/dia
