---
type: lenny-podcast
guest: "Lenny Rachitsky"
companies: ""
topic: "What is the lethal trifecta?"
date: 2026-04-08
duration: "1m"
views: 2217
likes: 19
youtube: "https://www.youtube.com/watch?v=rVBq12AgAJU"
tags:
  - lenny-podcast
---

# Lenny Rachitsky — What is the lethal trifecta

> Lenny's Podcast | 2026-04-08 | 1m | 2,217 views

## Links
- [Watch on YouTube](https://www.youtube.com/watch?v=rVBq12AgAJU)

---

## Full Transcript

Kind: captions Language: en So, prompt injection is the class of vulnerabilities in applications we build on top of LLMs. I didn't discover this problem, but I was the first to stamp a name on it. The problem is the name itself is misleading. You hear prompt injection and think, "Oh, I can solve SQL injection. I'll use the same thing." That doesn't work. The lethal trifecta was my second attempt at this, and you'll notice that the lethal trifecta, you cannot guess what it is. It's three things, but what are those things? And that means I get to control what it means, because you have to go look it up when you hear what it is. You have a lethal trifecta anytime your agent has three things. It's got access to private information, it's exposed to malicious instructions, so there's a way somebody attacking you can get their text into your system, and the third leg is exfiltration, or some mechanism the agent can send data back to that attacker. So, if you've got a system where you've got private emails, anyone can email you instructions, and it can email them back, that's the classic lethal trifecta. That's

a huge security problem. The only way to fix it is to cut off one of those three legs.
