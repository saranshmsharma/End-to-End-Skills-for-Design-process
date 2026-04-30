# 🛡️ Edge Case Brainstorming Prompt

> **Use this prompt to:** Pressure-test design concepts and find every way they could fail.

## When to Use

- Before committing to prototype
- When validating a design direction
- Before user testing
- When stakes are high (data, money, safety)

## What You'll Need

- ✅ Detailed concept description
- ✅ Project context and stakes
- ✅ ~10-15 minutes for AI processing

## Expected Output

- Comprehensive edge case analysis
- Categorized by severity (Critical/High/Medium/Low)
- Required design modifications
- Risk assessment
- Validation plan

---

## 📋 The Prompt

```
I'm a Senior Product Designer pressure-testing a design concept before prototyping. I need to identify every way this design could fail in real-world conditions.

CONCEPT UNDER REVIEW: [CONCEPT NAME]

CONCEPT DESCRIPTION:
[PASTE FULL CONCEPT DESCRIPTION INCLUDING:]
- Layout structure
- Interaction model (step-by-step)
- Visual approach
- Target users

PROJECT CONTEXT:
- Product: [YOUR PRODUCT]
- Feature: [WHAT YOU'RE TESTING]
- Users: [WHO USES IT]
- Stakes: [LOW/MEDIUM/HIGH - WHY]

---

YOUR TASK:
Conduct exhaustive edge case analysis with the rigor of a QA engineer + UX researcher + adversarial designer combined. Find every scenario where this design could break, frustrate users, or cause issues.

---

ANALYSIS FRAMEWORK:

## CATEGORY 1: USER BEHAVIOR EDGE CASES

**A. ACCIDENTAL ACTIONS:**
- Misclicks
- Double-clicks
- Drag mistakes
- Keyboard accidents

**B. IMPATIENCE/RUSHING:**
- User skips steps
- User cancels mid-action
- User refreshes during operation
- User opens duplicate tabs
- User multi-tasks

**C. CONFUSION:**
- User doesn't understand state
- User loses track of progress
- User can't find action needed
- User misinterprets feedback
- User assumes wrong things

**D. ABANDONMENT:**
- User starts but doesn't finish
- User walks away mid-task
- User closes browser
- User loses connection

**E. RECOVERY ATTEMPTS:**
- User tries to undo after time limit
- User tries to retry
- User attempts to modify mid-process
- User tries to delete in-progress items

FORMAT EXAMPLE:
```
EDGE CASE: [Scenario Title]

SCENARIO:
[Detailed description of what happens]

LIKELIHOOD: [HIGH/MEDIUM/LOW]
IMPACT: [HIGH/MEDIUM/LOW]

CURRENT DESIGN HANDLING:
- [How concept addresses or doesn't]

FAILURE MODE:
- [What goes wrong]

DESIGN IMPLICATIONS:
1. [Specific change needed]
2. [Specific change needed]
3. [Specific change needed]

PRIORITY: [HIGH/MEDIUM/LOW + reasoning]
```

---

## CATEGORY 2: SYSTEM CONSTRAINT EDGE CASES

**A. NETWORK ISSUES:**
- Internet drops
- Slow connection timeouts
- Intermittent connectivity
- High latency

**B. SERVER ISSUES:**
- Backend timeouts
- Partial responses
- Rate limiting
- Authentication expiration
- Unexpected errors

**C. PERMISSION CHANGES:**
- User permissions change mid-action
- Target permissions change
- Access revoked
- Role changes

**D. CONCURRENT MODIFICATIONS:**
- Other users modify simultaneously
- Items deleted during action
- Items moved during action
- System auto-processes affect items

**E. CAPACITY/SCALE:**
- Operation exceeds limits
- Memory/CPU limits
- Database conflicts
- API rate limits

**F. STATE INCONSISTENCY:**
- UI shows different state than backend
- Cache stale during operation
- Multiple sessions out of sync
- Storage corruption

---

## CATEGORY 3: DATA INTEGRITY EDGE CASES

**A. INVALID DATA:**
- Items deleted by others
- Item type changed
- Corrupt data
- Locked items

**B. DEPENDENCIES:**
- Items have dependencies
- Cascading effects
- Circular dependencies
- Orphaned data

**C. DUPLICATES:**
- Same item selected multiple times
- Duplicates from views/filters
- Confusion in counts

**D. SPECIAL CASES:**
- Templates (cannot modify)
- Archived items
- External integrations
- Legacy data

**E. CONFLICTS:**
- Action conflicts with state
- Permission conflicts
- Naming conflicts
- Tag/category conflicts

---

## CATEGORY 4: ACCESSIBILITY EDGE CASES

**A. KEYBOARD NAVIGATION:**
- Can't reach elements
- Wrong tab order
- Focus lost during updates
- Shortcut conflicts

**B. SCREEN READERS:**
- States not announced
- Updates not detected
- Errors not announced
- Dynamic content missed

**C. VISUAL IMPAIRMENTS:**
- Color-only differentiation
- Insufficient contrast
- Small touch targets
- Text too small

**D. MOTOR IMPAIRMENTS:**
- Drag impossible
- Tiny click targets
- Time-based actions
- Precise movements required

---

## CATEGORY 5: SCALE/PERFORMANCE EDGE CASES

**A. RENDERING ISSUES:**
- Many items = slow scroll
- Animation lag
- DOM size impacts
- Memory issues

**B. OPERATION DURATION:**
- Long operations
- Session expiration
- Tab suspension
- Timeout exceeded

**C. UI DEGRADATION:**
- What breaks first?
- Visibility issues
- Responsiveness issues
- Filter performance

**D. ERROR AT SCALE:**
- Many errors at once
- Retry costs
- Pagination needs
- Memory footprint

---

## CATEGORY 6: CROSS-DEVICE EDGE CASES

**A. SESSION CONTINUITY:**
- Switching devices mid-task
- Status checks across devices
- Different views of same operation

**B. INPUT MISMATCHES:**
- Hover vs. no hover
- Screen size differences
- Stylus vs. finger
- Keyboard differences

**C. NOTIFICATION PREFERENCES:**
- Where do notifications appear?
- Push vs. browser
- Email fallbacks

---

## CATEGORY 7: BUSINESS LOGIC EDGE CASES

**A. APPROVAL WORKFLOWS:**
- Action requires approval
- Different rules per item
- Approval timeouts

**B. AUDIT REQUIREMENTS:**
- Compliance logging
- Justification requirements
- Approval trails

**C. NOTIFICATIONS:**
- Other users need updates
- External tool notifications
- Stakeholder visibility

**D. INTEGRATION CASCADES:**
- Connected tool updates
- Webhook failures
- Sync delays

---

## OUTPUT FORMAT:

# EDGE CASE ANALYSIS: [Concept Name]

## Executive Summary
- Total edge cases identified: [count]
- Critical issues: [count]
- High priority issues: [count]
- Medium priority issues: [count]
- Low priority issues: [count]

## CRITICAL EDGE CASES (Must Fix Before Prototyping)
[Detailed analysis of top issues]

## HIGH PRIORITY EDGE CASES (Fix in V1)
[Detailed analysis]

## MEDIUM PRIORITY EDGE CASES (Address in V1 if Possible)
[Brief analysis]

## LOW PRIORITY EDGE CASES (V2 Considerations)
[List]

## DESIGN MODIFICATIONS REQUIRED

Based on analysis, design must be modified to:
1. [Specific modification + rationale]
2. [Specific modification + rationale]
3. [Specific modification + rationale]

## RISK ASSESSMENT

**Concept Stress Test:**
- Strengths: [What holds up]
- Weaknesses: [What needs work]
- Recommendation: [Continue/Modify/Reject]

**Top 3 Risks:**
1. [Risk + mitigation]
2. [Risk + mitigation]
3. [Risk + mitigation]

## VALIDATION PLAN

Before committing, validate:
1. [Edge case to test]
2. [Edge case to test]
3. [Edge case to test]

---

IMPORTANT INSTRUCTIONS:
1. Be adversarial - assume users WILL break this
2. Don't assume "users won't do that"
3. Quantify likelihood and impact
4. Provide actionable modifications
5. Don't just identify - propose solutions
6. Consider first-time AND long-term users
7. Think about compounding edge cases

Begin the edge case analysis now.
```

---

## 💡 Pro Tips

### For Better Results:
- **Provide detailed concept description** (vague concepts = vague edge cases)
- **State actual stakes clearly** (data loss? money? safety?)
- **Include real user scenarios** not idealized ones
- **Think about your worst users**, not your best

### Common Mistakes:
- ❌ Assuming "users won't do that" (they will)
- ❌ Only testing happy paths
- ❌ Ignoring rare but high-impact cases
- ❌ Not prioritizing fixes

## 🔗 Next Steps

After running this prompt:
1. Update concept with required modifications
2. Run **[Design Critique](./05-design-critique.md)** on refined concept
3. Build prototype with edge cases handled
4. Test with users to validate

---

[← Back to Library](../README.md)
