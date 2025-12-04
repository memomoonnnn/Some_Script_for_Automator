# Some Scripts for Automator

一些用于Automator的脚本

**由Gemini编写**

---

每个文件夹对应一个workflow，为文件夹添加后缀`.workflow`即可变成MacOS上的“工作流程”文件。

安装后可出现在右键菜单里。

使用ffmpeg对音频进行重编码，以及从视频里提取出对应的音频流。

ffmpeg库默认路径为`/opt/homebrew/bin/ffmpeg`。

ncm转换使用ncmdump库，默认路径为`/opt/homebrew/bin/ncmdump`。

默认ncm转换结果输出到一个统一的指定目录，需要修改变量`OUTPUT_DIR`的值。
