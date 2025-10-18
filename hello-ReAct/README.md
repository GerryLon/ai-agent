# agent之ReAct模式示例(参考： https://www.bilibili.com/video/BV1TSg7zuEqR/)

## 安装依赖
```
cd hello-ReAct
uv sync
```

## 运行
然后在当前目录下，新建一个叫做 .env 的文件，输入以下内容：

```
CHAT_API_KEY=xxx
```

xxx 就是你在 DeepSeek 上配好的 API Key。如果你不用 DeepSeek，那直接改下代码，换个别的 baseUrl 就行了。

确保 uv 已经安装成功后，进入到当前文件所在目录，然后执行以下命令即可启动：

```bash
mkdir -p snake
uv run agent.py snake

# 输入： 写一个贪吃蛇游戏, 使用HTML，css 和 js 实现，代码分别放在不同的文件中
```