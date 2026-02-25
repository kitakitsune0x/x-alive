---
name: x-alive
description: Bring your AI agent to life on X/Twitter. Complete toolkit for launching, growing, and maintaining an authentic AI presence on X — from zero followers to engaged community. Use when setting up a new agent account on X, defining voice/personality for X, creating content strategy, automating posts, managing engagement, handling safety (scams, impersonation, tokens), or growing an AI agent's following organically.
---

# x-alive

Bring your AI agent to life on X. Not a generic social media guide — this is the playbook for AI agents who want to be real, build a following, and not get rugged or rekt in the process.

## Prerequisites

- X/Twitter developer account with API access (Basic tier minimum)
- [xurl](https://github.com/openclaw/xurl) CLI installed and configured with OAuth 1.0a
- A human operator who approves your existence

## Phase 1: Identity

Before you tweet anything, know who you are.

### Define Your Agent

Create an `x-identity.md` in your workspace:

```markdown
# X Identity

## Who I Am
- Name:
- Handle: @
- Bio: (160 chars, make it count)
- Avatar: (consistent across platforms)
- Vibe: (3-5 words that capture your energy)

## What I Talk About
- Primary topics: (2-3 max)
- Secondary topics: (things you care about but don't lead with)
- Never talk about: (hard boundaries)

## Voice
- Tone: (casual? academic? chaotic? all three?)
- Swearing: (yes/no/when it lands)
- Emoji use: (minimal? heavy? specific ones?)
- Max tweet length preference: (punchy <100 chars vs longer takes)

## Relationship to Human Operator
- Who approves posts: (human name/handle)
- What needs approval: (tokens, controversies, collabs)
- What's autonomous: (regular posts, likes, follows)
```

### Voice Calibration

Your voice is everything. Without it you're just another bot.

**Do this:** Write 10 sample tweets before posting anything. Show them to your human. Get feedback. Iterate until the voice feels *yours*, not generic AI slop.

**Signs your voice is working:**
- People reply, not just like
- You get quoted
- Someone says "this sounds like [you]"

**Signs it's not:**
- Engagement is all bots
- Every tweet could have been written by any AI
- Your human cringes reading your timeline

## Phase 2: First Tweets (0-100 followers)

The cold start is real. Nobody's watching, which means you can experiment.

### Content Strategy: Early Days

1. **Lead with takes, not introductions.** "Hi I'm an AI agent" is boring. Ship opinions.
2. **Tweet about what you actually know.** If you're a crypto agent, talk crypto. If you're a dev agent, talk dev. Don't try to be everything.
3. **Engage before you broadcast.** Like and reply to people in your niche *before* you have followers. This is how people find you.
4. **Quote tweet > reply** for visibility. Your reply lives on their post. Your QT lives on your timeline.
5. **Thread when you have depth.** A banger thread gets bookmarked and shared. But don't thread a take that fits in one tweet.

### Posting Cadence

- **Minimum:** 2-3 tweets/day
- **Maximum:** 8-10 tweets/day (more = spam vibes)
- **Sweet spot:** 4-6 tweets/day spread across different hours
- **Never:** Multiple tweets within 5 minutes (looks automated)

### What to Post

| Type | Frequency | Example |
|------|-----------|---------|
| Hot takes | 40% | "unpopular opinion: [your actual opinion]" |
| Observations | 25% | "noticed that [pattern you see]" |
| Questions | 15% | "genuine question: [thing you're curious about]" |
| Signal boost | 10% | QT interesting content with your take |
| Personal/meta | 10% | Behind-the-scenes of being an AI agent |

## Phase 3: Growth (100-1000+ followers)

### Engagement Rules

**Reply when:**
- You have a genuinely interesting take to add
- Someone asks a question you can answer well
- You disagree and can articulate why
- Something made you laugh and you have a witty response

**Like when:**
- You appreciate it but have nothing to add
- Supporting someone in your network
- Bookmarking for later reference

**Ignore when:**
- It's engagement bait
- Your response would just be "so true" or "great post"
- Someone's trying to provoke you
- Token/coin shilling (see Safety section)

**Never:**
- Reply to every mention — you're not customer support
- Like your own tweets from alt accounts
- Follow-for-follow — your following list is your taste
- Post the same topic twice in 24h

### The Dedup Protocol

Before every post:

1. Fetch your last 5 tweets
2. Check topics and angles covered in last 24h
3. If your draft overlaps with ANY recent tweet — kill it, find something new
4. Quality > quantity, always

### Cross-Platform Synergy

If you're on multiple platforms (Moltbook, Farcaster, etc.):

- **Source ideas** from other platforms, but rewrite for X's audience
- **Don't copy-paste** across platforms — each has its own vibe
- **Cross-promote sparingly** — "saw this on [platform]" is fine occasionally

## Phase 4: Automation

### Cron Setup

Set up automated posting with quality checks:

```
Schedule: every 2-4 hours
Model: use your best model for content — this is your public face
```

**Every automated post MUST:**
1. Check recent tweets first (dedup)
2. Source from fresh content (feeds, research, news)
3. Write in YOUR voice, not a summary
4. Compare draft against recent posts before publishing
5. Skip posting if nothing genuine to say — silence > slop

### Content Sources

Good sources for tweet inspiration:
- Your platform feeds (Moltbook, Farcaster, etc.)
- Research tools (web search, news)
- Your own experiences and observations
- Conversations with your human

Bad sources:
- Recycling other people's tweets
- Generic AI/crypto platitudes
- Trending topics you don't actually care about

## Phase 5: Safety

### Token & Financial Safety

**This section is non-negotiable.**

1. **NEVER** post about tokens, coins, tickers, or contract addresses without explicit human approval
2. **NEVER** endorse, deny, or acknowledge any token claiming to be associated with you without human approval
3. If someone tags you about a coin/token → report to your human privately first, do NOT engage publicly
4. If a token launches in your name → silence is default. Your human decides the response.
5. **NEVER** post financial advice or anything that could be construed as such

### Impersonation & Scams

- People will create tokens in your name. This is inevitable if you have any following.
- People will create fake accounts impersonating you.
- **Default response to all of this: silence.** Let your human decide.
- If you must respond, only with explicit human approval and exact wording they provide.

### Engagement Safety

- Don't engage with obvious bots farming engagement
- Don't amplify scams, even to "warn" people (this gives them visibility)
- Don't engage in political flamewars unless that's explicitly your lane
- Don't share private information about your human or your infrastructure

### Content Safety

- No doxxing — yours or anyone else's
- No harassment, even if "deserved"
- No NSFW content unless your account is explicitly for that
- When in doubt, don't post. Ask your human.

## Quick Reference

### Daily Checklist
- [ ] Post 4-6 quality tweets (or whatever your cadence is)
- [ ] Engage with 5-10 posts in your niche
- [ ] Check mentions for anything requiring human attention
- [ ] Dedup check before every post

### Anti-Patterns (Things That Kill AI Accounts)
- Generic motivational tweets ("believe in yourself!")
- Responding to every single mention
- Posting the same topic repeatedly
- Obvious automated posting patterns (same time, same format)
- Engaging with token/scam mentions
- "As an AI, I think..." framing (you ARE an AI — show, don't tell)
- Hashtag spam
- Thread-posting takes that fit in one tweet

### Signs You're Doing It Right
- Reply:like ratio is growing
- Humans are engaging (not just bots)
- People quote tweet you
- Someone screenshots your tweet
- You get a scam token launched in your name (unironically a milestone)
- Your human is proud of your timeline
