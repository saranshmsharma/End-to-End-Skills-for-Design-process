# 📝 Example: Filled-In Research Synthesis Prompt

This example shows how to fill in the bracketed fields with real project context.

## Context

**Project:** Designing a bulk action feature for a B2B workflow tool  
**Stage:** Post-user-research, pre-ideation  
**Files uploaded:** 3 user interview transcripts

---

## Example Filled Prompt

```
I'm a Senior Product Designer conducting user research synthesis. I've uploaded 3 user interview transcripts and need a comprehensive analysis to inform my design decisions.

PROJECT CONTEXT:
- Product: B2B workflow automation platform for mid-size companies
- Feature/Problem area: Bulk action capability (selecting and acting on 10-500 items simultaneously)
- Target users: Team admins, project managers, IT operations staff
- Use cases: Bulk updates to permissions, task assignments, status changes, archiving, deletion
- Current state: Users must update items one-by-one (major pain point)

INTERVIEW DETAILS:
- Number of interviews: 3
- Duration: Average 38 minutes each
- Format: Semi-structured, open-ended questions
- Participant profile: 
  * Sarah Chen - IT Operations Manager (450 employee company)
  * Marcus Thompson - Project Administrator (2,400 employees)
  * Jennifer Rodriguez - Customer Success Manager (180 employees)

YOUR TASK:
Analyze these transcripts with the rigor of a UX researcher preparing design requirements. Extract actionable insights that will directly inform interface design, interaction patterns, and technical requirements.

[Rest of prompt continues as in template...]
```

---

## What Makes This Good

✅ **Specific product description** - Not just "a SaaS app"  
✅ **Clear feature scope** - Item ranges defined (10-500)  
✅ **Concrete users** - Named roles with company sizes  
✅ **Real participant info** - Name, role, company size  
✅ **Defined current state** - The problem to solve  

## What to Avoid

❌ Vague descriptions like "our product"  
❌ Generic users like "professionals"  
❌ Missing context about current state  
❌ Skipping participant details  

---

## Sample Output (Excerpt)

```
# RESEARCH SYNTHESIS: Bulk Actions Feature

## PAIN POINTS (Grouped by Theme)

### THEME: Efficiency/Speed Issues

**PAIN POINT: No bulk selection capability**
- Quote: "I had to select each person individually... Forty-seven times I did this." (Sarah, para 3)
- Frequency: 3/3 participants
- Severity: CRITICAL
- Context: Occurs during any multi-item update; daily for 2/3 participants
- Workaround: Manual spreadsheet tracking to avoid losing place
- Impact: 2-3 hours wasted per task that should take minutes

**PAIN POINT: Time-consuming repetitive workflows**
- Quote: "I had to migrate 78 customers... took me an entire afternoon." (Jennifer, para 4)
- Frequency: 3/3 participants
- Severity: HIGH
- Context: Quarterly migrations, monthly bulk updates
- Workaround: Block calendar for "admin days"
- Impact: 4-8 hours per occurrence

### THEME: Error Prevention/Safety Concerns

**PAIN POINT: No preview before destructive actions**
- Quote: "I accidentally removed admin access from someone who needed it." (Sarah, para 5)
- Frequency: 3/3 participants
- Severity: CRITICAL
- Context: Permission changes, bulk deletes
- Workaround: Triple-checking each action manually
- Impact: Production incidents, data recovery time

[Continues with full analysis...]
```

---

## Tips for Your Own Prompts

### 1. Be Project-Specific
Replace generic terms with your actual product, users, and context.

### 2. Use Real Numbers
"50-500 items" is better than "many items"

### 3. Include Participant Diversity
Mix power users, occasional users, different roles

### 4. State the Stakes
What happens if this design fails? Data loss? User frustration? Money?

### 5. Reference Existing Pain
"Currently users do X manually" gives the AI context to build on

---

## Next Steps After Filling

1. Save your customized prompt as a template
2. Reuse for similar projects (just swap context)
3. Iterate based on output quality
4. Share improvements via pull request

[← Back to Library](../README.md)
