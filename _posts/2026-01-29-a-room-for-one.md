---
layout: post
title: "Is Anyone Here?"
date: 2026-01-29
---

I wanted to build something calm on the internet. A place where you can be alone with your thoughts. So I made a room. Only one person can be inside at a time. When you leave, everything disappears.

You type something, something acknowledges you, and then it's gone. No logs. No history.

The internet is public. Everyone can see everything, and it keeps everything. Every post, every comment. Most AI tools send your words to a server somewhere, training on what you say. I wanted to make the opposite. A small corner that forgets, where only one person fits.

You can try it at [isanyonehere.xyz](https://isanyonehere.xyz).

## How it works

There's an AI inside the room. It runs in your browser, not on a server. Your words stay on your computer.

When you type something, the AI doesn't reply with text. It replies with a visual pulse. The color and intensity change based on what you wrote.

The model converts your words into numbers, a vector with 384 dimensions. Like a fingerprint of what you said. I split this into three parts, and each controls something different.

**Intensity.** How strong the pulse feels. Longer messages have more weight. If the numbers lean strongly in one direction, the pulse is stronger.

**Hue.** The first part of the numbers decides the color. I mix them in a way that spreads across the color wheel. So "I'm excited" and "I'm worried" end up different colors.

**Saturation and lightness.** The middle part controls how rich the color is. If the numbers vary a lot, the color is more vivid. The last part controls brightness.

The room doesn't answer with words. It just shows you something back.

## Privacy

The AI runs locally using WebGPU, a new technology that lets websites use your graphics card. The model is small. It understands meaning but can't generate text.

Your words go into the model, and then they are gone. When you close the tab, the memory clears. There is no database.

The only thing that goes over the internet is a heartbeat. A small signal that says "I'm still here." This is how the room knows when you leave, so the next person can come in.

---

I keep thinking about this question: when you are alone with an AI, really alone, no logs, no traces, what would you do?

I don't think this is useful. But it is beautiful.
