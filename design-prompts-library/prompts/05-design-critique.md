# 🎯 Design Critique Prompt

> **Use this prompt to:** Get comprehensive multi-dimensional critique on design concepts.

## When to Use

- Pre-user testing
- Before stakeholder presentation
- When deciding between concepts
- After receiving initial feedback

## What You'll Need

- ✅ Screenshots of design concepts (2-5 ideal)
- ✅ Brief description of each concept
- ✅ Project context
- ✅ ~15-20 minutes for AI processing

## Expected Output

- Multi-dimensional analysis (usability, domain, accessibility, scalability)
- Scored comparison matrix
- Detailed strengths/weaknesses per concept
- Specific modifications required
- Final recommendation with rationale

---

## 📋 The Prompt

```
I'm a Senior Product Designer seeking comprehensive critique on design concepts before user testing.

CONCEPTS UNDER REVIEW: [NUMBER] design concepts (screenshots attached)

CONCEPT 1: [BRIEF NAME AND DESCRIPTION]
CONCEPT 2: [BRIEF NAME AND DESCRIPTION]
CONCEPT 3: [BRIEF NAME AND DESCRIPTION]

PROJECT CONTEXT:
- Product: [YOUR PRODUCT]
- Feature: [WHAT YOU'RE DESIGNING]
- Stage: Pre-prototyping critique
- Goal: Identify strengths/weaknesses to refine

---

YOUR ROLE:
Act as a panel of senior experts:
- Senior UX Designer (usability focus)
- [INDUSTRY] Software Architect (scale/integration focus)
- Accessibility Specialist (WCAG compliance focus)
- Performance Engineer (scalability focus)
- Customer Success Manager (real-world usage focus)

Provide critique with the depth each expert would bring.

---

CRITIQUE FRAMEWORK:

## DIMENSION 1: USABILITY (Multi-Role Analysis)

### A. PRIMARY USER PERSPECTIVE
**Profile:** [DESCRIBE PRIMARY USER]

**Evaluate:**
- Speed of common tasks
- Keyboard shortcut support
- Efficiency at scale
- Time wasted on unnecessary steps
- Memorability
- Customization options
- Error recovery efficiency

**Quantify when possible:**
- Time to complete typical task
- Number of clicks/actions
- Cognitive load

### B. SECONDARY USER PERSPECTIVE
**Profile:** [DESCRIBE OCCASIONAL USER]

**Evaluate:**
- Discoverability
- Learnability (first-time success)
- Confidence
- Safety
- Recoverability
- Help availability
- Feedback clarity

**Specific scenarios:**
- First time using
- Returning after long gap
- Unfamiliar action type

### C. DEVICE/CONTEXT-SPECIFIC USER
**Profile:** [DESCRIBE EDGE-CASE USER - mobile/tablet/specific context]

**Evaluate:**
- Touch target sizes
- Gesture support
- Screen real estate
- Hover-state alternatives
- Orientation handling
- One-handed operation
- Connection reliability

**Specific scenarios:**
- [SCENARIO 1]
- [SCENARIO 2]
- [SCENARIO 3]

### USABILITY OUTPUT:

For each concept:
```
USABILITY ANALYSIS: Concept [#]

PRIMARY USER SCORE: X/10
- Strengths: [Specific elements]
- Weaknesses: [Specific friction]
- Critical Issues: [Showstoppers]
- Time estimate: ~X seconds
- Recommendations: [Specific changes]

SECONDARY USER SCORE: X/10
- Strengths: [What aids them]
- Weaknesses: [Confusion points]
- Critical Issues: [Barriers]
- First-time success: X%
- Recommendations: [Specific changes]

CONTEXT-SPECIFIC USER SCORE: X/10
- Strengths: [What works]
- Weaknesses: [Issues]
- Critical Issues: [Showstoppers]
- Recommendations: [Specific changes]

OVERALL USABILITY: X/30
```

---

## DIMENSION 2: [DOMAIN-SPECIFIC] CONSIDERATIONS

[CUSTOMIZE THIS SECTION FOR YOUR DOMAIN]
- For B2B: Enterprise considerations
- For Consumer: Engagement/retention
- For Healthcare: Compliance/safety
- For Finance: Security/audit
- For Education: Learning outcomes

### A. [DOMAIN ASPECT 1]
**Evaluate:**
- [SPECIFIC CRITERIA]
- [SPECIFIC CRITERIA]

### B. [DOMAIN ASPECT 2]
**Evaluate:**
- [SPECIFIC CRITERIA]
- [SPECIFIC CRITERIA]

### C. [DOMAIN ASPECT 3]
**Evaluate:**
- [SPECIFIC CRITERIA]
- [SPECIFIC CRITERIA]

### DOMAIN OUTPUT:

For each concept:
```
[DOMAIN] ANALYSIS: Concept [#]

[ASPECT 1]: Strong/Adequate/Weak
- Concerns: [List]
- Recommendations: [List]

[ASPECT 2]: Strong/Adequate/Weak
- Concerns: [List]
- Recommendations: [List]

[ASPECT 3]: Strong/Adequate/Weak
- Concerns: [List]
- Recommendations: [List]

DOMAIN READINESS SCORE: X/10
```

---

## DIMENSION 3: ACCESSIBILITY (WCAG 2.1 AA)

### A. KEYBOARD NAVIGATION
**Evaluate:**
- All elements reachable
- Logical tab order
- Visible focus indicators
- Documented shortcuts
- No keyboard traps

### B. SCREEN READER COMPATIBILITY
**Evaluate:**
- Semantic HTML
- ARIA labels and roles
- Live regions
- Form labels
- Error announcements

### C. VISUAL ACCESSIBILITY
**Evaluate:**
- Color contrast (4.5:1 minimum)
- Information not by color alone
- Text sizing (16px minimum)
- Touch targets (44x44px)
- Animation preferences

### D. COGNITIVE ACCESSIBILITY
**Evaluate:**
- Clear language
- Consistent patterns
- Error prevention
- Time-based actions optional
- Help available

### ACCESSIBILITY OUTPUT:

For each concept:
```
ACCESSIBILITY ANALYSIS: Concept [#]

WCAG 2.1 AA COMPLIANCE: Pass/Partial/Fail

KEYBOARD: Score X/10
- Compliant: [List]
- Issues: [WCAG violations]
- Fixes: [Required changes]

SCREEN READER: Score X/10
- Compliant: [List]
- Issues: [Violations]
- Fixes: [Changes]

VISUAL: Score X/10
- Contrast ratios: [Measurements]
- Issues: [Problems]
- Fixes: [Changes]

COGNITIVE: Score X/10
- Clarity: [Assessment]
- Prevention: [Assessment]
- Fixes: [Changes]

OVERALL: X/40
COMPLIANCE GAPS: [List]
LEGAL RISK: Low/Medium/High
```

---

## DIMENSION 4: SCALABILITY

### A. PERFORMANCE AT SCALE
**Evaluate:**
- Rendering performance
- State management
- Filter/search responsiveness
- Action responsiveness
- Memory footprint

**Specific tests:**
- [SCALE LEVEL 1]: Performance
- [SCALE LEVEL 2]: Performance
- [SCALE LEVEL 3]: Performance

### B. UI DEGRADATION
**Evaluate:**
- What breaks first?
- Graceful degradation
- Pagination needs
- Progressive disclosure
- Summarization patterns

### C. NETWORK CONSIDERATIONS
**Evaluate:**
- Slow connection handling
- Offline state
- Optimistic updates
- Conflict resolution

### D. CONCURRENT USERS
**Evaluate:**
- Race conditions
- Optimistic locking
- Conflict notifications
- Merge strategies

### SCALABILITY OUTPUT:

For each concept:
```
SCALABILITY ANALYSIS: Concept [#]

PERFORMANCE:
- [SCALE 1]: [Rating]
- [SCALE 2]: [Rating]
- [SCALE 3]: [Rating]

UI DEGRADATION:
- First failure: [What breaks]
- Mitigation: [Approach]
- Changes: [List]

NETWORK:
- Slow handling: [Assessment]
- Offline: [Assessment]
- Recommendations: [List]

CONCURRENT:
- Race conditions: [Assessment]
- Conflict resolution: [Assessment]
- Recommendations: [List]

SCALABILITY SCORE: X/10
```

---

## SUMMARY OUTPUT:

# DESIGN CRITIQUE: [Feature Name]

## Executive Summary
[3-4 sentences on overall findings]

## Concept Comparison Matrix

| Dimension | Concept 1 | Concept 2 | Concept 3 |
|-----------|-----------|-----------|-----------|
| Primary User Usability | X/10 | X/10 | X/10 |
| Secondary User Usability | X/10 | X/10 | X/10 |
| Context User Usability | X/10 | X/10 | X/10 |
| [Domain] Readiness | X/10 | X/10 | X/10 |
| Accessibility | X/40 | X/40 | X/40 |
| Scalability | X/10 | X/10 | X/10 |
| **TOTAL** | **X/100** | **X/100** | **X/100** |

## Detailed Analysis Per Concept

### CONCEPT 1: [Name]
- Strengths: [3-5 specific elements]
- Weaknesses: [3-5 specific elements]
- Critical Fixes: [List]
- Best For: [User type/scenario]
- Recommendation: [Continue/Refine/Reject]

### CONCEPT 2: [Name]
[Same structure]

### CONCEPT 3: [Name]
[Same structure]

## Cross-Concept Insights

**Universal Issues:**
[Issues affecting all concepts]

**Best Patterns:**
[Strong elements to combine]

**Worst Patterns:**
[Elements to avoid]

## Final Recommendation

**Recommended Concept:** [#]
**Rationale:** [Why]

**Required Modifications:**
1. [Specific change]
2. [Specific change]
3. [Specific change]

**Validation Plan:**
- Test [X] with [user type]
- Validate [Y] technically
- Verify [Z] with stakeholders

**Risk Assessment:**
- Low risk: [List]
- Medium risk: [List]
- High risk: [List + mitigations]

---

IMPORTANT INSTRUCTIONS:
1. Be specific - cite exact UI elements
2. Quantify when possible
3. Reference WCAG criteria for accessibility
4. Don't be diplomatic - identify real problems
5. Provide actionable fixes
6. Consider immediate AND long-term scalability
7. Think about real production environments

Provide the comprehensive critique now.
```

---

## 💡 Pro Tips

### For Better Results:
- **Upload high-quality screenshots** (full screens, not crops)
- **Include all states** (default, hover, active, error)
- **Provide context per concept** (what's different)
- **Be specific about user types** (helps scoring)

### Common Mistakes:
- ❌ Comparing too many concepts (3 max for clarity)
- ❌ Vague descriptions (AI can't critique what it doesn't see)
- ❌ Skipping domain customization
- ❌ Ignoring accessibility findings

## 🔗 Next Steps

After running this prompt:
1. Apply critical fixes to top concept
2. Test with users to validate
3. Refine based on testing
4. Move to **[Component Specification](./06-component-specification.md)**

---

[← Back to Library](../README.md)
