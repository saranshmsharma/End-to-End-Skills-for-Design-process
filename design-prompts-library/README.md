# 🎨 Design Process Prompt Library

A comprehensive collection of AI prompts for product designers to streamline the entire design process — from research synthesis to developer handoff.

## 📋 What's Inside

This library contains **6 production-ready prompt templates** that cover every stage of the product design process:

1. **[User Research Synthesis](./prompts/01-user-research-synthesis.md)** — Analyze user interview transcripts
2. **[Competitive Analysis](./prompts/02-competitive-analysis.md)** — Compare competitor implementations
3. **[Concept Generation](./prompts/03-concept-generation.md)** — Generate diverse design concepts
4. **[Edge Case Brainstorming](./prompts/04-edge-case-brainstorming.md)** — Stress-test design concepts
5. **[Design Critique](./prompts/05-design-critique.md)** — Multi-dimensional concept critique
6. **[Component Specification](./prompts/06-component-specification.md)** — Developer handoff documentation

## 🚀 Quick Start

1. **Choose** the prompt for your current design stage
2. **Copy** the prompt template
3. **Replace** all `[BRACKETED FIELDS]` with your project context
4. **Paste** into Claude, ChatGPT, or any capable LLM
5. **Iterate** based on outputs

## 🎯 Use Cases

- **Solo designers** working without a research team
- **Startup founders** who design their own products
- **Design students** learning structured methodology
- **Senior designers** documenting and scaling their process
- **Design teams** establishing consistent workflows

## 📊 Time Savings

Based on real design projects:

| Phase | Traditional Time | With AI Prompts | Savings |
|-------|-----------------|-----------------|---------|
| Research synthesis | 3 hours | 20 min | 89% |
| Competitive analysis | 2 hours | 15 min | 87% |
| Concept generation | 4 hours | 15 min | 94% |
| Design critique | 3 hours | 25 min | 86% |
| Documentation | 4.5 hours | 1 hour | 78% |

## 🛠️ Tools Compatible With

- ✅ Claude (Anthropic)
- ✅ ChatGPT (OpenAI)
- ✅ Gemini (Google)
- ✅ Any capable LLM

**Recommended:** Claude Sonnet or Opus for best results with complex prompts.

## 📖 How to Use

### Step 1: Pick Your Stage
Each prompt corresponds to a specific design phase. Start with the one matching your current need.

### Step 2: Customize Context
Every prompt has bracketed fields like `[YOUR PRODUCT]` or `[FEATURE NAME]`. Replace these with specifics about your project.

**Example:**
```
Before: "Product: [YOUR PRODUCT]"
After: "Product: B2B workflow automation platform"
```

### Step 3: Provide Inputs
Most prompts expect uploads:
- Research synthesis → User interview transcripts
- Competitive analysis → Competitor screenshots
- Design critique → Design concept screenshots
- Component spec → Final design screenshots

### Step 4: Run & Iterate
Paste customized prompt + uploads into your AI tool. Refine outputs through follow-up questions.

## 🎓 Best Practices

### ✅ DO:
- Fill in ALL bracketed fields (specificity = better outputs)
- Provide actual user data (real interviews, real screenshots)
- Use AI outputs as starting points, not final answers
- Validate insights with real users when possible
- Iterate on prompts based on what works for your domain

### ❌ DON'T:
- Use prompts without customization
- Trust AI outputs blindly without validation
- Skip the human design judgment step
- Use AI to replace design thinking — it accelerates it
- Apply prompts to high-stakes decisions without verification

## 📁 Repository Structure

```
design-prompts-library/
├── README.md
├── LICENSE
├── prompts/
│   ├── 01-user-research-synthesis.md
│   ├── 02-competitive-analysis.md
│   ├── 03-concept-generation.md
│   ├── 04-edge-case-brainstorming.md
│   ├── 05-design-critique.md
│   └── 06-component-specification.md
├── examples/
│   ├── filled-research-synthesis.md
│   └── sample-outputs.md
└── CONTRIBUTING.md
```

## 🤝 Contributing

Have a prompt that works well for your team? Found a way to improve these templates?

1. Fork this repository
2. Create a new branch (`git checkout -b feature/improve-prompt`)
3. Make your changes
4. Submit a pull request

Please follow the [contributing guidelines](./CONTRIBUTING.md).

## 📜 License

MIT License — Free to use, modify, and distribute.


**Made with ❤️ for product designers building better products**
