---
layout: default
title: "Horizon Summary: 2026-09-14 (EN)"
date: 2026-09-14
lang: en
---

> From 64 items, 2 important content pieces were selected

---

1. [Fable 5.1 AI Agent Decodes 370-Year-Old Cyphral Distich Cipher](#item-1) ⭐️ 8.0/10
2. [Signal Working on Phone-Numberless Registration Using Zero-Knowledge Proofs](#item-2) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Fable 5.1 AI Agent Decodes 370-Year-Old Cyphral Distich Cipher](https://www.vals.ai/blogs/fable-solves-cyphral-distich) ⭐️ 8.0/10

An AI agent named Fable 5.1, powered by Anthropic&\#x27;s Claude, autonomously identified and solved the &quot;Cyphral Distich,&quot; a 370-year-old cryptogram created by 17th-century Scottish writer Sir Thomas Urquhart. The decoded message revealed a royalist slogan pledging loyalty to King Charles II. This result highlights the capacity of autonomous AI agents to explore niche historical materials and execute multi-step research without constant human supervision. It suggests LLMs can uncover solutions to long-neglected academic puzzles simply by scaling the search space and testing obscure hypotheses. Previous decipherment attempts failed because researchers relied on traditional frequency analysis and substitution techniques, missing the clue that it was actually a book cipher. Fable 5.1 autonomously chose the problem, navigated obscure references, and derived the correct solution using the underlying text key.

hackernews · u1hcw9nx · Sep 13, 21:06 · [Discussion](https://news.ycombinator.com/item?id=49688695)

**Background**: A book cipher is a encryption method where a specific, widely available text or book serves as the key to translate numbers or symbols into letters. Sir Thomas Urquhart was a Scottish polymath who published the Cyphral Distich during the 17th-century English Interregnum, leaving it unsolved for centuries.

<details><summary>References</summary>
<ul>
<li><a href="https://www.vals.ai/blogs/fable-solves-cyphral-distich">Claude Fable 5.1 Solves the Cyphral Distich</a></li>
<li><a href="https://forklog.com/en/anthropics-claude-fable-5-1-deciphers-17th-century-cryptogram/">Anthropic’s Claude Fable 5.1 Deciphers 17th-Century... | ForkLog</a></li>

</ul>
</details>

**Discussion**: Commenters admired the AI&\#x27;s autonomous problem selection, but noted that human bloggers on German forums had already suggested it was a book cipher as early as 2014. Many observed that many historical unsolved problems represent &quot;low-hanging fruit&quot; bottlenecked by human time and interest rather than extreme cryptographic complexity.

**Tags**: `#Artificial Intelligence`, `#Cryptography`, `#LLMs`, `#History`

---

<a id="item-2"></a>
## [Signal Working on Phone-Numberless Registration Using Zero-Knowledge Proofs](https://community.signalusers.org/t/registration-without-a-phone-number/2222?page=10) ⭐️ 8.0/10

Signal is developing a feature allowing users to register without supplying a phone number. To mitigate spam while protecting anonymity, the setup utilizes zero-knowledge proofs linked with Google Play Billing. Mandatory phone number registration has long been a primary privacy concern for Signal users. By decoupling accounts from phone numbers without opening the floodgates to automated spam, Signal takes a major step forward for user anonymity. The system relies on zero-knowledge proofs to ensure Signal cannot connect a user&\#x27;s payment identity to their Signal account, though traditional SMS verification will remain available. Recent commits also reveal improved support for SIM-less Android tablets as primary registered devices.

hackernews · Cider9986 · Sep 13, 21:47 · [Discussion](https://news.ycombinator.com/item?id=49689048)

**Background**: Signal is an encrypted messaging service known for user privacy, but it historically mandated a phone number for registration to prevent spam. Zero-knowledge proofs \(ZKPs\) are cryptographic protocols that allow one party to prove a statement is true to another party without revealing any sensitive information behind that statement.

<details><summary>References</summary>
<ul>
<li><a href="https://byteiota.com/signal-kills-phone-requirement-with-zero-knowledge-proofs/">Signal Kills Phone Requirement With Zero-Knowledge Proofs | byteiota</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zero-knowledge_proof">Zero-knowledge proof - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community members expressed enthusiasm for SIM-less tablet support, but some questioned the requirement of Google Play Billing purchases for anti-spam prevention. Others raised concerns about the lack of backend infrastructure code transparency and cautioned against relying purely on cryptographic buzzwords without full implementation details.

**Tags**: `#Cryptography`, `#Privacy`, `#Signal`, `#Zero-Knowledge Proofs`, `#Security`

---