# Accelerated Learning Optimizer

> *Maximize learning, minimize time.*

A meticulously structured Claude skill designed to act as an expert AI tutor. It processes dense educational documents (like PDFs, lecture slides, textbooks) and distills the material using the **80/20 rule (Pareto Principle)**.

It strips away academic jargon, creates highly memorable mental models, and provides targeted multimedia (YouTube) resources to drastically reduce study time.

---

## ⚡ What it Does

When provided with educational materials, this skill forces Claude to output:

1. **🎯 The 80/20 Core:** Extracts only the absolute "Need to Know" 20% of information and explains it using simple, jargon-free English (ELI5).
2. **🧠 Hacks, Shortcuts & Mental Models:** 
   * **Mnemonics:** Ridiculous, memorable acronyms for lists.
   * **Analogies:** Relatable connections (e.g., "The CPU is like the head chef in a restaurant kitchen...").
   * **Exam Cheat Codes:** The fastest way to recognize correct answers and avoid common test-taking traps.
3. **📓 30-Second Cheat Sheet:** An ultra-condensed reference list with key formulas, definitions, or dates.
4. **📺 Visual Learning Links:** Exact-match, clickable YouTube search URLs tailored exactly to the hardest concepts in the provided materials.

---

## 🚀 How to Use It

### Using Claude Projects (Recommended)
If you have Claude Pro, you can install this skill permanently:
1. Open Claude and click **Projects** on the left sidebar.
2. Click **Create Project** and name it something like *"My AI Study Tutor"*.
3. Open the `SKILL.md` file in this repository and copy the entire text (or just the body contents).
4. Paste the text into the **"Custom Instructions"** box of your new project.
5. Upload your PDFs, syllabus, and PPTs into that project's knowledge base. Claude will automatically apply the skill anytime you chat in that project!

### Using Claude Chat (Free/Single Use)
1. Open a new chat in Claude.
2. Copy the contents of `SKILL.md` and paste it into the chat message.
3. Attach your PDF or PPT file.
4. Tell Claude: *"Please read the attached PDF and apply these rules to teach me."*

---

## 🛠 File Structure
* `SKILL.md`: The core instructional prompt file structured with YAML frontmatter to be used as a system instruction logic block.

---

*Built with ♥ for faster learning.*
