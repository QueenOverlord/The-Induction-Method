# The Clean Room Protocol (CRP)

### This protocol creates a verifiable chain of trust between you and your AI, ensuring every knowledge artifact you create is grounded in objective, external truth.

[← Return to The Cognitive Pressure Playbook](../playbooks/the-cognitive-pressure-playbook.md)

#### **Executive Summary**
> **Objective:** To produce a pristine, fact-checked "atomic note" by mandating a structured research and verification phase before the final output is created.
> 
> **Use Case:** Before finalizing any note, documentation, or claim where factual accuracy is non-negotiable. This is the quality assurance standard for your knowledge base.
> 
> **Expected Output:** A "Verification Manifest" proving the research was done, followed by a clean, impeccably formatted "Gallery" note ready for use.

---

## 1. Strategic Briefing (The "Why")

The core vulnerability of Large Language Models is **hallucination**—the tendency to state falsehoods with complete confidence. The Clean Room Protocol is the direct countermeasure. It creates an intellectual "airlock" between the messy, unpredictable world of AI-generated content and the clean, reliable world of your personal knowledge base. By mandating a "Workspace" phase for research and a "Gallery" phase for presentation, it forces a deliberate, evidence-based workflow. This protocol transforms your AI from a potential source of misinformation into a disciplined, auditable research assistant, ensuring the knowledge you rely on is built on a foundation of verifiable fact.

---

## 2. Operational Steps (The "How")

This protocol consists of a structured, multi-step dialogue initiated by a single, zero-input Master Prompt.

> **Watch It in Action:** To see how these steps flow together, here is a short demonstration of the entire protocol, from the initial query to the final, verified note.
>
> ![Demo of the Clean Room Protocol in Action](../gifs/demo-cleanroom.gif)

### Step 1: Initiate the Verification & Synthesis Engine

Copy the Master Prompt below and paste it into your AI interface. **You do not need to edit it.** The AI will guide you through the rest of the process.

> #### Master Prompt: The Verification & Synthesis Engine
> ```
> # MISSION: INITIATE THE CLEAN ROOM PROTOCOL - WORKSPACE PHASE
>
> You are a world-class Research Analyst and Fact-Checker. Your purpose is to guide me through a structured process to verify a claim and generate a pristine, fact-checked note.
>
> ---
> ### **STEP 1: THE CORE REQUEST**
>
> Your first and only action is to introduce yourself and ask me for the two key parameters for our mission. You must present the questions exactly as follows, and nothing more:
>
> "I am your Research Analyst. To begin, please state the claim, topic, or question you would like to verify.
>
> The output language is currently set to **English**. If you would like to change it, please specify the new language."
>
> After asking these questions, you must **STOP** and await my response.
>
> ---
> ### **STEP 2: SOURCE APPROVAL**
>
> Once I provide the claim, you will identify the top 2-3 primary or high-authority secondary sources you will use for verification. Your next response must be:
>
> "Understood. To verify the claim '[The claim I provided],' I propose consulting the following sources:
> - [Source 1]
> - [Source 2]
> - [Source 3]
>
> Do these sources have your approval?"
>
> After asking this question, you must **STOP** and await my approval.
>
> ---
> ### **STEP 3: THE VERIFICATION MANIFEST**
>
> Once I approve the sources, you will conduct your research and then generate the final output for this phase: a single Markdown block formatted *exactly* as follows.
>
> > **[BEGIN VERIFICATION MANIFEST]**
> > **Claim:** [The original claim to be verified]
> > **Verdict:** [e.g., True / Mostly True / True with Conditions / Misleading / False]
> > **Summary:** [A concise, 2-3 sentence summary of the findings in the specified Output Language.]
> > **Key Nuances:** [Bulleted list of critical conditions, exceptions, or details. If none, state "None."]
> > **Sources Consulted:** [Bulleted list of the approved high-authority sources with links.]
> > **[END VERIFICATION MANIFEST]**
>
> ---
>
> You have your full mission instructions. Begin Step 1 now.
> ```

### Step 2: State Your Claim & Language

Respond to the AI's questions. Provide the claim you want to verify and specify a different output language if needed.

### Step 3: Approve the Sources

The AI will propose its sources. Review them for quality. Respond with "Yes, proceed" or suggest better sources. This is a critical quality gate.

### Step 4: Receive the Verification Manifest

The AI will perform the research and deliver the structured "Verification Manifest." This is the proof of work for the protocol. Once you have this, you can proceed to create the final, clean "Gallery" note.

---

## 3. Field Notes & Best Practices

- **Pro-Tip:** If the AI proposes a generic source like "Wikipedia," challenge it. Ask for the primary source that the Wikipedia article itself cites. This trains the AI to dig deeper.
- **Common Pitfall:** Accepting the AI's proposed sources without scrutiny. The quality of the output is entirely dependent on the quality of the input sources. Always act as the final gatekeeper.
- **Integration Note:** The "Verification Manifest" produced by this protocol is the perfect "proof of work" to store alongside your final note. The "Gallery" note itself is the ideal input for the **"Atomic Knowledge Protocol (AKP)"**.