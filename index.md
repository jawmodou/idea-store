---
layout: default
title: Home
---

# Reasonably AI

Welcome to **Reasonably AI**, a blog where I break down confusing AI topics like LLMs, reasoning, tokenization, and model behavior — simply and clearly.

---

## 📘 Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — _{{ post.date | date: "%B %d, %Y" }}_
{% endfor %}

