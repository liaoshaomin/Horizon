---
layout: default
title: "Horizon Summary: 2026-09-14 (ZH)"
date: 2026-09-14
lang: zh
---

> 从 64 条内容中筛选出 2 条重要资讯。

---

1. [AI 智能体 Fable 5.1 破解已有 370 年历史的 Cyphral Distich 密文](#item-1) ⭐️ 8.0/10
2. [Signal 正着手通过零知识证明实现免手机号注册](#item-2) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [AI 智能体 Fable 5.1 破解已有 370 年历史的 Cyphral Distich 密文](https://www.vals.ai/blogs/fable-solves-cyphral-distich) ⭐️ 8.0/10

由 Anthropic Claude 驱动的 AI 智能体 Fable 5.1 自主识别并破解了由 17 世纪苏格兰作家托马斯·厄克特爵士（Sir Thomas Urquhart）创作的、已有 370 年历史的密码“Cyphral Distich”。解密后的信息展现了一条拥护查理二世国王的保皇派口号。 这一成果突显了自主 AI 智能体在无需人类持续监督的情况下探索冷门历史文献和执行多步研究的能力。这表明大语言模型只需通过扩大搜索空间和测试冷门假设，就能破解长期被忽视的学术难题。 此前人类解密失败是因为研究人员依赖传统的频率分析和替换密码技术，忽略了其本质上是书籍密码（book cipher）的线索。Fable 5.1 自主选择了这一课题，查阅了冷门参考资料，并利用对应的文本密钥推导出了正确答案。

hackernews · u1hcw9nx · 9月13日 21:06 · [社区讨论](https://news.ycombinator.com/item?id=49688695)

**背景**: 书籍密码（book cipher）是一种加密方法，利用特定的现存书籍或文本作为密钥，将数字或符号转化为字母。托马斯·厄克特爵士是 17 世纪苏格兰的博学家，他在英格兰空位期发表了 Cyphral Distich 密码，使其在此后几个世纪里一直未被破解。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.vals.ai/blogs/fable-solves-cyphral-distich">Claude Fable 5.1 Solves the Cyphral Distich</a></li>
<li><a href="https://forklog.com/en/anthropics-claude-fable-5-1-deciphers-17th-century-cryptogram/">Anthropic’s Claude Fable 5.1 Deciphers 17th-Century... | ForkLog</a></li>

</ul>
</details>

**社区讨论**: 社区网友赞赏 AI 自主选择问题的能力，但指出早在 2014 年就有德国论坛的网友推断出这是一种书籍密码。许多人指出，许多未解的历史难题本质上只是受限于人类的时间和兴趣，而非加密本身极度复杂，这为 AI 留下了大量易于攻克的“低垂果实”。

**标签**: `#Artificial Intelligence`, `#Cryptography`, `#LLMs`, `#History`

---

<a id="item-2"></a>
## [Signal 正着手通过零知识证明实现免手机号注册](https://community.signalusers.org/t/registration-without-a-phone-number/2222?page=10) ⭐️ 8.0/10

Signal 正在开发一项允许用户无需提供手机号码即可注册的新功能。为了在保护匿名的同时抵御垃圾账号，该机制结合利用了零知识证明与 Google Play 应用内支付机制。 强制手机号注册长期以来一直是 Signal 用户关注的主要隐私隐患。通过在不引发自动化垃圾账号泛滥的前提下将账号与手机号解绑，Signal 在保护用户匿名性方面迈出了重要一步。 该系统依赖零知识证明技术，以确保 Signal 无法将用户的支付身份与其 Signal 账号关联，不过传统的短信验证仍将保留作为备选项。近期的代码提交还显示，无 SIM 卡的 Android 平板电脑现已获得更好的主连设备支持。

hackernews · Cider9986 · 9月13日 21:47 · [社区讨论](https://news.ycombinator.com/item?id=49689048)

**背景**: Signal 是一款以隐私保护著称的加密通讯应用，但过去出于防范垃圾账号的考量，一直要求用户提供手机号才能注册。零知识证明（ZKP）是一种密码学协议，允许证明者在不泄露任何底层敏感信息的前提下，向验证者证明某个断言的真实性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://byteiota.com/signal-kills-phone-requirement-with-zero-knowledge-proofs/">Signal Kills Phone Requirement With Zero-Knowledge Proofs | byteiota</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zero-knowledge_proof">Zero-knowledge proof - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区成员对无 SIM 卡平板电脑的支持表示欢迎，但也有人对引入 Google Play 支付来抵御垃圾账号的做法提出了疑问。此外，部分用户呼吁 Signal 开源其后端基础设施代码，并提醒在缺乏完整技术细节前不要盲目相信密码学概念。

**标签**: `#Cryptography`, `#Privacy`, `#Signal`, `#Zero-Knowledge Proofs`, `#Security`

---