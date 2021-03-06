# 深入异步:执行Future和任务

在本节中，我们将介绍如何调度Futures和异步任务的内部结构。如果您只想学习如何编写使用现有Future类型的高级代码，并且对`Future`类型的工作方式不感兴趣，可以跳到`async/await`章节。但是，有几个本章讨论的主题是如何理解`async/await`代码工作，了解`async/await`代码的运行时间和性能性能，并建立新的异步原语。如果您现在决定跳过此部分，可能需要将其加入书签以便将来重新访问。

现在，通过这种方式，让我们谈谈这个`Future`特质。
