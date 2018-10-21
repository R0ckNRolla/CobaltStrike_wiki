# 什么是Cobalt Strike？
`Cobalt Strike`是主要用于`apt`(高级持续威胁)攻击的软件，能对目标进行针对性攻击。本节介绍`Cobalt Strike`的功能支持过程。 本手册的其余部分将会详细讨论了这些功能。

![The Path to Post Exploitation](https://raw.githubusercontent.com/evilwing/wing-images/master/img/20181022024023.png)

通过前期的侦察然后开始对你的目标攻击。`Cobalt Strike`的系统分析器是一个Web应用程序，可以映射目标的客户端攻击面。
使用`Cobalt Strike`将正常文档转换成恶意文件。 设置恶意`Java Applet`，将攻击性的宏嵌入到Word文档中，或创建删除文档并执行payload的可执行文件。这些用户驱动的攻击可以让我们在目标的网络中获得一个很好的立足点。

使用Cobalt Strike的鱼叉式网络钓鱼工具进行攻击。 此工具将保存的电子邮件重新用于更加完美的网络钓鱼。 使用此工具将恶意文档或者发送一个克隆站点给目标。
使用Cobalt Strike的Beacon控制目标网络。payload使用与高级威胁恶意软件相同的异步"低速和慢速"通信模式。 Beacon通过DNS，HTTP或HTTPS通信。 Beacon遍历常见的代理配置，与多个主机通信，以防止通信阻塞。