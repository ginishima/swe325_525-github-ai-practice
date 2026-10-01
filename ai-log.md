Git link: https://github.com/ginishima/swe325_525-github-ai-practice

AI prompts and responses below:
================================================================================================================================

## AI interaction 1
Date: 9 / 29 // 2026
Assistant: Microsoft Copilot
Purpose: To detail between repo, branchm commit, pull request, and issue
Prompt or summary: "Git: Explain the difference between a repository, branch, commit, pull request, and issue"
Useful suggestion: No suggestions needed from this prompt.
Decision: accepted
Reason: It gave accurate information detailing what each item was
Related GitHub URL: None

A repository is the entire project: its files and its full version history. It’s the “house where code lives,” containing commits, branches, and metadata like issues and pull requests. Repositories exist both locally (your .git folder) and remotely on GitHub.

A branch is an independent line of development inside a repository. It’s simply a movable pointer to a sequence of commits. As you commit, the branch label moves forward to the newest commit. 

A commit is a snapshot of changes with an author, timestamp, message, and parent link. It’s the fundamental unit of version history.

A pull request is a GitHub feature for proposing that changes from one branch be reviewed and merged into another. It’s not part of Git itself—it's a collaboration layer added by GitHub. 

An issue is a GitHub project-management item used to track bugs, feature requests, questions, or discussions. It’s not tied to Git’s version-control mechanics but lives inside the repository’s metadata.

================================================================================================================================

## AI interaction 2
Date: 9 / 29 // 2026
Assistant: Microsoft Copilot
Purpose: To suggest revisions to my README.md to improve it
Prompt or summary: "Review the below README.md and suggest improvements to the document: [insert readme]"
Useful suggestion:

WE 325 – Course Repository
This repository contains coursework, labs, and project materials for SWE 325, maintained by Gaige Szymanski.

📘 Purpose
The full scope of this repository will evolve as the course progresses. It will serve as a central location for:

Lab assignments

Code samples

Documentation

Project deliverables

Any additional materials developed throughout the semester

📅 Status
Currently in early development. Content and structure will expand as new labs and requirements are introduced.

Decision: revised
Reason: It was useful! I just don't want emojis in my project. Also revised some wording and took out what wasn't needed.
Related GitHub URL: https://github.com/ginishima/swe325_525-github-ai-practice/blob/main/README.md

================================================================================================================================

## AI interaction 3
Date: 9 / 29 // 2026
Assistant: Microsoft Copilot
Purpose: To suggest a pull request checklist template
Prompt or summary: "Suggest a checklist for a complete pull-request description from this github repo: https://github.com/ginishima/swe325_525-github-ai-practice"
Useful suggestion: 

# 📝 Pull Request Description

## 📌 Summary
Provide a clear, concise explanation of what this PR does.  
What problem does it solve? What feature does it add?

---

## 🔗 Related Issue(s)
Link any relevant issues, tasks, or assignment requirements.

- Closes #
- Related to #

---

## 🧠 Motivation
Explain *why* this change is necessary.  
What was missing, broken, or required by the course/lab?

---

## 🛠️ Changes Made
List the major changes so reviewers know where to focus.

- 
- 
- 

---

## 🧪 Testing Instructions
Describe how to verify the changes.

- Steps to reproduce
- Expected results
- Any test data or environment setup

---

## 📸 Screenshots / Output (If Applicable)
Add images, logs, or terminal output that help reviewers understand the change.

---

## ⚠️ Risks / Notes
Call out anything reviewers should be aware of:

- Breaking changes
- Migration steps
- Known issues
- Areas needing extra attention

---

## ✔️ PR Checklist
Before requesting review, confirm the following:

- [ ] PR title is clear and descriptive  
- [ ] Description explains *what* and *why*  
- [ ] Code follows project conventions  
- [ ] No debug code or commented‑out blocks  
- [ ] Tests added or updated (if applicable)  
- [ ] All CI checks pass  
- [ ] Linked issues included  
- [ ] Reviewer focus areas identified  

---

## 👀 Reviewer Focus
Tell reviewers exactly what parts of the code need the most attention.

Decision: revised
Reason: It was a helpful checklist, but I don't think the motivation section is necessary. Also -- No emojis!
Related GitHub URL: https://github.com/ginishima/swe325_525-github-ai-practice