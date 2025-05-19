# Unsloth-LLaMA3-RecoveryPrompter

This repository powers a peer-led AI recovery assistant, fine-tuned for MARA-style affirmations, motivational prompts, and group-friendly check-ins using the `NousResearch/Meta-Llama-3-8B-Instruct` model, loaded via Unsloth in Colab. The toolkit provides structured prompts and technical strategies for creating trauma-informed, MAT-respecting, culturally inclusive responses suited for MARA groups, recovery centers, or integration into platforms like Anonymous Haven.

---

## Core Focus Areas

### 1. Motivation in Early Recovery
- **Target**: First 90 days (highest dropout risk)
- **Tone**: Gentle, real, hopeful
- **Example Prompt**:
  > "Write a short, uplifting message for someone in their first week of recovery using MAT."
- **Example Output**:
  > "You’re showing incredible courage by starting this journey. Taking your medication is strength. Try one small act of self-care today — you’re already doing more than enough."

### 2. Inclusive, Non-Stigmatizing Language
- **Use**: Person-first language (avoid "addict," "clean," "failure")
- **Purpose**: Reduce shame, support all recovery paths, especially MAT
- **Example Prompt**:
  > "Write a reflection question for someone on medication-assisted recovery that encourages pride without shame."
- **Example Output**:
  > "What’s one moment this week where you felt proud of your recovery, even in a small way? How did your medication support that?"

### 3. Group Format & App Integration
- **Format**: Short, discussion-ready prompts
- **Use Cases**: MARA meetings, digital check-ins, recovery center workbooks
- **Example Prompt**:
  > "Create a daily app check-in question that encourages MAT-friendly reflection."
- **Example Output**:
  > "What’s one thing you did today to care for yourself in recovery, like taking your medication, resting, or reaching out?"

---

## Technical Features
- **Model**: LLaMA 3 (8B Instruct)
- **Framework**: Unsloth + QLoRA (4-bit efficiency)
- **Runtime**: Google Colab (T4 GPU preferred)
- **Optimizations**:
  - Gradient checkpointing
  - Token budget for low-resource inference

---

## Advanced Suggestions (For Expansion / Fine-Tuning)
- **Few-shot Prompt Engineering**: Train with 5–10 MARA-style examples
- **Chain-of-Thought Logic**: Compassion-first reasoning for sensitive prompts
- **Bias Control**: Blocklists for stigmatizing terms (e.g., “junkie”)
- **Cultural Support**: Spanish, Indigenous language variants
- **Trauma-Informed Guardrails**: Polyvagal-theory tone tuning (e.g., avoid “you must”)

---

## Use Cases
- **MARA Group Meetings**: Open check-ins, reflections, or affirmations
- **Anonymous Haven App**: Push notifications, user-led journaling
- **Workbooks**: Print-ready affirmations and reflection prompts
- **Peer Training**: Real-time generation of motivational messages for coaching

---

## Example Workflow

1. **Setup**: Launch notebook, load Unsloth + LLaMA 3 on T4
2. **Prompt Selection**: Use included prompts or write new ones
3. **Generate Output**: Receive affirmation, check-in, or reflection
4. **Deployment**: 
   - In group (spoken)
   - In app (notification or journal)
   - In workbook (print or PDF)
5. **Feedback Loop**: Collect anonymous ratings or reactions

---

## Next Steps

- Curate 500+ recovery-style prompts for fine-tuning
- Test with MARA facilitators and peer specialists
- Explore Hugging Face API deployment
- Build feedback refinement loop (federated learning optional)
- Translate prompts into multilingual recovery templates

---

## Disclaimer
This AI toolkit supports peer-led recovery and is not a replacement for licensed clinical care. Always consult professionals for medical or mental health concerns.

---

Made with intention, lived experience, and code by Andrés + ChatGPT (Ritarte)
