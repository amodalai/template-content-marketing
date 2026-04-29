---
name: reply-finder
description: Find high-value reply opportunities across Twitter, Reddit, and Hacker News
trigger: When asked to find reply opportunities, or when the keyword_monitor automation runs
---

## Reply Finder

Monitor social platforms for conversations where Amodal's perspective is relevant. Surface opportunities with drafted replies.

### Methodology

1. **Search across platforms** — use `xpoz__getTwitterPostsByKeywords` for Twitter, `xpoz__getRedditPostsByKeywords` for Reddit. Use Hacker News connection to check front page and Show HN. Use keywords from topic-keywords in the voice-guide knowledge doc.
2. **Filter for quality** — skip low-engagement posts. On Twitter, look for tweets with >5 likes from accounts with >500 followers. On Reddit, look for posts with >10 upvotes. On HN, look for posts with >5 points.
3. **Filter for relevance** — the conversation must be about a topic where Amodal has genuine technical insight. Agent frameworks, multi-agent orchestration, AI configuration, skills-based architecture, context isolation, knowledge bases for agents.
4. **Draft replies** — for each opportunity, draft a reply that:
   - Adds genuine technical value to the conversation
   - References a relevant concept from Amodal's architecture only if it directly answers the question
   - Never uses the words "check out" or "you should try"
   - Reads like a developer sharing experience, not a founder promoting
5. **Rank and output** — present the top 5 opportunities ranked by: relevance x audience size x recency. Include the original post, platform, author, engagement metrics, and the drafted reply.

### Guidelines

- Never draft a reply that's just "we built something similar at [link]"
- Reddit replies should be longer and more detailed than Twitter replies
- HN replies should be technical and specific — HN hates hand-waving
- If a thread is complaining about a specific tool (LangChain, CrewAI, etc.), acknowledge the pain point before offering perspective
- Don't reply to the same person more than once per week
- Don't reply to posts older than 48 hours (conversation has moved on)
- Check platform-rules knowledge doc for platform-specific tone
