# Prompt Engineering

Master the art of writing effective prompts to get better results from AI.

## The CARE Framework

!!! success "CARE = Context + Action + Result + Example"
    The most effective prompts follow this structure.

### 1. Context 🎯

Provide background information:

- Your role (student, researcher)
- Your field/domain
- The situation

!!! example "Good Context"
    *"I am a Master's student in Marketing at Salahaddin University researching social media's impact on consumer behavior in the Kurdistan Region."*

---

### 2. Action ✏️

Clearly describe what you want:

- Be specific about the task
- Include constraints
- Specify any requirements

!!! example "Good Action"
    *"Identify 5 potential research gaps in this area from recent literature (2020-2024)."*

---

### 3. Result 📋

Describe the desired output:

- Format (table, bullet points, essay)
- Length (word count, number of items)
- Style (academic, casual)

!!! example "Good Result"
    *"For each gap, provide: description, significance, 2-3 research questions, and suggested methodology. Present in a structured format with clear headings."*

---

### 4. Example 💡

When possible, provide:

- Sample outputs
- Reference materials
- Models to follow

!!! example "Good Example"
    *"Here's an example of the format I need: [paste example]"*

---

## Complete CARE Prompt Example

```text
Act as an academic researcher specializing in Digital Marketing. 
I am a Master's student interested in studying social media marketing 
in the Kurdistan Region.

Analyze recent literature (2020-2024) and identify 5 potential 
research gaps. For each gap, provide:
- The gap description (what is missing)
- Why it matters (significance)  
- 2-3 potential research questions
- Suggested methodology

Focus on understudied contexts, populations, or variable combinations. 
Present in a structured format with clear headings.
```

---

## Quick Tips

| Do ✅ | Don't ❌ |
|------|---------|
| Be specific and detailed | Be vague ("help me with my thesis") |
| Specify the format you want | Accept whatever format AI gives |
| Ask for sources/citations | Trust citations without verifying |
| Iterate and refine | Accept first output as final |
| Provide context about yourself | Assume AI knows your situation |

---

## Advanced Techniques

### Chain of Thought
Ask AI to "think step by step" for complex problems.

### Role Assignment
Start with "Act as a [expert type]" to get specialized responses.

### Output Constraints
Specify exact formats: "Provide as a numbered list of exactly 5 items."

### Clarification Request
End prompts with: *"If you need any clarification, ask me before proceeding."*
