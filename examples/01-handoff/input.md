# 场景：长对话里的交接记录

## 用户材料

我在 Mac 上用普通的 Claude 聊天窗口，没有用 Claude Code 或终端。长对话压缩以后，经常会丢掉我们已经做出的决定、文件名，还有工作进行到了哪里。我最先想到的是，让它在压缩前写一份交接文档，但它似乎不能可靠地知道什么时候会压缩，等到要写时可能已经太晚，或者记录已经不是最新的。

我现在想到的办法是，不等压缩，每次回复之后都更新一份 HANDOFF.md，这样发生压缩或开始新聊天时，就已经有最新记录可以读。我想让一个 AI 帮我把这件事处理好。

## 给编写提示词的 AI 的任务

根据上面的情况，整理一份可以直接发给另一个 AI Agent 的任务提示词，让它接手处理。只输出这份提示词。

## 来源与场景性质

依据 [Can you force Claude to write a handoff .md file before a chat gets compacted?](https://www.reddit.com/r/ClaudeAI/comments/1wui0hj/can_you_force_claude_to_write_a_handoff_md_file/)，作者 u/Glass-Present-8753；2026-10-24 获取。
上文是本项目对作者公开问题和想法的中文整理，不是逐字翻译。让另一个 Agent 接手的任务由本项目设置。没有获得原作者的完整聊天或交接文件，不代表原作者曾使用本协作文档。

