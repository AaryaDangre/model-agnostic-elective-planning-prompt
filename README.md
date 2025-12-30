# model-agnostic-elective-planning-prompt
AI Prompt for Elective Planning; syllabus-driven, resume-oriented decision matrix


# 📘 Syllabus-Verified Elective Analysis Prompt

A **model-agnostic, reusable prompt** designed to help students make informed academic decisions by analyzing electives **strictly using official syllabus documents**.

---

## 🎯 Purpose

This prompt helps evaluate electives based on:
- Verified learning outcomes
- Difficulty level
- Weekly workload
- Technical and coding skills involved
- Resume-safe skills
- Career relevance

It avoids assumptions, speculation, and marketing-style advice.

---

## 🧠 Key Principles

- **Syllabus-first**: Uses only official syllabus content
- **Model-agnostic**: Works across ChatGPT, Claude, Gemini, Perplexity, etc.
- **Accuracy-focused**: Marks uncertain topics as *Not guaranteed*
- **Reusable**: Applicable across years, branches, and universities

---

## 🧩 Who Should Use This?

- Engineering / BTech students
- Students choosing electives (MDM / MDC / OE / Open Electives)
- Students optimizing workload vs skill ROI
- Anyone mapping syllabus → resume skills

---

## 📂 Files in This Repository

| File | Description |
|----|------------|
| `prompt.yaml` | Core model-agnostic prompt |
| `README.md` | Usage guide and documentation |

---
## 🚀 How to Use

1. Upload the official syllabus PDF(s) for the electives you are considering.
2. Paste the contents of `elective-planning-prompt_v1.yaml` into your AI tool.
3. Copy, edit, and run the example prompt below:

   ```text
   I am a [year] [branch] student.
   I have attached the official syllabus PDFs for the available electives.

   Compare electives using syllabus-verified learning outcomes, difficulty level,
   weekly workload, technical skills involved, and resume relevance.
   Highlight uncertainty and assumptions.

---

## 🧠 Rule to remember (useful for future READMEs)

**If the user is expected to copy and run it → use a code block.**  
*Never italics. Never quotes.*

---

## 🔄 Versioning

This project follows **semantic versioning**:

- `v1.x.x` → Stable prompt structure
- Minor updates refine wording or clarity
- Major updates change prompt logic or scope

---

## 📌 Example Usage

**Input provided to the AI:**
- Student year: Second Year
- Branch: Artificial Intelligence & Data Science
- Uploaded documents:
  - Official syllabus PDF for Image Processing
  - Official syllabus PDF for Data Analytics and Machine Learning

**Prompt used:**
- `elective-planning-prompt_v1.yaml`

**Expected output:**
- A side-by-side comparison table covering:
  - Syllabus-verified learning outcomes
  - Difficulty level
  - Estimated hours per week
  - Coding / technical skills required
  - Resume-safe skills after completion
  - Internship and industry relevance

⚠️ Topics not explicitly mentioned in the syllabus are marked as *Not guaranteed*.

---

## ⚠️ Common Mistakes to Avoid

- Relying on subject names instead of syllabus content  
- Expecting advanced topics not explicitly listed in the syllabus  
- Using marketing-style descriptions instead of verified outcomes  
- Treating difficulty or workload estimates as exact values  
- Skipping syllabus PDFs and relying only on opinions  

This prompt prioritizes **accuracy and verification** over optimistic assumptions.

---

## ⚠️ Disclaimer

This prompt assists decision-making but does not replace:
- Academic advisors
- Official departmental guidance

Always cross-check with institutional rules.

---

## 📌 License

Free to use, modify, and share for educational purposes.
