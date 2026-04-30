# 🔎 Competitive Analysis Prompt

> **Use this prompt to:** Analyze competitor implementations and identify market gaps + differentiation opportunities.

## When to Use

- Before starting ideation
- To validate market patterns
- To identify differentiation opportunities
- When establishing feature requirements

## What You'll Need

- ✅ Screenshots of 3-5 competitor implementations
- ✅ Competitor names and context
- ✅ Your project context
- ✅ ~10-15 minutes for AI processing

## Expected Output

- Common patterns (table stakes)
- Unique approaches (differentiation opportunities)
- Inferred UX gaps
- Visual/interaction patterns
- Comparison matrix
- Strategic recommendations

---

## 📋 The Prompt

```
I'm a Senior Product Designer conducting competitive research. I've uploaded [NUMBER] screenshots showing how competitors handle [FEATURE/PROBLEM AREA].

PROJECT CONTEXT:
- Product: [YOUR PRODUCT TYPE]
- Feature being analyzed: [SPECIFIC FEATURE]
- Target users: [YOUR USER BASE]
- Goal: Identify market patterns, gaps, and differentiation opportunities

COMPETITORS UPLOADED:
1. [COMPETITOR 1 NAME]
2. [COMPETITOR 2 NAME]
3. [COMPETITOR 3 NAME]
4. [COMPETITOR 4 NAME]
5. [COMPETITOR 5 NAME]

YOUR TASK:
Analyze each competitor's implementation with the rigor of a UX researcher and competitive strategist. Extract patterns that inform our design decisions and identify market gaps we can exploit.

---

ANALYSIS FRAMEWORK:

## 1. COMMON PATTERNS (Table Stakes)

For each pattern present in 3+ competitors, document:

**A. PATTERN NAME & DESCRIPTION:**
- What is this pattern called?
- How does it work? (interaction sequence)
- Where is it positioned in the UI?

**B. IMPLEMENTATION VARIATIONS:**
- How does each competitor implement it differently?
- What's the most common approach?

**C. EVIDENCE:**
- Reference specific screenshots
- Note visual/interaction details

**D. WHY IT'S TABLE STAKES:**
- What user need does this address?
- Why have most converged on this approach?
- What would users expect if missing?

FORMAT EXAMPLE:
```
PATTERN: [Pattern Name]

IMPLEMENTATION:
- [Competitor A]: [How they implement it]
- [Competitor B]: [How they implement it]
- [Competitor C]: [How they implement it]
[Continue for all]

COMMON ELEMENTS ([X/Total]):
- [Universal element 1]
- [Universal element 2]

DIVERGENT ELEMENTS:
- [Where they differ]

WHY TABLE STAKES:
[User need this addresses]

OUR IMPLEMENTATION RECOMMENDATION:
[Match or differentiate]
```

---

## 2. UNIQUE APPROACHES (Differentiation Opportunities)

Identify approaches used by only 1-2 competitors:

**A. INNOVATIVE PATTERNS:**
- What is unique to this competitor?
- Why might they have chosen this?
- Does it solve a real problem?

**B. RISKY PATTERNS:**
- What approaches seem confusing or limiting?
- What might fail at scale?

**C. OPPORTUNITY ASSESSMENT:**
- Could we adopt this as differentiation?
- Could we improve on it?
- Should we avoid it?

FORMAT EXAMPLE:
```
UNIQUE APPROACH: [Approach Name]

DESCRIPTION:
- [Detailed description of approach]

WHY THEY MIGHT HAVE CHOSEN THIS:
- [Strategic reasoning]

POTENTIAL ISSUES:
- [Problems with this approach]

OPPORTUNITY ASSESSMENT:
- [Should we adopt/improve/avoid]
- [V1, V2, or never]
```

---

## 3. UX GAPS & FRUSTRATIONS (Inferred)

Identify problems competitors haven't solved well.

**A. MISSING FUNCTIONALITY:**
- What's absent across all competitors?
- What user needs aren't addressed?

**B. POOR EXECUTION:**
- Where do competitors fall short?
- What looks confusing or cluttered?

**C. INFERRED PAIN POINTS:**
- Based on UI quirks, what user complaints might exist?
- What workarounds would users need?

**D. ACCESSIBILITY GAPS:**
- Are competitors handling screen readers, keyboard nav?
- Color contrast issues?
- Mobile/touch optimization?

FORMAT EXAMPLE:
```
UX GAP: [Gap Title]

OBSERVATION:
- [What's missing or poorly done]

INFERRED USER FRUSTRATION:
- [Likely user complaints]

EVIDENCE:
- [Specific competitor examples]

DIFFERENTIATION OPPORTUNITY:
- [How we could solve this better]

PRIORITY: [HIGH/MEDIUM/LOW]
```

---

## 4. VISUAL & INTERACTION PATTERNS

**A. SELECTION/INPUT STATES:**
- How are different states indicated?
- Color choices and contrast
- Animation/transition styles

**B. ACTION TRIGGERS:**
- Button styles
- Icon usage
- Placement strategies

**C. FEEDBACK PATTERNS:**
- Progress indicators
- Success states
- Error displays

**D. CONFIRMATION PATTERNS:**
- When is confirmation required?
- What information is shown?
- Cancel vs. confirm hierarchy

**E. RESPONSIVE BEHAVIOR:**
- Mobile/tablet adaptations
- Touch target sizes
- Information prioritization

---

## 5. COMPARISON MATRIX

| Feature/Capability | [Comp 1] | [Comp 2] | [Comp 3] | [Comp 4] | [Comp 5] | Our Plan |
|-------------------|----------|----------|----------|----------|----------|----------|
| [Feature 1] | | | | | | |
| [Feature 2] | | | | | | |
| [Feature 3] | | | | | | |
| [Feature 4] | | | | | | |
| [Feature 5] | | | | | | |
| [ADD MORE FEATURES SPECIFIC TO YOUR PRODUCT] | | | | | | |

---

## 6. STRATEGIC RECOMMENDATIONS

**A. MUST MATCH (Table Stakes):**
- Features we cannot launch without
- Industry standards we must meet

**B. MUST EXCEED (Differentiation):**
- Areas where we should clearly win
- Specific improvements with rationale

**C. CAN SKIP (Not Worth It):**
- Patterns that don't add value
- Features that increase complexity without ROI

**D. WATCH OUT FOR:**
- Common mistakes competitors made
- Patterns that look good but fail

---

## OUTPUT FORMAT:

# COMPETITIVE ANALYSIS: [Feature Name]

## Executive Summary
[3-4 sentence overview]

## 1. Common Patterns (Table Stakes)
[Detailed analysis]

## 2. Unique Approaches
[Detailed analysis]

## 3. UX Gaps & Frustrations
[Detailed analysis]

## 4. Visual & Interaction Patterns
[Detailed analysis]

## 5. Comparison Matrix
[Full table]

## 6. Strategic Recommendations
- Must Match
- Must Exceed
- Can Skip
- Watch Out For

## 7. Top 3 Differentiation Opportunities
1. [Opportunity + implementation]
2. [Opportunity + implementation]
3. [Opportunity + implementation]

---

IMPORTANT INSTRUCTIONS:
1. Reference specific screenshots
2. Quantify when possible
3. Be honest about competitor strengths
4. Tie observations to user impact
5. Distinguish visible features from inferred behavior
6. Highlight contradictions between competitors
7. Identify what's NOT in any competitor (gaps = opportunities)

Analyze the [NUMBER] uploaded competitor screenshots using this framework.
```

---

## 💡 Pro Tips

### For Better Results:
- **Capture full flows** not just single screens
- **Include 5+ competitors** for pattern recognition
- **Annotate screenshots** with key elements highlighted
- **Note context** (when feature appears, who uses it)

### Common Mistakes:
- ❌ Only screenshotting the "happy path"
- ❌ Missing edge cases and error states
- ❌ Comparing features in isolation
- ❌ Not validating with actual users

## 🔗 Next Steps

After running this prompt:
1. Review patterns with team
2. Move to **[Concept Generation](./03-concept-generation.md)**
3. Reference findings during **[Design Critique](./05-design-critique.md)**

---

[← Back to Library](../README.md)
