# 📋 Component Specification Prompt

> **Use this prompt to:** Generate developer-ready component specifications.

## When to Use

- Final design ready for development
- Creating handoff documentation
- Building design system components
- Onboarding new developers

## What You'll Need

- ✅ Final design screenshots
- ✅ Tech stack info
- ✅ Design system reference
- ✅ ~20-25 minutes for AI processing

## Expected Output

- Complete component specification
- Anatomy and states documented
- Props/parameters defined
- Accessibility requirements
- Edge case handling
- Performance requirements
- Testing scenarios

---

## 📋 The Prompt

```
I'm a Senior Product Designer creating developer handoff documentation. I need a complete specification developers can implement without ambiguity.

COMPONENT: [COMPONENT NAME] (screenshots attached)
TARGET DEVELOPERS: [TECH STACK - e.g., React/TypeScript]
DESIGN SYSTEM: [YOUR DESIGN SYSTEM]
PRODUCT CONTEXT: [YOUR PRODUCT]

---

YOUR TASK:
Generate a production-ready component specification document with everything developers need to build correctly, handle edge cases, and meet quality standards.

---

SPECIFICATION FRAMEWORK:

## SECTION 1: COMPONENT OVERVIEW

**A. PURPOSE & USE CASE:**
- What problem does this solve?
- When should it be used?
- When should it NOT be used?

**B. USER STORIES:**
- As a [user type], I need [capability] so that [outcome]
- Cover all major user types

**C. DESIGN PRINCIPLES:**
- Design philosophies guiding this
- Performance considerations
- Accessibility commitments

---

## SECTION 2: COMPONENT ANATOMY

**A. STRUCTURAL ELEMENTS:**
For each element:
- Element name
- Purpose
- Visual reference
- Hierarchy/nesting

**B. INTERACTIVE ELEMENTS:**
For each:
- Element type
- Default appearance
- Available actions
- State variations
- Touch target size

**C. CONTENT ELEMENTS:**
For each:
- Content type
- Content source (props, state, API)
- Localization needs
- Empty states
- Error states

FORMAT EXAMPLE:
```markdown
### Component Anatomy

#### 1. [Element Name]
**Type:** [Interactive type]
**Purpose:** [What it does]
**Position:** [Where in UI]
**Size:** [Visual + touch target]
**States:**
- Default: [Appearance]
- Hover: [Changes]
- Focus: [Changes]
- Active: [Changes]
- Disabled: [Changes]
[Continue for all elements]
```

---

## SECTION 3: STATES & VARIATIONS

**A. PRIMARY STATES:**
- Default
- Loading
- Active
- Success
- Error (full)
- Error (partial)
- Empty

**B. STATE TRANSITIONS:**
- How does component move between states?
- Animation specifications
- Side effects

**C. ERROR STATES:**
- Network errors
- Permission errors
- Validation errors
- Timeout errors

FORMAT EXAMPLE:
```markdown
### State: [State Name]

**Trigger:** [What causes this state]
**Visual Indicators:**
- [Visual change 1]
- [Visual change 2]
- [Visual change 3]

**User Capabilities:**
- ✅ Can [action]
- ✅ Can [action]
- ❌ Cannot [action]
- ❌ Cannot [action]

**System Behavior:**
- [Behavior 1]
- [Behavior 2]

**Animation:**
- [Animation specs]

**Accessibility:**
- ARIA attributes
- Screen reader behavior
- Focus management

**Edge Cases:**
- [Edge case + handling]
```

---

## SECTION 4: PROPS & PARAMETERS

**A. REQUIRED PROPS:**
For each:
- Prop name
- TypeScript type
- Description
- Validation rules
- Example

**B. OPTIONAL PROPS:**
[Same details]

**C. CALLBACK FUNCTIONS:**
- Function signature
- When triggered
- Parameters
- Expected return

**D. CHILDREN/SLOTS:**
- Allowed types
- Slot positions
- Default content

FORMAT EXAMPLE:
```typescript
interface ComponentProps {
  /**
   * [Description]
   */
  propName: PropType;
  
  /**
   * [Description]
   * @default defaultValue
   */
  optionalProp?: PropType;
  
  /**
   * Callback when [event]
   * @param param - [Description]
   * @returns [Description]
   */
  onEvent: (param: ParamType) => ReturnType;
}
```

---

## SECTION 5: ACCESSIBILITY REQUIREMENTS

**A. ARIA ATTRIBUTES:**
- Required labels
- Required roles
- Required states
- Live regions

**B. KEYBOARD NAVIGATION:**
- Tab order
- Shortcuts
- Focus management
- Focus trap rules

**C. SCREEN READER:**
- Announcement strategy
- Reading order
- Dynamic updates
- Error announcements

**D. VISUAL ACCESSIBILITY:**
- Color contrast
- Touch targets
- Focus indicators
- Animation preferences

FORMAT EXAMPLE:
```markdown
### Accessibility Specifications

#### ARIA Implementation

**[Element]:**
```html
<element
  role="[role]"
  aria-label="[label]"
  aria-describedby="[id]"
/>
```

#### Keyboard Navigation

| Key | Context | Action |
|-----|---------|--------|
| [Key] | [When] | [Does what] |
```

---

## SECTION 6: EDGE CASE HANDLING

**A. INPUT EDGE CASES:**
- Empty data
- Single item
- Maximum capacity
- Invalid items

**B. INTERACTION EDGE CASES:**
- Rapid clicking
- Concurrent modifications
- Network failures

**C. STATE EDGE CASES:**
- Stale data
- Optimistic updates
- Rollback scenarios
- Sync conflicts

**D. PERMISSION EDGE CASES:**
- Mid-action permission changes
- Insufficient permissions
- Revoked access

FORMAT EXAMPLE:
```markdown
### Edge Case: [Scenario]

**Scenario:** [Description]

**Detection:**
- [How to detect]

**System Response:**
1. [Action 1]
2. [Action 2]
3. [Action 3]

**Code Example:**
```typescript
// Implementation example
```
```

---

## SECTION 7: VISUAL DESIGN SPECIFICATIONS

**A. SPACING:**
- Margin/padding (use design tokens)
- Grid alignment
- Responsive breakpoints

**B. TYPOGRAPHY:**
- Font families
- Sizes
- Line heights
- Weights

**C. COLORS:**
- Reference design tokens
- Hex codes as fallback
- Dark mode variations
- High contrast mode

**D. ICONS:**
- Library reference
- Sizes
- Colors
- States

**E. ANIMATIONS:**
- Duration
- Easing
- Triggers
- Reduced motion alternatives

---

## SECTION 8: PERFORMANCE REQUIREMENTS

**A. RENDERING:**
- Initial render time
- Re-render optimization
- Virtual scrolling rules
- Memoization strategy

**B. INTERACTION:**
- Click-to-feedback time (<100ms)
- Animation frame rate (60fps)
- Search/filter response time

**C. NETWORK:**
- API call batching
- Debouncing/throttling
- Optimistic updates
- Cache strategy

**D. MEMORY:**
- Cleanup on unmount
- Event listener removal
- Subscription cleanup

---

## SECTION 9: TESTING REQUIREMENTS

**A. UNIT TESTS:**
- Component rendering
- Prop handling
- State transitions
- Edge cases

**B. INTEGRATION TESTS:**
- API integration
- Multi-component interactions
- State management

**C. ACCESSIBILITY TESTS:**
- Keyboard navigation
- Screen reader
- Color contrast
- Focus management

**D. PERFORMANCE TESTS:**
- Render at scale
- Rapid interactions
- Memory leaks
- Network conditions

---

## OUTPUT FORMAT:

```markdown
# [Component Name] Specification

**Version:** 1.0
**Status:** Ready for Development
**Owner:** [Designer Name]
**Last Updated:** [Date]

## Table of Contents
1. Component Overview
2. Component Anatomy
3. States & Variations
4. Props & Parameters
5. Accessibility Requirements
6. Edge Case Handling
7. Visual Design Specifications
8. Performance Requirements
9. Testing Requirements
10. Implementation Notes

[Full specification follows]

## Appendix A: Design Files
- Figma file: [link]
- Prototypes: [link]
- Design tokens: [link]

## Appendix B: Related Documentation
- API documentation: [link]
- Design system: [link]
- Accessibility guidelines: [link]

## Appendix C: Open Questions
1. [Question]
2. [Question]

## Appendix D: Future Enhancements
- V2 features
- Known limitations
- Tech debt
```

---

IMPORTANT INSTRUCTIONS:
1. Be comprehensive - leave nothing to interpretation
2. Use code examples for clarity
3. Reference design tokens
4. Document all states explicitly
5. Specify exact ARIA attributes
6. Include performance benchmarks
7. Provide testing scenarios
8. Note dependencies
9. Make it self-contained

Generate the complete specification now.
```

---

## 💡 Pro Tips

### For Better Results:
- **Upload all states** (default, hover, error, etc.)
- **Reference your design system** by name
- **Specify exact tech stack** (React 18, TypeScript 5, etc.)
- **Include data structure examples** when possible

### Common Mistakes:
- ❌ Skipping edge cases
- ❌ Vague accessibility requirements
- ❌ No performance benchmarks
- ❌ Missing testing scenarios

## 🔗 Next Steps

After running this prompt:
1. Review spec with developers
2. Address open questions
3. Add to design system docs
4. Update Figma with annotations

---

[← Back to Library](../README.md)
