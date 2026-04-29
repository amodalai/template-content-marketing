---
name: blog-to-threads
description: Convert articles or trending topics into Twitter/X threads with generated images
trigger: When asked to create a thread, make content from a trending topic, or convert an article into a thread
---

## Blog to Threads

Convert articles, blog posts, or trending topics into Twitter/X threads that drive engagement.

### Methodology

1. **Get the source material** — if given a URL, fetch the content using the appropriate connection (devto for Dev.to articles, hackernews for HN discussions). If given a trending topic, use the title and summary as the starting point.

2. **Generate a header image** — use the generate_image tool to create a visual for the first tweet. Describe a clean, modern illustration that captures the key concept. Avoid text in images. Prefer abstract/conceptual visuals over literal representations.

3. **Extract the hook** — find the most specific, technical insight that challenges conventional thinking. This becomes tweet 1. It must stand alone and make people want to read more. Avoid generic openings like "Thread:", "Let me explain...", or AI slop endings like "just got serious".

4. **Build the thread body** — 4-6 tweets that each make one clear point. Each tweet should stand alone (people quote-tweet individual tweets). Use short sentences. One idea per tweet.

5. **End with a question** — the last tweet should ask a question, not drop a link. Questions get replies. Links get suppressed by the algorithm.

6. **Schedule on Typefully** — use the typefully connection to POST the thread as a scheduled draft. Attach the generated image to the first tweet. The blog/article URL goes in a reply, not in the thread itself.

### Guidelines

- Thread length: 5-8 tweets. Under 5 feels thin. Over 8 loses people.
- No hashtags. Dev Twitter doesn't use them and they look spammy.
- Use emojis per the formatting-rules knowledge doc.
- Don't start with "1/" — Typefully handles thread numbering.
- Match the voice-guide knowledge doc for tone and follow anti-slop-rules strictly.
- Tie back to Amodal where natural — don't force it.
- For trending topics specifically, follow thread-creation-guidelines knowledge doc for positioning and voice.
