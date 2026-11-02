# Social Media Mechanics 2026

![Social Media Mechanics 2026 Banner](assets/banner.png)

> A Hermes skill that teaches the **core mechanics of how social media works in 2026** — platform-agnostic principles for agents to analyze, strategize, and guide users. No personal data, no APIs, pure mechanics.

---

## 🎯 What This Skill Does

This skill encapsulates the **fundamental mechanics** that drive social media success in 2026. It's not a script, not a tool, not an API wrapper — it's a **knowledge skill** that agents load to understand:

- **Why** certain content patterns work (psychological triggers, algorithmic incentives)
- **How** platforms actually distribute content (signals, ranking factors, feedback loops)
- **What** creators/brands should optimize for (attention, retention, conversion)
- **When** to adapt strategy (platform shifts, trend cycles, saturation points)

Agents with this skill can:
1. **Analyze** any social media account/content and identify mechanical strengths/weaknesses
2. **Strategize** platform-agnostic content plans based on 2026 mechanics
3. **Guide** users through decisions with mechanistic reasoning, not guesswork
4. **Predict** which formats/topics will perform before posting

---

## 🧠 Core Mechanics (The "Why It Works")

### 1. Attention Economy → Retention Economy Shift
**2024-2025:** Platforms optimized for *click-through* and *impressions*.
**2026:** Platforms optimize for **session duration** and **return frequency**. The algorithm rewards content that keeps users in-app *and* brings them back.

> **Mechanic:** `Retention > Reach`. A 10k-view video with 80% retention beats 100k views with 10% retention.

### 2. Algorithmic Signals Hierarchy (2026)
```
Tier 1 (Strongest):  Watch time % → Re-watches → Shares (private) → Saves
Tier 2:              Comments (substantive) → Profile visits → Link clicks
Tier 3:              Likes → Public shares → Follows (weak signal alone)
```

**Why:** Platforms learned that passive engagement (likes) is gameable. Active investment (watch time, saves, private shares) correlates with genuine value.

### 3. Format-Mechanics Mapping
| Format | Primary Mechanic | Secondary Mechanic | 2026 Viability |
|--------|------------------|-------------------|----------------|
| Short-form vertical (Reels/TikTok/Shorts) | Swipe retention (0-3s hook) | Loop completion rate | ⭐⭐⭐⭐⭐ |
| Long-form horizontal (YouTube) | Session extension | CTR from browse/suggested | ⭐⭐⭐⭐ |
| Carousel/Thread | Swipe-through rate | Save rate | ⭐⭐⭐⭐ |
| Live/Stream | Concurrent viewers → Duration | Chat velocity | ⭐⭐⭐ |
| Stories/EPHEMERAL | Completion rate | Reply rate | ⭐⭐⭐ |
| Text/Post (X/LinkedIn/Threads) | Dwell time | Reply depth | ⭐⭐⭐ |

### 4. The "Hook → Value → Action" Loop
Every successful 2026 post follows this mechanical sequence:

```
[HOOK] 0-1.5s  →  Stops the scroll (pattern interrupt, curiosity gap, visual anomaly)
[VALUE] 1.5s+  →  Delivers on hook's promise (insight, emotion, utility, narrative)
[ACTION] End   →  Triggers algorithmic signal (save, share, comment, follow, click)
```

**Mechanic:** Missing any link breaks the loop. Hook without value = bait (penalized). Value without hook = unseen. Value without action = dead end.

### 5. Platform-Agnostic Distribution Mechanics
| Mechanism | How It Works | Agent Application |
|-----------|--------------|-------------------|
| **Interest Graph** | Content → user matching via consumption history, not social graph | Optimize for *topic consistency* over follower count |
| **Collaborative Filtering** | "Users like you watched X" | Seed content in proven clusters |
| **Freshness Decay** | Half-life: 2-6h (short), 24-72h (long) | Schedule for audience timezone peaks |
| **Authority Compounding** | Consistent niche → algorithmic trust → wider distribution | Build topical depth before breadth |
| **Cross-Platform Seeding** | Native upload + platform-specific wrapper | Repurpose core asset, adapt wrapper |

### 6. Creator/Brand Mechanical Archetypes (2026)
| Archetype | Core Mechanic | Metric to Maximize |
|-----------|---------------|-------------------|
| **Educator** | Save rate → Reference value | Saves per 1k views |
| **Entertainer** | Re-watch rate → Emotional loop | Completion rate |
| **Community Builder** | Comment depth → Reciprocity | Replies per comment |
| **Curator** | Share rate → Signal filtering | Private shares |
| **Documentarian** | Profile visit → Trust building | Follow conversion |

---

## 🤖 How Agents Use This Skill

### When Loaded, The Agent:
1. **Analyzes** user's current social presence (if provided) against mechanical benchmarks
2. **Asks clarifying questions** to diagnose mechanical gaps:
   - "What's your primary format?" → maps to Format-Mechanics table
   - "What action do you want viewers to take?" → maps to Hook→Value→Action
   - "Which platform(s)?" → maps to Platform-Agnostic Distribution
3. **Generates mechanistic strategy** — not "post more" but "increase save-rate via reference-format carousels"
4. **Predicts performance** using mechanical proxies (hook strength, value density, action clarity)
5. **Iterates** based on signal feedback (retention curves, signal ratios)

### Example Agent Dialogue:
```
User: "My Reels get views but no followers."
Agent: "Views = hook working. No follows = value→action gap. 
       Your Hook→Value→Action loop breaks at Action. 
       Add explicit 'Follow for more [specific niche]' CTA at 80% retention mark. 
       Test: 3 Reels with CTA at 80% vs 3 without. Measure follow-conversion."
```

---

## 📹 Video References (Why It Works)

| Video | Creator | Core Mechanic Demonstrated | Why It Works |
|-------|---------|---------------------------|--------------|
| [The Retention Economy: How TikTok/Reels/Shorts Algorithm Works in 2026](https://www.youtube.com/watch?v=example) | [Channel Name] | Watch-time optimization, loop mechanics | Shows real retention curves & algorithmic tier list |
| [Why Saves Beat Likes: The New Algorithmic Currency](https://www.youtube.com/watch?v=example2) | [Channel Name] | Save-rate as Tier-1 signal | Platform insider explains signal hierarchy shift |
| [Hook-Value-Action: The 3-Step Content Framework](https://www.youtube.com/watch?v=example3) | [Channel Name] | Loop mechanics | Frame-by-frame breakdown of viral posts |

> **Note:** Replace example URLs with actual researched videos. One high-quality mechanistic breakdown > 10 tactical "tips" videos.

---

## 📦 Installation

```bash
# As Hermes global skill
hermes skill install social-media-mechanics-2026

# Or clone for local development
git clone https://github.com/Kowo101/social-media-mechanics-2026.git
```

---

## 📄 License

MIT — see [LICENSE](LICENSE). Free for any use, commercial or personal.

---

## 🤝 Contributing

PRs welcome for:
- New mechanistic insights (with evidence)
- Platform-specific mechanical nuances
- Video reference additions
- Translation of core mechanics

See [CONSTITUTION.md](CONSTITUTION.md) for project governance.

---

## 🏗️ Repository Structure

```
social-media-mechanics-2026/
├── README.md              # This file
├── LICENSE                # MIT License
├── CONSTITUTION.md        # Project governance
├── SKILL.md               # Hermes skill definition
└── references/
    └── video-links.md     # Curated mechanistic video references
```

---

**Built for Hermes agents. No APIs. No personal data. Pure mechanics.**