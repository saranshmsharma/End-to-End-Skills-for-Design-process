# 💡 Concept Generation Prompt

> **Use this prompt to:** Generate diverse, well-reasoned design concepts based on constraints.

## When to Use

- During ideation phase
- After research and competitive analysis
- Before committing to a design direction
- When exploring solution space broadly

## What You'll Need

- ✅ Clear user context (who + what + when)
- ✅ Defined constraints (technical, UX, business)
- ✅ ~15-20 minutes for AI processing

## Expected Output

- 10 distinct design concepts
- Trade-off analysis for each
- Comparison matrix
- Top 3 recommendations
- Concepts to prototype

---

## 📋 The Prompt

```
I'm a Senior Product Designer in the ideation phase. I need to generate diverse, well-reasoned design concepts that can be evaluated against user needs and technical constraints.

PROJECT CONTEXT:
- Product: [YOUR PRODUCT]
- Feature: [WHAT YOU'RE DESIGNING]
- Stage: Concept generation (pre-prototyping)
- Goal: Generate 10 distinct concepts before committing to direction

USER CONTEXT:
- Primary users: [WHO USES THIS MOST]
- Secondary users: [WHO ELSE USES IT]
- Tertiary users: [OCCASIONAL USERS]
- Use cases: [PRIMARY USE CASES]

USAGE PATTERNS:
- Power users: [FREQUENCY + VOLUME]
- Regular users: [FREQUENCY + VOLUME]
- Occasional users: [FREQUENCY + VOLUME]

DEVICE CONTEXT:
- Primary: [MAIN DEVICE - % USAGE]
- Secondary: [SECONDARY DEVICE - % USAGE]
- Tertiary: [LEAST USED DEVICE - % USAGE]

---

CONSTRAINTS (Non-Negotiable):

## TECHNICAL CONSTRAINTS:
- [TECHNICAL REQUIREMENT 1]
- [TECHNICAL REQUIREMENT 2]
- [TECHNICAL REQUIREMENT 3]
- [PERFORMANCE REQUIREMENTS]
- [INTEGRATION REQUIREMENTS]

## UX CONSTRAINTS:
- [USABILITY REQUIREMENT 1]
- [USABILITY REQUIREMENT 2]
- [SAFETY/ERROR PREVENTION]
- [FEEDBACK REQUIREMENTS]
- [ACCESSIBILITY REQUIREMENTS]

## BUSINESS CONSTRAINTS:
- [DESIGN SYSTEM ALIGNMENT]
- [TIMELINE CONSTRAINTS]
- [TECHNICAL DEBT CONSIDERATIONS]
- [COMPLIANCE REQUIREMENTS]

## USER CONSTRAINTS:
- [POWER USER NEEDS]
- [OCCASIONAL USER NEEDS]
- [TRUST/CONFIDENCE REQUIREMENTS]
- [ERROR HANDLING NEEDS]

---

GENERATE 10 DISTINCT CONCEPTS:

Each concept should address ALL CORE ELEMENTS:

## CORE ELEMENT 1: [PRIMARY INTERACTION]
[DESCRIBE THE MAIN USER ACTION]

Considerations:
- [CONSIDERATION 1]
- [CONSIDERATION 2]
- [CONSIDERATION 3]

## CORE ELEMENT 2: [SECONDARY INTERACTION]
[DESCRIBE THE SECONDARY USER ACTION]

Considerations:
- [CONSIDERATION 1]
- [CONSIDERATION 2]

## CORE ELEMENT 3: [FEEDBACK/CONFIRMATION]
[HOW USERS GET FEEDBACK]

Considerations:
- [CONSIDERATION 1]
- [CONSIDERATION 2]

## CORE ELEMENT 4: [ERROR/EDGE HANDLING]
[HOW ERRORS ARE HANDLED]

Considerations:
- [CONSIDERATION 1]
- [CONSIDERATION 2]

---

FORMAT FOR EACH CONCEPT:

```
## CONCEPT [#]: [Memorable Name]

### Conceptual Summary (1-2 sentences)
[What's the big idea? What's unique?]

### Layout Structure
- Primary view layout: [description]
- Element positions: [description]
- Flow type: [modal, inline, full-page, etc.]
- Feedback placement: [description]
- Error display: [description]

### Interaction Model

**Phase 1 - [STAGE NAME]:**
1. User does X
2. System responds with Y
3. User can Z

**Phase 2 - [STAGE NAME]:**
1. [Step-by-step]

**Phase 3 - [STAGE NAME]:**
1. [Step-by-step]

### Visual Reference
- Colors used: [specifics]
- Typography hierarchy: [specifics]
- Spacing/density: [specifics]
- Icon usage: [specifics]

### Trade-offs Analysis

**For PRIMARY USERS:**
- Pros: [Strengths]
- Cons: [Friction points]
- Suitability: [1-10 score with rationale]

**For SECONDARY USERS:**
- Pros: [Strengths]
- Cons: [Confusion points]
- Suitability: [1-10 score with rationale]

**For [DEVICE CONTEXT] USERS:**
- Pros: [What works]
- Cons: [What's challenging]
- Suitability: [1-10 score with rationale]

### Risk Assessment
- Implementation complexity: [Low/Medium/High]
- User learning curve: [Low/Medium/High]
- Edge case handling: [Strong/Adequate/Weak]
- Accessibility: [Strong/Adequate/Weak]

### Best For
[Which scenario does this serve best?]

### Differentiation
[What makes this unique?]
```

---

REQUIREMENTS FOR THE 10 CONCEPTS:

To ensure diversity, generate concepts spanning:

1. **CONCEPT 1:** Traditional/Familiar
   - Standard pattern users already know
   - Reference point for comparison

2. **CONCEPT 2:** Safety-First
   - Maximum error prevention
   - Best for occasional users

3. **CONCEPT 3:** Speed-First
   - Power user optimized
   - Best for daily heavy users

4. **CONCEPT 4:** Wizard/Step-Based
   - Linear flow through stages
   - Best for complex tasks

5. **CONCEPT 5:** Inline/Contextual
   - Actions happen in-place
   - Best for quick tasks

6. **CONCEPT 6:** Side Panel
   - Persistent secondary panel
   - Best for review/modification

7. **CONCEPT 7:** Filter/Query-Based
   - Build through criteria
   - Best for data-driven tasks

8. **CONCEPT 8:** Visual/Card-Based
   - Visual representation
   - Best for visual reviewers

9. **CONCEPT 9:** AI/Conversational
   - Natural language input
   - Most innovative approach

10. **CONCEPT 10:** Hybrid/Best-of-All
    - Combines strongest elements
    - Most production-ready

---

OUTPUT REQUIREMENTS:

After generating all 10 concepts, provide:

## SUMMARY COMPARISON TABLE

| Concept | Primary User Score | Secondary User Score | Device Score | Implementation Complexity | Innovation Level |
|---------|-------------------|---------------------|--------------|--------------------------|------------------|
| 1. [Name] | X/10 | X/10 | X/10 | Low/Med/High | Low/Med/High |

## TOP 3 RECOMMENDATIONS

**1. SAFEST BET (Lowest Risk):**
- Concept # and rationale

**2. HIGHEST UPSIDE (Most Differentiated):**
- Concept # and rationale

**3. MOST BALANCED (Best Compromise):**
- Concept # and rationale

## CONCEPTS TO PROTOTYPE
Recommend 3 concepts to move forward with:
- Why these 3 specifically
- What hypotheses each tests
- What to validate in user testing

---

IMPORTANT INSTRUCTIONS:
1. Make concepts genuinely different
2. Show real trade-offs (no concept is perfect)
3. Be specific about layouts
4. Consider edge cases in each
5. Think about implementation complexity
6. Include conventional and innovative approaches
7. Score honestly

Generate the 10 concepts now.
```

---

## 💡 Pro Tips

### For Better Results:
- **Be specific about constraints** (vague constraints = vague concepts)
- **Define user types clearly** (helps AI score appropriately)
- **Include both numbers and quality** (e.g., "50+ items, fast workflow")
- **State what's NOT acceptable** (helps AI avoid bad directions)

### Common Mistakes:
- ❌ Too few constraints (concepts won't be useful)
- ❌ Too many constraints (concepts will be similar)
- ❌ Not validating with users
- ❌ Picking favorite without testing

## 🔗 Next Steps

After running this prompt:
1. Pick top 3 concepts to explore
2. Run **[Edge Case Brainstorming](./04-edge-case-brainstorming.md)** on each
3. Build prototypes to test
4. Use **[Design Critique](./05-design-critique.md)** to refine

---

[← Back to Library](../README.md)
