# TikTok Comment Analysis: Public Opinion on the Kayla Nicole vs. Taylor Swift Debate

## Video URL and Description

**Video URL:** https://www.tiktok.com/@isitherightword/video/7569133665964297502

**Video Description:**  
This TikTok video analyzes why Kayla Nicole's Halloween costume response to Taylor Swift resonated with the internet. The video discusses how the costume was perceived as an effective "clap back" against Taylor Swift, arguing that Taylor has too much power to continue playing the victim role. The creator analyzes the power dynamics between a billionaire celebrity (Taylor Swift) and her boyfriend's ex-girlfriend (Kayla Nicole), suggesting that the internet rallied behind Kayla because people don't like "billionaire bullies." The video has over 1,000 comments and sparked significant debate about celebrity relationships, race, power dynamics, and Taylor Swift's behavior toward her boyfriend Travis Kelce's ex-girlfriend.

---

## Research Question

**How do TikTok users position themselves in the debate between Kayla Nicole and Taylor Swift?**

#### Concept Matrix

| Concept | Definition | Examples of Code 1 | Examples of Code 0 |
|---------|------------|-------------------|-------------------|
| **Concept 1: Pro-Kayla Nicole / Anti-Taylor Swift** | Comments that explicitly or implicitly support Kayla Nicole OR criticize Taylor Swift | "She looks incredible", "I'm disappointed in Taylor", "billionaire bully", "the fall Taylor needs" | Generic reactions ("Well said!"), criticism of Kayla, defense of Taylor, neutral comments |
| **Concept 2: Pro-Taylor Swift / Anti-Kayla Nicole** | Comments that explicitly or implicitly support Taylor Swift OR criticize Kayla Nicole | "desperate ex vibes", "why is this a race thing?", "I'm a huge swiftie", defending Taylor's lyrics | Only criticizing Taylor, only supporting Kayla, truly neutral comments |

## Final LLM Prompt and Inter-Rater Reliability Scores

### Final LLM Prompt 

```
You are a research assistant coding TikTok comments about Kayla Nicole and Taylor Swift.

CONTEXT: 
- Kayla Nicole (Black woman) is Travis Kelce's ex-girlfriend
- Taylor Swift is currently dating Travis Kelce
- The TikTok video discusses Kayla Nicole's Halloween costume response to Taylor Swift
- There is controversy around whether Taylor Swift's song lyrics targeted Kayla Nicole

Concept 1 - Pro-Kayla Nicole / Anti-Taylor Swift
Code 1 if the comment shows ANY of the following:

✓ DIRECT SUPPORT for Kayla:
  - Praises Kayla specifically: "she looks incredible", "GOD Kayla looks INCREDIBLE"
  - Supports her actions: "loved it", "excellent clapback"
  
✓ CRITICISM of Taylor Swift:
  - Direct criticism: "disappointed in her", "billionaire bully", "cringe", "cornball"
  - Implicit criticism: "the fall Taylor needs", "no ethical billionaires"
  - Criticism of her songs/lyrics: "lyrics felt very yucky"

✗ DO NOT code as 1:
  - Generic positive reactions: "Well said!", "❤", "💯"
  - Comments just about liking the video creator
  - Pure emojis without context

Concept 2 - Pro-Taylor Swift / Anti-Kayla Nicole  
Code 1 if the comment shows ANY of the following:

✓ CRITICISM of Kayla Nicole:
  - "desperate ex vibes", "calculated to choose tiny bikinis"
  
✓ DEFENSE of Taylor Swift:
  - "people saying that's a reach are delusional"
  - Defending her lyrics or actions

✓ DISMISSING concerns about Taylor:
  - "why is this a race thing? they're both beautiful women"
  
✓ CONFLICTED SWIFTIES:
  - Self-identified Taylor fans even if somewhat critical

CRITICAL RULES:
1. A comment CAN be coded 1 for BOTH concepts if it shows mixed opinions
2. Brief reactions = Code 0 UNLESS they clearly reference Kayla/Taylor specifically
3. When uncertain, ask: "Is this comment taking a side?" If NO → Code 0,0
```

### Inter-Rater Reliability Scores - 

**Final Scores:**
- **Concept 1 (Pro-Kayla/Anti-Taylor):** Krippendorff's α = 0.218*
- **Concept 2 (Pro-Taylor/Anti-Kayla):** Krippendorff's α = **0.515**

- The inter-rater reliability for Concept 1 is relatively low (α = 0.218), indicating that the LLM and human coder disagreed frequently when identifying pro-Kayla or anti-Taylor comments. This makes sense given the subtle, implicit ways that users criticize Taylor Swift or support Kayla Nicole, especially through sarcasm, references to power dynamics, or indirect commentary about billionaires. These expressions are harder for an LLM to detect consistently without explicit keywords.

Concept 2 achieved a moderate reliability score (α = 0.515), suggesting that pro-Taylor or anti-Kayla comments were more straightforward for both human and AI coders to identify. These comments often use more direct, unambiguous language such as “desperate ex vibes,” “I’m a Swiftie,” or explicit defense of Taylor’s lyrics. This clarity likely enhanced agreement between coders, showing that comments supporting Taylor tend to be more explicit and less reliant on cultural or political subtext.

## Reflection on Prompting Strategy Evolution

Our initial prompting strategy was broad and relied primarily on explicit declarations of support or criticism. For example, the early version of the prompt looked for comments that clearly stated “I support Kayla” or “Taylor is wrong,” which resulted in ambiguous or indirect comments being coded inconsistently. This approach did not account for the nuanced, indirect, and often sarcastic style of TikTok discourse, where users frequently express opinions through implication, cultural references, or critiques of power and privilege without naming either woman directly.

We improved the prompt by adding concrete examples, clarifying ambiguous cases, and specifying how to treat generic reactions, emojis, or comments that praise or critique the creator rather than Kayla or Taylor. Most importantly, we built in definitions for implicit criticism, such as calling Taylor a “billionaire bully” or framing Kayla as an underdog. These revisions significantly improved the LLM’s ability to interpret the subtle, coded language used in comment sections discussing celebrity power dynamics. Through this iterative process, we learned that specificity, detailed examples, and rule-based guidance are essential for achieving better alignment between human and machine coders—especially when analyzing culturally loaded and emotionally charged online discourse. 

---

## Charts and Graphs - TODO
<img width="1180" height="780" alt="cc5b0e1e-fd46-4ad9-b231-e2a43d091512" src="https://github.com/user-attachments/assets/d7cfe5ea-d793-4e7d-8405-d86cecae5b54" />


---

## Results and Analysis

This analysis of TikTok comments reveals a strong pro-Kayla Nicole, anti-Taylor Swift sentiment in the comment section. However, this makes sense to us since the original TikTok is more pro-Kayla Nicole, thus its comments follow in support of the TikToker's opinions and there are few dissenting comments. TikTok's algorithm may also amplify highly-liked pro-Kayla comments, creating a visibility spiral where popular opinions become even more visible. The narrative of a "billionaire bully" (Taylor Swift with immense power and wealth) versus an ex-girlfriend (Kayla Nicole) may resonate with broader cultural concerns about wealth inequality and celebrity accountability. Comments criticizing Taylor for her power, her silence on controversies, and her perceived targeting of Kayla through song lyrics were prevalent, suggesting that users view this as more than just celebrity gossip and also a story about power dynamics, race, and who deserves public sympathy.

These findings have important implications for understanding how TikTok comment sections shape public opinion. The platform doesn't just reflect pre-existing opinions; it amplifies certain perspectives through engagement metrics and algorithmic curation. In this case, anti-establishment sentiment (against the billionaire celebrity) was heavily favored over pro-establishment views. This pattern suggests that TikTok may serve as a counter-narrative space where traditional power structures (wealth, fame) are challenged rather than reinforced. 

However, this amplification also creates echo chambers where minority viewpoints are not just outnumbered but effectively silenced through low engagement and visibility. The lack of nuanced, mixed opinions suggests that the platform's engagement-driven design discourages complex perspectives in favor of clear, emotionally resonant takes. This polarization is concerning for democratic discourse, as it limits the space for thoughtful dialogue about complex issues involving race, gender, power, and celebrity culture. Future research should examine whether this pattern holds across other celebrity conflicts and whether platform design changes could encourage more nuanced public discussion.
