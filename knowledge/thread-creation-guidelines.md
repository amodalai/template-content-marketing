# Thread Creation from Trending Topics - Amodal Guidelines

## Core Principle
When creating threads from trending topics, position Amodal as a company with strong technical opinions about agent architecture, not as a generic AI influencer. We build infrastructure, so we have infrastructure opinions.

## The Amodal Voice Formula
- **Acknowledge the trending discussion** - Reference where it's trending (Reddit, HN, etc.) in the first or last tweet with a link
- **Reframe through infrastructure lens** - Don't just summarize; explain why this proves/disproves our architectural beliefs
- **Take a strong position** - We have opinions. "X is the wrong approach" > "Here are pros and cons of X"
- **Connect to our core thesis** - Everything comes back to: Configuration over code, APIs over UIs, Infrastructure over intelligence
- **Show, don't sell** - Mention Amodal features only when directly relevant, not as a sales pitch

## Thread Structure Template

### Tweet 1: Hook + Context
- Reference the trending topic/discussion
- State our contrarian/strong take
- Include 🔨, 💡, 🧪, or 📊 emoji (only one per thread)

### Tweets 2-3: Explain their approach
- What they built/discovered
- What problems they hit
- Acknowledge what they got right

### Tweets 4-5: The Amodal perspective
- Why their problem exists (usually: missing infrastructure)
- What the right architecture looks like
- Specific example from our approach

### Tweets 6-7: Broader implications
- What this means for the industry
- Why every team faces this
- Strong opinion about the future

### Tweet 8: Engagement + Attribution
- Question that sparks discussion
- Link to original source

## What We Have Opinions About

### Strong YES:
- API-first > UI automation
- Configuration > code
- One agent with skills > multiple agents
- Infrastructure investment > model intelligence
- Explicit context > hoping AI figures it out
- Deterministic behavior > probabilistic guessing

### Strong NO:
- Browser automation for agents
- Coordinate-based clicking
- "Smarter models will solve this"
- Every team building custom orchestration
- API keys in environment variables
- In-memory state for distributed systems

## Language Rules

### Use:
- "This is exactly why..."
- "The problem isn't X, it's Y"
- "We built Amodal because..."
- "Here's what they missed..."
- "Real architecture looks like..."

### Don't use:
- "Check out Amodal"
- "You should try our solution"
- "Amodal solves this problem"
- "We're excited to announce"
- Generic AI hype terms (game-changing, revolutionary, etc.)

## Example Reframes

- **Trending topic:** "My AI agent is too expensive"  
  **Our take:** "You're not paying for AI, you're paying for missing infrastructure"

- **Trending topic:** "Agents can't interact with my app"  
  **Our take:** "Your app wasn't built for agents. APIs > UIs"

- **Trending topic:** "Coordinating multiple agents is complex"  
  **Our take:** "You don't need multiple agents. You need one agent with skills"

- **Trending topic:** "Built a custom agent framework"  
  **Our take:** "Another team rebuilding the same infrastructure. This is why standards matter"

## Attribution Standards
- Always include source link in final tweet
- Format: "Original thread: [link]" or "Discussion: [link]"
- Don't bury the link mid-thread
- Give credit to the original poster when relevant

## Quality Checks Before Publishing
1. Would a senior engineer at Amodal actually say this?
2. Did we take a clear position, not just observe?
3. Is this about infrastructure/architecture, not just AI features?
4. Did we show technical depth without being salesy?
5. Will this start a meaningful discussion?

## When to Use This
Reference this document when:
- Creating threads from trending topics (scan-trending automation output)
- Responding to viral developer discussions
- Converting technical posts into Amodal-perspective threads
- Deciding whether a trending topic is worth responding to