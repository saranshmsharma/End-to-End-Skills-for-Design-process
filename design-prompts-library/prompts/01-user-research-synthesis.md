# 🔍 User Research Synthesis Prompt

> **Use this prompt to:** Analyze user interview transcripts and extract actionable design insights.

## When to Use

- After conducting user interviews (3+ recommended)
- Before starting ideation
- To validate assumptions with real user data
- When synthesizing research for stakeholder presentations

## What You'll Need

- ✅ User interview transcripts (text or document files)
- ✅ Basic project context (product, feature, users)
- ✅ ~15-20 minutes for AI processing

## Expected Output

- Categorized pain points with severity ratings
- User mental models with direct quotes
- Edge cases prioritized by frequency
- Success criteria with measurable metrics
- Cross-cutting insights and design implications

---

## 📋 The Prompt

```
I'm a Senior Product Designer conducting user research synthesis. I've uploaded [NUMBER] user interview transcripts and need a comprehensive analysis to inform my design decisions.

PROJECT CONTEXT:
- Product: [DESCRIBE YOUR PRODUCT]
- Feature/Problem area: [WHAT YOU'RE DESIGNING]
- Target users: [WHO YOUR USERS ARE]
- Use cases: [PRIMARY USE CASES]
- Current state: [HOW USERS HANDLE THIS TODAY]

INTERVIEW DETAILS:
- Number of interviews: [NUMBER]
- Duration: [AVERAGE TIME]
- Format: [STRUCTURED/SEMI-STRUCTURED/OPEN]
- Participant profile: [WHO YOU INTERVIEWED]

YOUR TASK:
Analyze these transcripts with the rigor of a UX researcher preparing design requirements. Extract actionable insights that will directly inform interface design, interaction patterns, and technical requirements.

---

ANALYSIS FRAMEWORK:

## 1. PAIN POINTS (Current State Problems)

Extract and categorize every problem, frustration, or inefficiency mentioned. For each pain point:

**A. QUOTE THE EXACT PROBLEM:**
- Use direct quotes from transcripts (cite participant + paragraph)
- Preserve user language (don't paraphrase unless clarifying)

**B. FREQUENCY & SEVERITY:**
- How many participants mentioned this? (X/[total])
- Severity rating based on user language:
  - CRITICAL: "I can't do my job", "This blocks me", "I waste hours"
  - HIGH: "Very frustrating", "Major issue", "Happens constantly"
  - MEDIUM: "Annoying", "Wish this was better", "Slows me down"
  - LOW: "Minor inconvenience", "Not a big deal"

**C. CONTEXT OF OCCURRENCE:**
- When does this pain point surface? (specific workflow step)
- How often? (daily, weekly, monthly, rare)
- What triggers it? (task type, scale, user role)

**D. CURRENT WORKAROUNDS:**
- How do users cope now?
- What manual processes have they created?
- What external tools do they use?

**E. THEME GROUPING:**
Group related pain points under categories such as:
- Efficiency/Speed Issues
- Error Prevention/Safety Concerns
- Lack of Visibility/Feedback
- Cognitive Load/Mental Overhead
- Technical Limitations
- Permission/Access Issues
- Mobile/Device Constraints
- Collaboration/Team Coordination
- [ADD CATEGORIES SPECIFIC TO YOUR PRODUCT]

FORMAT EXAMPLE:
```
THEME: [Theme Name]

PAIN POINT: [Pain Point Title]
- Quote: "[Exact user quote]" ([Participant], para [#])
- Frequency: [X/Total] participants
- Severity: [Critical/High/Medium/Low]
- Context: [When and how often it occurs]
- Workaround: [Current coping mechanism]
- Impact: [Time/cost/frustration]
```

---

## 2. MENTAL MODELS (User Expectations & Analogies)

Identify how users THINK about this problem space.

**A. DIRECT ANALOGIES:**
- What tools/experiences do they compare this to?
- Quote exact analogies: "It should work like [X]"

**B. CONCEPTUAL MODELS:**
- How do they describe the ideal flow? (step-by-step)
- What metaphors do they use?
- What visual representations do they mention?

**C. INTERACTION EXPECTATIONS:**
- Expected input methods
- Expected feedback
- Expected safety mechanisms

**D. ROLE-BASED DIFFERENCES:**
- Do power users think differently than occasional users?
- Do different roles expect different capabilities?

FORMAT EXAMPLE:
```
MENTAL MODEL: [Model Name]

User Quote: "[Exact analogy or expectation]"
Participant: [Name + Role]
Referenced Features: [What they expect]
Interaction Expectations: [How they expect it to work]
Cross-referenced by: [X/Total participants mentioned similar]
```

---

## 3. EDGE CASES & FAILURE SCENARIOS

Extract every "what if" scenario, error condition, or failure mode mentioned.

**A. USER-MENTIONED EDGE CASES:**
- Quote exactly what they said
- Categorize by type:
  - USER BEHAVIOR: Accidental actions, confusion, mistakes
  - SYSTEM CONSTRAINTS: Timeouts, permission changes, technical limits
  - DATA ISSUES: Invalid items, duplicates, dependencies, conflicts
  - PARTIAL FAILURES: Some succeed, others fail

**B. FREQUENCY RANKING:**
- How many participants mentioned this?
- Did they describe it as common or rare?

**C. CURRENT IMPACT:**
- What happens today when this edge case occurs?
- How do they recover?
- What's the cost?

**D. IMPLICIT EDGE CASES:**
- Read between the lines: what risks are implied but not stated?

FORMAT EXAMPLE:
```
EDGE CASE: [Scenario Title]

User Quote: "[Exact user quote]"
Frequency: [X/Total] participants
Type: [USER BEHAVIOR/SYSTEM/DATA/PARTIAL FAILURE]
Scenario: [Detailed description]
Current Impact: [What happens now]
Severity: [Critical/High/Medium/Low]
Design Implication: [What design must address]
```

---

## 4. SUCCESS CRITERIA (Definition of "Working Well")

Extract both explicit and implicit measures of success.

**A. EXPLICIT METRICS:**
- Direct quotes about measurable success
- Time saved, error reduction, task completion
- User satisfaction indicators

**B. TASK COMPLETION CRITERIA:**
- What does "done" look like?
- What confirmation do they need?
- What should they be able to do after?

**C. QUALITY INDICATORS:**
- Accuracy (no mistakes)
- Speed (faster than current method)
- Confidence (trust the system)
- Learnability (easy first time, easier second time)

**D. COMPARATIVE BENCHMARKS:**
- Compared to what? (current process, competitor tools)
- What's the target improvement?

FORMAT EXAMPLE:
```
SUCCESS METRIC: [Metric Name]

User Quote: "[Exact user quote about success]"
Measurement: [How to measure]
Target: [Specific goal]
Frequency: [X/Total] participants mentioned
Validation Method: [How to verify in testing]
```

---

## 5. CROSS-CUTTING INSIGHTS

**A. PATTERNS ACROSS PARTICIPANTS:**
- What did ALL participants mention? (universal needs)
- What did most mention? (strong signals)
- What did only one mention but feels critical? (edge innovation)

**B. CONTRADICTIONS:**
- Where do user needs conflict?
- How might we design for both?

**C. UNSTATED ASSUMPTIONS:**
- What are they assuming exists but not saying?
- What features are they NOT asking for?

**D. PRIORITY RANKING:**
- Top 5 must-haves (frequency + severity)
- Nice-to-haves
- Out of scope for v1

---

## OUTPUT FORMAT:

# RESEARCH SYNTHESIS: [Feature Name]

## PAIN POINTS (Grouped by Theme)
[Organized by themes, prioritized by severity]

## USER MENTAL MODELS
[Each model documented in detail]

## EDGE CASES & FAILURE SCENARIOS
[Categorized by priority: Critical / High / Medium / Low]

## SUCCESS CRITERIA
[Measurable metrics + qualitative indicators]

## CROSS-CUTTING INSIGHTS
[Universal needs, contradictions, priority ranking]

## DESIGN IMPLICATIONS (Recommendations)
1. Core interaction model recommendation
2. Critical safety mechanisms needed
3. Feedback/visibility requirements
4. Mobile/responsive considerations
5. Error handling strategy
6. V1 scope recommendations
7. V2/V3 deferrals

---

IMPORTANT INSTRUCTIONS:
1. Be exhaustive - don't skip details
2. Use exact quotes - preserve user language
3. Quantify everything - frequency, severity, impact
4. Highlight contradictions - call out conflicts
5. Think like a designer - connect insights to design decisions
6. Be skeptical - flag discrepancies between stated and observed
7. Connect dots - link pain points to mental models to success
8. Prioritize ruthlessly - critical vs. nice-to-have

Now analyze the [NUMBER] uploaded interview transcripts using this framework.
```

---

## 💡 Pro Tips

### For Better Results:
- **Upload high-quality transcripts** with clear participant attribution
- **Include diverse user types** in your sample (power users + occasional users)
- **Provide rich context** about your product and current state
- **Run follow-up queries** if initial output lacks depth

### Common Mistakes:
- ❌ Skipping bracket fields (generic outputs)
- ❌ Uploading only one interview (no patterns to find)
- ❌ Not validating insights with users
- ❌ Treating output as final without human review

## 🔗 Next Steps

After running this prompt:
1. Review insights with stakeholders
2. Move to **[Competitive Analysis](./02-competitive-analysis.md)**
3. Use insights to inform **[Concept Generation](./03-concept-generation.md)**

---

[← Back to Library](../README.md)
