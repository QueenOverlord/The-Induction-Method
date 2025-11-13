---
name: "🔬 Testing Report"
title: "🔬 Testing Report: [Protocol Name] on [AI Model Name]"
labels: ["testing", "feedback", "community-report"]
assignees: ''
body:
  - type: markdown
    attributes:
      value: |
        **Thank you for becoming a Battle-Tester!**

        Your feedback is the most valuable contribution to this project. By sharing your results, you are helping us build a resilient, model-agnostic arsenal for everyone. Please be as detailed as you can.

  - type: dropdown
    id: protocol
    attributes:
      label: "Protocol Tested"
      description: "Which protocol or tool from our playbook did you test?"
      options:
        - "The Cognitive MRI"
        - "The On-Demand Tutor"
        - "The Prompt Strategy Matrix"
        - "The Persona Forge"
        - "Clean Room Protocol"
        - "The Vector Priming Protocol"
        - "The Council Blueprints"
        - "The Epoch Protocol"
        - "The 3-Horizon Brainstorm"
        - "Other (Please specify below)"
    validations:
      required: true

  - type: input
    id: model
    attributes:
      label: "AI Model Used"
      description: "Which AI model and version did you use for this test?"
      placeholder: "e.g., Claude 3 Sonnet, GPT-4o, Llama 3 70B, Gemini 1.5 Pro"
    validations:
      required: true

  - type: dropdown
    id: outcome
    attributes:
      label: "Test Outcome"
      description: "At a high level, what was the result?"
      options:
        - "✅ Success: Worked perfectly as expected."
        - "⚠️ Partial Success: Worked, but with minor issues or needed tweaks."
        - "❌ Failure: Did not work or produced very low-quality results."
    validations:
      required: true

  - type: textarea
    id: results-log
    attributes:
      label: "Detailed Results & Log"
      description: |
        Please provide the details of your test. If possible, paste the full, unedited output from the AI model in a code block. This is incredibly helpful for our analysis.
      placeholder: |
        "I ran the first prompt of the Cognitive MRI. The AI understood the persona but failed to ask Socratic questions. Here is the full output:"
      render: markdown
    validations:
      required: true

  - type: textarea
    id: feedback
    attributes:
      label: "Feedback & Suggestions (Optional but Invaluable)"
      description: "Do you have any ideas for how to improve this protocol? Did you find a specific tweak that made it work better on your model? This is where the magic happens!"
      placeholder: |
        "I found that adding the line 'Think step-by-step before you answer' made it work much better on Model X. Maybe we should add that to the core prompt?"

  - type: markdown
    attributes:
      value: |
        ---
        Again, thank you for your contribution. You are helping to forge the future of this project.
---
