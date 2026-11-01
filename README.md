# Portfolio Starter (AI-Powered Engineer Accelerator · Session 2)

Build your personal portfolio website from your resume with a coding agent,
then put it live on the internet for free with GitHub Pages.
Live in class: about 12 minutes. Finish at home if you need more time.

## What is in this folder
- AGENTS.md: the rules the agent must follow (only facts from your resume, no libraries)
- resume.md: fill this with YOUR resume text (instructions inside)
- resume-example.md: a filled example (fictional student). Do not copy it.
- prompts.md: the 5 prompts, copy-paste

## Steps

1. Unzip this folder into your cohort folder and rename it to `portfolio`.
2. Fill `resume.md` (5 min). Remove phone number, address, date of birth and ID numbers.
   This page will be public.
3. Antigravity: folder+ icon → New Project → Add Folder → `portfolio` → Create.
   Settings → Agent → Request review must be ON.
4. Prompt P1 (plan). Read the plan. Approve it.
5. Open `index.html` in your browser (double-click it). Check it on a small window too.
6. Prompt P2 (fact check), new conversation. Fix anything marked NOT FOUND.
7. Prompt P3 (rule test). The agent should refuse to invent. Screenshot it.
8. Put it live (pick one):

### Option A: upload in the browser (easiest, no git needed)
1. github.com → New repository → name: `portfolio` → Public → Create repository.
2. Click "uploading an existing file". Drag in `index.html` and `style.css`
   (and any image you used). Do NOT upload resume-example.md.
   Commit changes.
3. Settings → Pages → Build and deployment → Source: "Deploy from a branch"
   → Branch: `main`, folder: `/ (root)` → Save.
4. Wait 1–2 minutes and refresh the Pages screen. Your site is at
   `https://YOUR-USERNAME.github.io/portfolio/`

### Option B: let the agent push (if git + GitHub CLI are set up)
Prompt P5. Read every command before you approve it. Then do step 3 of Option A.

## Your check before you share the link
- [ ] Every line on the page is true and is in resume.md
- [ ] No phone number, address, date of birth or ID on the page
- [ ] Looks right on your phone
- [ ] No placeholder text left ("Lorem ipsum", "[ ]")
- [ ] Links (email, LinkedIn, GitHub) open the right page

Homework label: **S2 – Portfolio**: your live link + the rule-test screenshot.

Tip: want a shorter link (`https://YOUR-USERNAME.github.io/`)? Name the repo exactly
`YOUR-USERNAME.github.io` instead of `portfolio`.
